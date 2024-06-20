



# Mental Health Support Chatbot

This project is a Mental Health Support Chatbot built using [Streamlit](https://streamlit.io/) and powered by [OpenAI's GPT-3.5-turbo model](https://platform.openai.com/docs/models/gpt-3-5-turbo). The chatbot provides mental health support through a conversational interface, offering sentiment analysis, mood tracking, and personalized coping strategies based on user input.

## Features

- **Chat Interface**: Engage with the chatbot in a user-friendly interface.
- **Sentiment Analysis**: Analyze the sentiment of user messages and classify emotions.
- **Mood Tracking**: Track user mood over time based on their interactions.
- **Personalized Coping Strategies**: Offer tailored strategies based on the user's emotional state.
- **Session Summaries**: Summarize the chat session and provide insights.
- **Helpful Resources**: Provide links to immediate help resources for mental health support.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your_username/mental-health-support-chatbot.git
    cd mental-health-support-chatbot
    ```

2. **Create a virtual environment and activate it:**
    - On Windows:
      ```bash
      python -m venv env
      .\env\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      python3 -m venv env
      source env/bin/activate
      ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up your OpenAI API key:**
    - Obtain your OpenAI API key from [OpenAI](https://platform.openai.com/account/api-keys).
    - Set your API key as an environment variable `OPENAI_API_KEY` or replace `'your_openai_api_key'` in the code with your actual API key.

## Usage

1. **Run the Streamlit application:**
    ```bash
    streamlit run app.py
    ```

2. **Open the provided URL (typically `http://localhost:8501`) in your web browser.**

3. **Interact with the chatbot:**
    - Enter your message in the input box and click "Send."
    - The chatbot will respond, analyze your sentiment, track your mood, and suggest coping strategies as appropriate.

## Project Structure

- `app.py`: Main application file containing the Streamlit code and chatbot logic.
- `requirements.txt`: List of required Python packages.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [OpenAI](https://openai.com/)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)

## Resources

If you need immediate help, please contact one of the following resources:
- National Suicide Prevention Lifeline: 1-800-273-8255
- Crisis Text Line: Text 'HELLO' to 741741
- [More Resources](https://www.mentalhealth.gov/get-help/immediate-help)

---

