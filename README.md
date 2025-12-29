Project Overview

This project is an AI-powered web application designed to separate a song into two distinct audio tracks: vocals and background music. It addresses a common problem faced by singers and music enthusiasts who struggle to find clean instrumental versions of songs online. By allowing users to upload any audio file and process it locally using AI models, the application provides a reliable and high-quality alternative for singing practice and music analysis.

*Features*

Upload any audio file (MP3/WAV)

AI-powered music source separation using Demucs

Automatic loudness normalization using FFmpeg

Simple and interactive web interface using Gradio

Agent-based workflow orchestration using LangGraph

Download separated vocals and instrumental tracks


*Tech Stack*

-Python
-Demucs (AI model for music source separation)
-FFmpeg (audio processing and normalization)
-Gradio (frontend UI)
-LangGraph (agentic workflow orchestration)


*How It Works*

-User uploads an audio file through the Gradio interface.

-The file is processed by an AI separation agent using Demucs.

-The output vocals and instrumental tracks are post-processed using FFmpeg.

-Final audio files are returned to the user for download.


*Prerequisites*

-Python 3.9+

-FFmpeg installed and available in PATH

-Demucs installed


*Use Cases*

Singing practice

Music production

Audio analysis

Karaoke track creation
