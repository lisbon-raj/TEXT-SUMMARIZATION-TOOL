# TEXT-SUMMARIZATION-TOOL

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:LISBON RAJA B

*INTERN ID*:CT04DG3488

*DOMAIN*:ARTIFICIAL INTELLIGENCE

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTOSH

*DESCRIPTION*:
              This repository contains a comprehensive Python script designed to perform automatic text summarization using the Natural Language Toolkit (NLTK). Summarizing long passages of text is an essential task in natural language processing (NLP), and this tool simplifies the process by extracting the most relevant sentences from any given article, report, or document. The script begins by cleaning the input text, which includes removing citations in square brackets, extra whitespace, and other unnecessary characters that may interfere with accurate tokenization. Once the text is cleaned, it uses NLTK’s sent_tokenize function to split the passage into individual sentences and word_tokenize to break the text into words, ensuring a detailed analysis at the sentence and word level.

To focus on meaningful words, the script filters out common English stopwords such as “the,” “is,” and “and” using NLTK’s built-in stopword corpus. The remaining words are used to compute word frequencies, which serve as an indicator of word importance within the text. Each word’s frequency count is stored in a dictionary, incrementing the count each time the word appears. The script then scores each sentence by summing the frequencies of the important words it contains, effectively identifying sentences rich in keywords that best represent the overall content.

An additional filter is applied to exclude sentences that exceed a maximum length, avoiding overly long or complex sentences that may reduce the readability of the summary. The script employs Python’s heapq.nlargest function to select the top N highest-scoring sentences, where N is customizable by the user depending on how concise they want the summary to be. Finally, these key sentences are concatenated into a coherent summary that retains the essence of the original passage in a fraction of the length, making it perfect for quickly understanding the main points of long texts.

This summarizer is ideal for a variety of applications, including creating abstracts for research papers, generating short summaries of news articles, condensing blog posts, or building more complex NLP tools that require text summarization as a component. It demonstrates fundamental NLP techniques such as tokenization, stopword removal, word frequency analysis, and sentence scoring, serving as an excellent educational resource for those interested in learning how summarization algorithms work under the hood. The script is lightweight and easy to integrate into larger Python projects or to use as a standalone command-line tool. It requires only Python and the NLTK library, with initial downloads for the necessary tokenizer and stopword resources.

Overall, this repository offers a practical, easy-to-understand, and customizable solution for anyone looking to implement text summarization without relying on complex or transformer-based models. Whether you are a student, researcher, developer, or professional dealing with large volumes of text, this tool can help you distill information quickly and effectively. By using classic NLP methods, it avoids the computational overhead of deep learning models, making it accessible even on systems with limited resources. With clear code structure and detailed documentation, this repository provides a strong foundation for exploring more advanced summarization techniques or incorporating additional features such as keyword extraction, topic modeling, or integration with web applications.
