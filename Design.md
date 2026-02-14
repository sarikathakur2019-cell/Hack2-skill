# SakhiAI – System Design

## Architecture Overview

User → Chat Interface → Backend Server → OpenAI API → Response → User

## Modules

1. User Input Module
   - Accepts text in Hindi or English

2. Emotion Detection Module
   - Uses AI to classify emotions

3. Response Generator
   - Provides supportive and safe replies

4. Helpline Module
   - Shows emergency support numbers

## Safety Measures
- No medical diagnosis
- Emergency detection for self-harm keywords
- Redirect to national helplines

## Scalability
- Cloud hosted (AWS)
- API-based modular system
