# THE CIRCULAR GARDEN
## Description
This code is used to solve for several math things 

## How To Run
Simply input any number(Decimals are also allowed) for the radius and the code solves everything.

## Inputs Needed
float/integer

## Sample Output
Enter the raidus of the garden(in meters): 5

The area of the garden is 78.54 square meters
The Circumference of the garden is 31.42 meters
The square root of the area of the garden is 31.42 meters
The rounded down area of the garden is 78.00 square meters
The rounded up area of the garden is 78.00 square meters

## 1. Problem Identification
The problem, is that the school plans to create a circular garden and that we must develop a python program that will help determine the area, square root of the area, rounded up/down area, and the circumference.

## 2. Problem Decomposition
Firstly, the math library must be imported, in order to gain access to math.pi for the circumference and radius, math.pow() for the area, math.sqrt() for the square root of the area, math.floor() for the rounded down area, and lastly, math.ceil() for the rounded up area.

## 3. Pattern Recognition
Area is required for everything but the circumference,

## 4. Data Representation
The data will be expressed as numbers rounded to the second decimal place, aside for the rounded down and up areas.

## 5. Algorithm Development
#Import math library
import math

#Input radius
radius = float(input("Enter the radius of the garden(in meters): "))

#Area solution
area = math.pi * math.pow(radius, 2)

#Circumference solution
circumference = 2 * math.pi * radius

#Square root solution
square_root = math.sqrt(area)

#Rounded up/ Rounded down solution
rounded_down = math.floor(area)
rounded_up = math.floor(area)

#Final outputs
print(f"The area of the garden is {area:.2f} square meters")
print(f"The circumference of the garden is {circumference:.2f} meters")
print(f"The square root of the area of the garden is {square_root:.2f}")
print(f"The rounded down area of the garden is {rounded_down} square meters")
print(f"The rounded up area of the garden is {rounded_up} square meters")