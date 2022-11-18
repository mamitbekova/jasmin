# jasmin
my project
# Program make a simple calculator

# This function adds two numbers
def add(x, z):
    return x + z

# This function subtracts two numbers
def subtract(x, z):
    return x - z

# This function multiplies two numbers
def multiply(x, z):
    return x * z

# This function divides two numbers
def divide(x, z):
    return x / z


print("Select operation.")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

while True:
    # take input from the user
    choice = input("Enter choice(1/2/3/4): ")
