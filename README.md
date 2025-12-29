AI-Based Vocal and Instrumental Separator

This project is a web application that allows users to upload a song and automatically separate it into two parts:

Vocals only

Instrumental (background music only)

The motivation behind this project came from a real problem faced while practicing singing, where clean instrumental versions of songs were not always available online. This tool makes it easy to generate high-quality background tracks for practice and analysis.

Features:

Upload any audio file (MP3/WAV)

AI-powered music source separation using Demucs

Automatic loudness normalization using FFmpeg

Simple and interactive web interface using Gradio

Agent-based workflow orchestration using LangGraph

Download separated vocals and instrumental tracks

Tech Stack:

Python

Demucs (AI model for music source separation)

FFmpeg (audio processing and normalization)

Gradio (frontend UI)

LangGraph (agentic workflow orchestration)


How It Works:

User uploads an audio file through the Gradio interface.

The file is processed by an AI separation agent using Demucs.

The output vocals and instrumental tracks are post-processed using FFmpeg.

Final audio files are returned to the user for download.


Prerequisites:

Python 3.9+

FFmpeg installed and available in PATH

Demucs installed



Use Cases:

Singing practice

Music production

Audio analysis

Karaoke track creation
