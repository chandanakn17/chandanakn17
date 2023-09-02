
def calculate_area(side_length):
    return side_length ** 2
side_length = float(input("Enter the side length of the square: "))

area_of_square = calculate_area(side_length)

print("The area of the square with side length", side_length, "is:", area_of_square)

