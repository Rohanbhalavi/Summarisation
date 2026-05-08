LLM Summarisation

### Steps
1. Add Colab-specific setup: install required packages (`PyPDF2`, `transformers`, `tiktoken` or alternatives, etc.).
2. Replace OpenAI and LangChain code with Hugging Face `transformers` pipeline for summarization.
3. Update token counting to use a compatible tokenizer (e.g., from `transformers`).
4. Adjust PDF reading and text extraction for compatibility and robustness.
5. Save the summary output as `Summary.txt` in the Colab environment.
6. Add markdown cells with clear instructions for each step.

### Further Considerations
1. Which free LLM? (e.g., `facebook/bart-large-cnn`, `google/pegasus-xsum`, or similar on Hugging Face)
2. Colab GPU/CPU availability may affect model choice and performance.
3. Large PDFs may need chunking for summarization due to model input limits.

Please review this draft plan and specify if you have a preferred free LLM or any other requirements.## Plan: Convert Notebook for Google Colab with Free LLM

Convert the provided notebook to run smoothly on Google Colab, replacing paid/proprietary LLMs (like OpenAI's GPT) with a free, industry-available LLM (such as Hugging Face's `transformers` models). Ensure all code is runnable in Colab, with clear installation and usage instructions.

### Steps
1. Add Colab-specific setup: install required packages (`PyPDF2`, `transformers`, `tiktoken` or alternatives, etc.).
2. Replace OpenAI and LangChain code with Hugging Face `transformers` pipeline for summarization.
3. Update token counting to use a compatible tokenizer (e.g., from `transformers`).
4. Adjust PDF reading and text extraction for compatibility and robustness.
5. Save the summary output as `Summary.txt` in the Colab environment.
6. Add markdown cells with clear instructions for each step.

### Further Considerations
1. Which free LLM? (e.g., `facebook/bart-large-cnn`, `google/pegasus-xsum`, or similar on Hugging Face)
2. Colab GPU/CPU availability may affect model choice and performance.
3. Large PDFs may need chunking for summarization due to model input limits.
