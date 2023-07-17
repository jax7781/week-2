# week-2
Scripts for Week 2
def calculate_surface_area(edge_length):
    surface_area = 6 * (edge_length ** 2)
    return surface_area

edge1 = 5
area1 = calculate_surface_area(edge1)
print("The surface area of the cube with edge length", edge1, "is:", area1)

edge2 = 7.5
area2 = calculate_surface_area(edge2)
print("The surface area of the cube with edge length", edge2, "is:", area2)

NEW_VIDEO_PRICE = 3.00
OLD_VIDEO_PRICE = 2.00

num_new_videos = int(input("Enter the number of new videos rented: "))
num_old_videos = int(input("Enter the number of old videos rented: "))

total_cost = (num_new_videos * NEW_VIDEO_PRICE) + (num_old_videos * OLD_VIDEO_PRICE)

print("Total charge for the video rentals: $", total_cost)

import math

radius = float(input("Enter the radius of the sphere: "))

diameter = 2 * radius

circumference = 2 * math.pi * radius

surface_area = 4 * math.pi * radius ** 2

volume = (4/3) * math.pi * radius ** 3

print("Sphere's Diameter:", diameter)
print("Sphere's Circumference:", circumference)
print("Sphere's Surface Area:", surface_area)
print("Sphere's Volume:", volume)
