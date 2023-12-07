import math

def hexagon_properties(side_length):
    # Calculate the area of the hexagon
    area = (3 * math.sqrt(3) * (side_length ** 2)) / 2

    # Calculate the perimeter of the hexagon
    perimeter = 6 * side_length

    return area, perimeter

side_length = float(input("Enter the side length of the hexagon: "))
area, perimeter = hexagon_properties(side_length)

print("The area of the hexagon is: ", area)
print("The perimeter of the hexagon is: ", perimeter)
