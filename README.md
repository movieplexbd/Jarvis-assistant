# Jarvis Assistant - CEO Titan AI

Jarvis Assistant is a next-generation Android AI Assistant built with Kotlin and Jetpack Compose. It is designed to be a powerful, offline-first personal assistant that understands natural human speech in Bangla, English, and Banglish.

## Core Features

- **Hybrid Intelligence**: Combines local offline processing with cloud-based Gemini and Groq APIs.
- **Natural Language Understanding**: Advanced engine for Bangla, English, and Banglish speech, even with slang or grammatical errors.
- **Deep Phone Automation**: Control system settings, apps (WhatsApp, YouTube), and more via accessibility services.
- **Personal Memory**: Learns user habits and maintains context across conversations.
- **Business CEO Mode**: Specialized tools for managing business ideas, notes, and reminders.

## Tech Stack

- **Language**: Kotlin
- **UI**: Jetpack Compose
- **Architecture**: MVVM Clean Architecture
- **Local AI**: Vosk, Whisper (local), Fuzzy command matcher
- **Cloud AI**: Gemini API, Groq API
- **Database**: Room, DataStore

## CI/CD

This repository includes a GitHub Actions workflow that automatically builds a debug APK on every push to the `main` branch.

## Getting Started

1. Clone the repository.
2. Open in Android Studio.
3. Configure your Gemini and Groq API keys in the app settings.

