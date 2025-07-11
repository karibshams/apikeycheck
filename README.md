# AI Chatbot for Mental Health Support

This project is a **Streamlit** app that integrates OpenAI's GPT model for providing therapeutic support using **Cognitive Behavioral Therapy (CBT)**, **Dialectical Behavioral Therapy (DBT)**, and **Acceptance and Commitment Therapy (ACT)**. It is designed to offer users a virtual mental health assistant with personalized guidance.

## Features

- AI-powered therapeutic assistant based on **CBT**, **DBT**, and **ACT**.
- User-friendly interface powered by **Streamlit**.
- Custom chat history to engage in ongoing conversations.
- Offers real-time responses for emotional well-being, wellness tips, mindfulness, and more.

## Technologies Used

- **Python** for the backend logic.
- **Streamlit** for the web interface.
- **OpenAI GPT-4** (or another version like GPT-3.5) for generating AI responses.
- **dotenv** for environment variable management.

## Requirements

- Python 3.7+ (or higher)
- OpenAI API Key
- Streamlit library
- dotenv for securely storing API keys

### Installing Dependencies

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/mental-health-chatbot.git
    cd mental-health-chatbot
    ```

2. Create and activate a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Ensure your `.env` file contains the **OpenAI API key**:

    Create a `.env` file in the project root and add your OpenAI API key like so:

    ```plaintext
    OPENAI_API_KEY=your-api-key-here
    ```

## Usage

1. Make sure the OpenAI API key is properly set in the `.env` file.
2. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

3. Open the URL shown in the terminal (typically `http://localhost:8501`) to interact with the chatbot.

### Example Conversation Flow

The AI chatbot can provide support in areas such as:
- Daily emotional well-being check-ins.
- Mindfulness exercises.
- Thought reframing using **CBT**.
- Emotional regulation strategies with **DBT**.
- Acceptance-based exercises with **ACT**.

**User:** "I am feeling really stressed at work, what can I do?"

**AI:** "It’s completely understandable that you’re feeling stressed. Let’s try a grounding exercise to help you refocus on the present moment. Take a few deep breaths and focus on your feet. Imagine they are firmly planted on the ground, helping you feel connected and centered."

## Contributing

Feel free to fork this project and submit pull requests. If you have suggestions for improving the functionality or making the assistant more effective, open an issue!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to contact me via GitHub or email.

---
Built with ❤️ by [Your Name]
