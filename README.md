**#Area Calculator**
import math
pi = math.pi
def calculate_area(shape, dimensions):
    shape = input('Enter shape (circle, rectangle, triangle, square): ')
        if shape == 'circle':
         radius = float(input('Enter radius: '))
        area = calculate_area(shape, [radius])
    elif shape == 'rectangle':
        length = float(input('Enter length: '))
        width = float(input('Enter width: '))
        area = calculate_area(shape, [length, width])
    elif shape == 'triangle':  
        base = float(input('Enter base: '))
        height = float(input('Enter height: '))
        area = calculate_area(shape, [base, height])
    elif shape == 'square':
        side = float(input('Enter side length: '))
        area = calculate_area(shape, [side])    
    else:
        area = 'no recognized shape' 
