# COSMMIC
 Developed multilingual reader-aware news summarization systems across 9 Indian languages using the
COSMMIC dataset containing 4,959 article-image pairs and 24,484 reader comments.<br>
• Fine-tuned Gemma-7B using parameter-efficient LoRA adaptation under four training strategies, leveraging
language-specific COSMMIC data and UPDESH (9.5M+ instruction-response pairs across 13 Indian
languages) for instruction tuning and multilingual pre-adaptation.<br>
• Trained and merged 9 language-specific LoRA adapters through parameter averaging to build a unified
multilingual summarization model; evaluated performance using ROUGE-1, ROUGE-L, and BERTScore,
achieving consistently superior results over joint multilingual fine-tuning<br>
