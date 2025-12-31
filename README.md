# VERBANOVA

A Python-based command-line application that uses Google’s Gemini Generative AI API to translate romanized text (text written using English letters but belonging to another language) into clear, natural-sounding English.

This tool is useful for translating informal or transliterated text such as:

Hinglish (Hindi in English letters)

Romanized Telugu, Tamil, or other Indian languages

Chat-style or social media text

#  Features

Translates romanized text into fluent English

Uses Google Gemini (gemini-2.5-pro / gemini-pro) for high-quality translation

Simple command-line interface

Handles empty input and API errors gracefully

Easy to configure and extend

# Tech Stack

Python 3

Google Generative AI (Gemini API)

Jupyter / Google Colab compatible

Command-line interface

# Get a Gemini API Key

Go to: https://aistudio.google.com/

Create a new project (if needed)

Generate an API key

Enable the Generative Language API for your project

# Configure the API Key

Open translator.py and replace:

YOUR_GEMINI_API_KEY = "PASTE_YOUR_API_KEY_HERE"

with your actual key:
YOUR_GEMINI_API_KEY = "your_real_api_key_here"

# Example
Enter Text > kal tum office jaoge kya
Output:
English: Will you go to the office tomorrow?

# How It Works

The user enters romanized text in the terminal.

The input is sent to the Gemini model with a prompt requesting translation.

Gemini generates and returns the English translation.

The program prints the translated output and exits.

#Author

SK. Zaafira Yumn
B.Tech CSE (AI & ML), VIT-AP University
