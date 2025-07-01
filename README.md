# Filmception
AI-powered tool that classifies movie genres, translates summaries into multiple languages, and generates voiceovers — all via a simple interface.
# AI Tool for Movie Genre Prediction, Translation & Voiceover

This project is an AI-powered application that performs three key tasks:
1. Classifies the genre of a movie based on its plot summary,
2. Translates the summary into multiple languages, and
3. Generates audio narration for the translated summaries.

A graphical user interface (GUI) built with Tkinter allows users to interact with all features in an accessible way.

## Features

- **Movie Genre Classification**  
  Uses a machine learning model trained on movie plot summaries to predict genres such as Action, Comedy, Drama, etc.

- **Multilingual Translation**  
  Automatically translates English summaries into languages including Urdu and Arabic using a pre-trained NLP model.

- **Text-to-Speech (TTS) Conversion**  
  Converts translated text into speech using Google Text-to-Speech (gTTS).

- **User-Friendly GUI**  
  Built with Tkinter to allow users to enter a summary, view predictions, hear audio, and see translated text.

## Dataset Information

The project uses the **CMU Movie Summary Corpus**, which contains plot summaries and metadata for thousands of movies.  
**Note**: Due to file size and licensing, the dataset is not uploaded to this repository.  

Specifically:
- `plot_summaries.txt`  
- `movie.metadata.tsv`

Place the files in the appropriate data directory as referenced in the code.

## Technologies Used

- Python 3.x
- Scikit-learn
- Transformers (Helsinki-NLP)
- gTTS (Google Text-to-Speech)
- Pandas, NumPy
- NLTK / spaCy
- Tkinter (GUI)
- Matplotlib (for optional visualization)


## How to Run

1. Install Python 3.x.
2. Download the dataset and place it in the appropriate folder.
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
4. Run the notebook Project_22I-1565_22I-1776.ipynb or launch the GUI script.
5. Use the interface to input a summary and explore predictions, translations, and audio.

Acknowledgements
This project was developed as the final submission for the Artificial Intelligence course at FAST National University, Islamabad.

