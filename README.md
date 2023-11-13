# speech_to_text_vector

**job_main.py:**
- Script running Speech to Text (using Whisper) on video stored in a bucket
- Video is split in 3 sections of 3 minutes
- Transcribed text fed to GenAI to 1) create summaries and 2) extract key phrases
- Embeddings created for full transcribed text and all results pushed to Qdrant vector database
