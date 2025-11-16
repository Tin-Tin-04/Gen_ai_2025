# Gen_ai_2025
Project Summary: Generative AI Text Summarizer

This project implements a Generative AI-based text summarization system using transformer models T5 and BART. It provides an interactive tool for generating summaries of any text while offering flexibility in model choice, summary length, and additional analytical insights.

Key Features

Model Selection: Users can choose between T5 and BART models or compare both side by side.

Summary Length Control: Generate summaries of short, medium, or long lengths based on user preference.

Compression Ratio Calculation: The system calculates the ratio of summary length to original text length, giving an insight into text reduction.

Keyword Extraction: Extracts key terms from the original text to highlight main topics.

Side-by-Side Comparison: Users can view outputs from both T5 and BART simultaneously, demonstrating differences in summarization style and coverage.

Motivation

Text summarization is an essential task in NLP, useful in applications from academic research and news aggregation to business reporting and accessibility. This project demonstrates practical use of transformer-based models for abstractive summarization while providing metrics to evaluate and compare outputs.

Models Used

T5 (Text-to-Text Transfer Transformer): Converts NLP tasks into a text-to-text format. It produces concise, abstractive summaries and is lightweight for fast experimentation.

BART (Bidirectional and Auto-Regressive Transformer): Encoder-decoder model that excels at generating longer and more detailed summaries. It is useful for understanding differences in model behavior.

Implementation

Built using Python and Hugging Face Transformers library.

Gradio is used to create an interactive user interface for text input, model selection, length customization, and output display.

The system can be extended to include additional models or evaluation metrics in the future.

Applications

Academic research: quickly summarize papers or articles.

News and media: generate concise versions of articles.

Business: create executive summaries from long reports.

Accessibility: assist visually impaired users or those with limited reading time.

Text analytics: use keyword extraction and compression ratio for deeper insights.

Conclusion

This project provides a practical demonstration of transformer-based summarization. It highlights the differences between T5 and BART, offers interactive features, and delivers actionable metrics like keywords and compression ratio for better interpretability.
