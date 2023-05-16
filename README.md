def calculate_sum(numbers):
    total = 0
    for num in numbers:
        total += num
    return total

# Example list of numbers
numbers = [1, 2, 3, 4, 5]

# Calculate the sum of numbers in the list
result = calculate_sum(numbers)

# Display the result
print("The sum of numbers is:", result)
