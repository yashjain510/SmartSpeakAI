# SmartSpeakAI

This project is a Python-based speech processing application that leverages Natural Language Processing (NLP) libraries to perform various tasks such as word meaning retrieval, spelling correction, sentence correction, and translation.

## Features

- **Get Meaning of a Word**: Recognizes spoken words and provides their meanings using WordNet.
- **Correct Spelling in a Sentence**: Recognizes spoken sentences and corrects their spelling using TextBlob.
- **Correct Sentence**: Recognizes spoken sentences and corrects them grammatically using TextBlob.
- **Translate Spoken Text to English**: Recognizes spoken sentences and translates them to English using Google Translate.

## Requirements

- Python 3.x
- NLTK
- TextBlob
- SpeechRecognition
- Pyttsx3
- Googletrans

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/speech-processing-app.git
   cd speech-processing-app
   ```

2. Install the required packages:
   ```bash
   pip install nltk textblob SpeechRecognition pyttsx3 googletrans==4.0.0-rc1
   ```

3. Download the necessary NLTK data:
   ```python
   import nltk
   nltk.download('punkt')
   ```

## Usage

Run the main script to start the application:
```bash
python main.py
```

### Options

1. **Get meaning of a word**:
   - Speak a word, and the application will provide its meaning.

2. **Correct spelling in a sentence**:
   - Speak a sentence, and the application will correct its spelling.

3. **Ask sentence to be corrected**:
   - Speak a sentence, and the application will correct it grammatically.

4. **Translate spoken text to English**:
   - Speak a sentence, and the application will translate it to English.

5. **Exit**:
   - Exit the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [NLTK](https://www.nltk.org/)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [Pyttsx3](https://pypi.org/project/pyttsx3/)
- [Googletrans](https://pypi.org/project/googletrans/)
