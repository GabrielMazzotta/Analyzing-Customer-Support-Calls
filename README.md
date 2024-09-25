<p><img alt="Phone Call" src="./customer_support_icon.jpg">


# Speech Recognition & Sentiment Analysis - Analyzing Customer Support Calls

## Background and Project Goals

A retail company is on a transformative journey, aiming to elevate their customer services through cutting-edge advancements in Speech Recognition and Natural Language Processing (NLP).

The goal is to transcribe customer support audio calls, evaluate customers' sentiment, uncover common named entities and search most similar context to a query.

We are tasked with developing functionalities that not only convert customer support audio calls into text but also explore methodologies to extract insights from transcribed texts.

In this dynamic project, I leverage the power of `SpeechRecognition`, `Pydub`, and `spaCy` – three open-source packages that form the backbone of my solution. The objectives are:
  - Transcribe a sample customer audio call, stored at `sample_customer_call.wav`.
  - Analyze sentiment, identify common named entities, and enhance user experience by searching for the most similar customer calls based on a given query from a subset of their pre-transcribed call data, stored at `customer_call_transcriptions.csv`.


## Dataset

The dataset contains 102 pre-transcribed customers calls with a sentiment label assigned and a sample customer audio call.


## Libraries

- spaCy
- nltk (VADER)
- Pydub
- speech_recognition
- Pandas

## Possible Enhancements

Here are some features that could enhance the functionality of this project:

- **Speaker Diarization**: Implement speaker diarization to distinguish between multiple speakers in the audio and assign transcriptions to the appropriate speaker.
  
- **Punctuation Restoration**: Add a system to automatically restore punctuation to the transcribed text for improved readability.

- **Named Entity Recognition (NER) on Audio**: Extend NER functionality to detect and highlight important entities directly from the audio transcription.

- **Keyword Spotting (KWS)**: Implement keyword spotting to highlight and extract specific key terms (e.g., product names, issues) from customer call transcriptions.

- **Emotion Recognition**: Incorporate emotion detection to analyze the emotional tone of the speaker from the audio data.

- **Real-Time Speech Transcription**: Enable real-time speech transcription, allowing the system to process and display transcriptions as the audio is being recorded.