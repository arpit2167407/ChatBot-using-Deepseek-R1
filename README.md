# 🧠 DeepSeek Code Companion
DeepSeek Code Companion is an AI-powered coding assistant built using Streamlit, LangChain, and Ollama. It provides real-time assistance for coding tasks, debugging, code documentation, and solution design. Whether you're writing new code or debugging an existing project, DeepSeek helps by providing concise, strategic, and accurate suggestions with debugging support.

# Key Features
* 🐍 Python Expert: Assists with Python code generation, debugging, and optimization.
* 🐞 Debugging Assistant: Suggests code improvements and debugging tips.
* 📝 Code Documentation: Automatically generates documentation for your code.
* 💡 Solution Design: Provides guidance for designing algorithms and software systems.

# 🔧 Built With
* Ollama: The model behind the AI assistant.
* LangChain: A framework for developing language model-powered applications.
* Streamlit: For building the interactive UI.

⚙# Configuration Options
* Choose Model: Select the AI model to use for generating responses (deepseek-r1:1.5b, deepseek-r1:3b).
* Model Capabilities: This section highlights what DeepSeek can help you with:
* Python expertise
* Debugging assistance
* Code documentation
* Solution design
# 🛠️ How to Use
1. # Install Dependencies:
Ensure you have Python installed and the necessary dependencies. You can install them by running:
pip install streamlit langchain langchain-ollama

2. # Run the Application:
To start the DeepSeek Code Companion app, run the following command in your terminal:
streamlit run app.py

3. # Interacting with DeepSeek:

Type your coding questions in the input box and submit.
DeepSeek will process your query and respond with the solution, complete with debugging advice and print statements for easy debugging.
# 📝 Project Structure
app.py: The main file that sets up the Streamlit interface and handles the interaction with LangChain and Ollama models.
styles.css: Custom CSS for styling the app’s interface.
# 🏗️ Features to Be Implemented
a. Multi-language support.
b. Saving and retrieving past sessions.
c. Integration with GitHub for code version control.
# 👨‍💻 Contributing
Feel free to contribute! If you want to add more features, fix bugs, or improve the documentation, create a pull request or open an issue.

