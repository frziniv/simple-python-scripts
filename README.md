# This is a simple script to greet the user.

def greet_user():
    """
    Prompts the user for their name and then prints a personalized greeting.
    """
    # Ask the user to enter their name
    name = input("Please enter your name: ")

    # Create a greeting message
    greeting_message = f"Hello, {name}! Welcome."

    # Print the message
    print(greeting_message)

# Call the function to run the script
if name == "main":
    greet_user()
