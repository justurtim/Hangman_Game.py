🤖 Simple Rule-Based Chatbot

A beginner-friendly rule-based chatbot built with Python. The chatbot responds to specific user inputs using predefined rules and replies.

📌 Features

Responds to greetings like hello

Responds to how are you

Says goodbye when the user types bye

Handles unknown inputs with a default response

Simple command-line interface

No external libraries required

🛠️ Technologies Used

Python 3

input()

if / elif / else

String methods

📂 Project Structure
simple-chatbot/
│
├── chatbot.py
└── README.md

🚀 How to Run
1. Clone the repository
git clone https://github.com/your-username/simple-chatbot.git

2. Open the project folder
cd simple-chatbot

3. Run the chatbot
python chatbot.py

💬 Example Conversation
Chatbot: Hello! I'm a simple chatbot.
Chatbot: Type 'bye' to exit.

You: hello
Chatbot: Hi!

You: how are you
Chatbot: I'm fine, thank you!

You: what is your name
Chatbot: Sorry, I don't understand that.

You: bye
Chatbot: Goodbye! Have a nice day!

🧠 How It Works

The chatbot uses simple if-elif-else rules to match the user's input with predefined phrases.

For example:

if user_input == "hello":
    print("Chatbot: Hi!")

elif user_input == "how are you":
    print("Chatbot: I'm fine, thank you!")

elif user_input == "bye":
    print("Chatbot: Goodbye!")


If the input doesn't match any rule, the chatbot displays a default response.

🔮 Future Improvements

Add more questions and responses

Support multiple variations of the same question

Add a graphical user interface (GUI)

Store conversations

Add more advanced natural-language processing

👨‍💻 Author

Your Name

⭐ If you found this project useful, consider giving the repository a star!
