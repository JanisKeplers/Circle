# Calculate the area of a circle

def calculate_circle_area(radius):
    """
    Calculate the area of a circle given its radius.

    Args:
        radius (float): The radius of the circle.

    Returns:
        float: The area of the circle.
    """
    pi = 3.14159
    area = pi * radius**2
    return area

# Example usage
radius = 5.0
print("Radius:", radius)
print("Area:", calculate_circle_area(radius))
