# Ruqayyakhan.py
assignment03_variables

# Question No. 01: Calculate the sum, difference, product, and average of three numbers

# Function to perform calculations
def calculate_numbers(num1, num2, num3):
    total_sum = num1 + num2 + num3       # Sum of the numbers
    difference = num1 - num2 - num3      # Difference of the numbers
    product = num1 * num2 * num3         # Product of the numbers
    average = total_sum / 3               # Average of the numbers
    
    return total_sum, difference, product, average

# Example input
num1 = 5
num2 = 10
num3 = 15

# Get results
results = calculate_numbers(num1, num2, num3)

# Print results
print("Sum:", results[0])
print("Difference:", results[1])
print("Product:", results[2])
print("Average:", results[3])

# Question No. 02: Calculate the area of various shapes

# Function to calculate area of different shapes
def calculate_area(base, height, side, n, radius, length, width):
    area_triangle = 21 * base * height    # Area of triangle
    area_square = side ** 2                # Area of square
    area_circle = n * (radius ** 2)        # Area of circle
    area_rectangle = length * width         # Area of rectangle
    
    return area_triangle, area_square, area_circle, area_rectangle

# Example input for shapes
base = 4
height = 3
side = 5
n = 3.14  # Approximation of π
radius = 2
length = 6
width = 4

# Get area results
area_results = calculate_area(base, height, side, n, radius, length, width)

# Print area results
print("Area of triangle:", area_results[0])
print("Area of square:", area_results[1])
print("Area of circle:", area_results[2])
print("Area of rectangle:", area_results[3])
Home Home-PC MINGW32/Desktop (master)

$ git init

Reinitialized existing Git repository in C:/Users/Home/Desktop/.git/

Home@Home-PC MINGW32 ~/Desktop (master)

$ git add

fatal: Unable to create 'C:/Users/Home/Desktop/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g. an editor opened by 'git commit'. Please make sure all processes are terminated then try again. If it still fails, a git process may have crashed in this repository earlier: remove the file manually to continue.

Home@Home-PC MINGW32 ~/Desktop (master)

$ git commit m "add files" error: pathspec 'm' did not match any file(s) known to git

error: pathspec 'add files' did not match any file(s) known to git

Home@Home-PC MINGW32 ~/Desktop (master) $|Home Home-PC MINGW32/Desktop (master)

$ git init

Reinitialized existing Git repository in C:/Users/Home/Desktop/.git/

Home@Home-PC MINGW32 ~/Desktop (master)

$ git add

fatal: Unable to create 'C:/Users/Home/Desktop/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g. an editor opened by 'git commit'. Please make sure all processes are terminated then try again. If it still fails, a git process may have crashed in this repository earlier: remove the file manually to continue.

Home@Home-PC MINGW32 ~/Desktop (master)

$ git commit m "add files" error: pathspec 'm' did not match any file(s) known to git

error: pathspec 'add files' did not match any file(s) known to git

Home@Home-PC MINGW32 ~/Desktop (master) $|