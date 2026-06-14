from collections.abc import async_generator
from os import name


class Circle:
    def __init__(self,radius):
        self.radius = radius        
    def area(self):
        print("Area of Circle",(22/7)*int(self.radius)*int(self.radius))
    def perimeter(self):
        print("Perimeter of Circle",2*(22/7)*int(self.radius))

c1 = Circle(input('Enter radius of circle: '))

c1.area()
c1.perimeter()
