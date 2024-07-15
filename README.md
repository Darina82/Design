# Design
# Simple Python code to greet the user

# Function to greet the user
def greet_user(name):
    print(f"Hello, {name}! Welcome to the program.")

# Main program
if __name__ == "__main__":
    # Ask for user's name
    user_name = input("Please enter your name: ")
    
    # Call the greet_user function
    greet_user(user_name)
