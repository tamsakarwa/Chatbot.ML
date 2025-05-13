# Machine Learning Chatbot using Python

This project is a simple machine learning–based chatbot implemented in Python. It uses NLP techniques (tokenization, lemmatization) and a classifier (`scikit-learn`) to understand user intents and respond accordingly.

## Features
- Rule-based + ML intent classification
- Customizable intents from a JSON file
- NLP preprocessing using `nltk`
- Simple command-line interface for chatting

## Technologies Used
- Python
- NLTK (Natural Language Toolkit)
- NumPy
- Scikit-learn (SVM or Logistic Regression)

## Project Files

| File | Description |
|------|-------------|
| `chatbot.py` | Main chatbot logic and ML model training |
| `intents.json` | Custom training data (intents, patterns, responses) |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |

## How to Run

1. Clone the repo (after you push it to your GitHub):
```bash
git clone https://github.com/yourusername/ML-Chatbot.git
cd ML-Chatbot
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

3. Run the chatbot:
```bash
python chatbot.py
```

## Sample Intent Format (intents.json)

```json
{
  "intents": [
    {
      "tag": "greeting",
      "patterns": ["Hi", "Hello", "How are you"],
      "responses": ["Hello!", "Hi there!", "Greetings!"]
    }
  ]
}
```

## Future Improvements
- Add a GUI using Tkinter or Streamlit
- Add voice input/output using `speech_recognition` and `pyttsx3`
- Use a neural network (e.g., TensorFlow or Transformers)

## Author
Made by Tamsa Karwa  
[GitHub Profile](https://github.com/tamsakarwa)

