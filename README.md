# Mood Comparison of Melodies and Lyrics in Thai Songs

A research project focused on analyzing and comparing the emotional alignment between musical melodies and song lyrics in the Thai music industry using Deep Learning techniques.

## 🎵 Project Overview

Music has a profound impact on human emotions. This study explores how the two primary components of a song—melody and lyrics—work together (or contrast) to convey specific moods. Using **Russell's Circumplex Model of Affect**, the project classifies songs into four emotional categories: **Angry, Calm, Happy, and Sad**.

## 🧠 Methodology & Models

The project utilizes specialized models for both text and audio analysis:

### 1. Lyrics Classification (Text)
*   **Data**: Scraped from LyricFind (200 Thai songs).
*   **Models Tested**: RNN (LSTM), CNN, and **WangchanBERTa**.
*   **Best Performer**: **WangchanBERTa (Fine-tuned)** achieved the highest accuracy of **75%**.

### 2. Melody Classification (Audio)
*   **Data**: Scraped from YouTube (400 Thai songs).
*   **Features**: Mel Spectrogram, Chromagram, and MFCC.
*   **Models Tested**: CNN (using VGG16 architecture).
*   **Best Performer**: **CNN with Mel Spectrogram** features achieved an accuracy of **60%**.

## 📊 Key Findings

*   The study successfully identified songs where the melody and lyrics have contrasting moods (e.g., a sad lyric with a happy melody) with **60% accuracy**.
*   The integration of these models allows for more nuanced music recommendations that account for the complex emotional layers of Thai music.

## 🛠️ Tech Stack

*   **Language**: Python
*   **Deep Learning**: TensorFlow/Keras, PyTorch, WangchanBERTa
*   **Audio Processing**: Librosa (Mel Spectrogram, MFCC, Chromagram)
*   **Web Scraping**: Selenium, BeautifulSoup
*   **Data Source**: YouTube, LyricFind

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
*Developed as part of a Project at the Data Science Department, Faculty of Science, Silpakorn University.*
