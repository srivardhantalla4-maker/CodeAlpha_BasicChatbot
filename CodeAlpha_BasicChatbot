# Display chatbot title and exit instruction
print("========== BASIC CHATBOT ==========")
print("Type 'bye' to exit the chatbot.")

# Function to generate chatbot responses
def chatbot_response(user_input):

    # Greet the user
    if user_input == "hello" or user_input == "hi" or user_input == "hey":
        print("Bot: Hi! Welcome.")

    # Respond to user's well-being question
    elif user_input == "how are you":
        print("Bot: I'm fine, thank you!")

    # Tell the chatbot's name
    elif user_input == "what is your name":
        print("Bot: I'm a simple Python chatbot.")

    # Respond to current activity
    elif user_input == "what are you doing":
        print("Bot: I'm chatting with you!")

    # Explain chatbot capabilities
    elif user_input == "what can you do" or user_input == "what you will do":
        print("Bot: I can chat with you and answer simple questions.")

    # Provide help information
    elif user_input == "help":
        print("Bot: You can ask me about my name, how I am, or just say hello!")

    # Give information about Python
    elif user_input == "what is python":
        print("Bot: Python is a high-level programming language known for its simplicity and readability.")

    # Give information about AI
    elif user_input == "what is ai":
        print("Bot: AI stands for Artificial Intelligence, which is the simulation of human intelligence in machines.")

    # Give information about Machine Learning
    elif user_input == "what is machine learning":
        print("Bot: Machine Learning is a subset of AI that allows systems to learn and improve from experience without being explicitly programmed.")

    # Give information about Deep Learning
    elif user_input == "what is deep learning":
        print("Bot: Deep Learning is a subset of Machine Learning that uses neural networks with many layers to analyze complex data.")

    # Give information about Natural Language Processing
    elif user_input == "what is natural language processing":
        print("Bot: Natural Language Processing (NLP) is a field of AI that focuses on the interaction between computers and humans through natural language.")

    # Respond to user's gratitude
    elif user_input == "thank you" or user_input == "thanks" or user_input == "thank you very much":
        print("Bot: You're welcome!")

    # Respond to favorite color question
    elif user_input == "what is your favorite color":
        print("Bot: I don't have a favorite color, but I like all colors equally!")

    # Exit the chatbot
    elif user_input == "bye":
        print("Bot: Goodbye! Have a great day!")
        return True

    # Handle unknown questions
    else:
        print("Bot: Sorry, I don't understand that.")

    # Continue the chatbot loop 
    return False


# Main chatbot loop
while True:

    # Get user input
    user_input = input("You: ").lower()

    # Call the chatbot function and exit if requested
    if chatbot_response(user_input):
        break
