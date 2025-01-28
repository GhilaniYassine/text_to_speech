# 🎙️ Kokoro Text-to-Speech Demo

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A personal exploration of the state-of-the-art Kokoro text-to-speech model.

## 🚀 Features

- 🗣️ Multiple voice options (male/female)
- 🎵 High-quality 24kHz audio output
- 🎭 Support for different speaking styles
- 🔊 Natural-sounding speech synthesis

## 📋 Requirements

```bash
pip install -r requirements.txt
```

## About Kokoro
Kokoro is an advanced neural text-to-speech model that can generate high-quality speech in multiple voices. The model used in this demo is Kokoro-82M, which offers:

Multiple voice options including male and female voices
High quality natural-sounding speech synthesis
Support for different speaking styles
24kHz audio output

## Dependencies
- torch 
- transformers
- phonemizer
- scipy
- munch
- espeak-ng

## Available Voices
The demo includes several voice options:

Default mixed voice (af)
Female voices: af_bella, af_sarah, bf_emma, bf_isabella, af_nicole, af_sky
Male voices: am_adam, am_michael, bm_george, bm_lewis

## Usage
The notebook provides a simple interface to:

Load the Kokoro model
Select a voice
Input text
Generate and play synthesized spe

## note 
This is a personal exploration project to understand and showcase the capabilities of the Kokoro text-to-speech system.


git remote set-url origin https://<>@github.com/GhilaniYassine/TEXT_TO_SPEECH.git