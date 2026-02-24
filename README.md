# test
testing 
print =("""press 1 to get the area of square
press 2 to get the area of rectangle
press 3 to get the area of circle
press 4 to get the area of triangle""") 

count = int(input("enter the number: "))
if count == 1:
    side = float(input("Enter the side of the square: "))
    area = side*side
    print("The area of the square is:", area)
elif count == 2:
    length = float(input("Enter the length of the rectangle: "))
    breadth = float(input("Enter the breadth of the rectangle: "))
    area = length*breadth
    print("The area of the rectangle is:", area)
elif count == 3:
    radius = float(input("Enter the radius of the circle: "))
    area = 3.14*radius*radius
    print("The area of the circle is:", area)
elif count == 4:
    base = float(input("Enter the base of the triangle: "))
    height = float(input("Enter the height of the triangle: "))
    area = 0.5*base*height
    print("The area of the triangle is:", area)
else:
    print("Invalid input")
