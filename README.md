🎤 Voice-to-SQL System with Wav2Vec2 & T5

This project demonstrates a Voice-to-SQL system that converts spoken or written natural language queries into SQL statements.
It is designed to assist non-technical users in interacting with databases by removing the need to learn SQL syntax.

✨ Overview
Accepts both voice and text inputs.
Uses Wav2Vec2 for speech-to-text and T5-small for text-to-SQL generation.
A custom projection layer bridges audio and text representations for improved accuracy.
Implemented and tested entirely in Python Jupyter Notebook using PyTorch and Hugging Face Transformers.

📊 Model Performance
BLEU Score: 85%
ROUGE-L: 81.4%
Word Error Rate (WER): 4.4%
Training Loss: 0.1074
These results indicate the model’s robust ability to generate accurate SQL queries from both text and audio inputs.

🛠 Tech Stack
Language: Python
Framework: PyTorch
Libraries: Hugging Face Transformers (Wav2Vec2, T5)

📈 Key Learnings
Combining speech recognition (Wav2Vec2) with natural language to SQL translation (T5) provides a powerful pipeline for database accessibility.
Preprocessing and handling multimodal data (audio + text) is crucial for performance.
The system reduces the barrier for non-technical users by letting them query databases naturally.

🔮 Future Scope
Deploy as a web or mobile application for real-time use.
Extend support to complex SQL queries (joins, nested queries, etc.).
Optimize for low-resource environments and faster inference.
