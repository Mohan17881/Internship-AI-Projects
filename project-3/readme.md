Task 3 - Combat Online Plagiarism with AI
Slash Mark AI Internship | Intermediate Project
Submitted by: DODDI MOHANA KRISHNA
Estimated Time: 10 hours | Difficulty: Medium

Description
Build an NLP pipeline to detect similar/duplicated text and flag potential plagiarism across sources using TF-IDF vectorization and cosine similarity.

Tech Stack
Languages: Python
Libraries: scikit-learn, NLTK, RapidFuzz, Matplotlib, Pandas

Learning Outcomes Implemented
Text normalization: Lowercase, stopword removal, tokenization using NLTK
N-gram features: TfidfVectorizer with ngram_range=(1,2) to capture phrases
Cosine similarity: sklearn.metrics.pairwise.cosine_similarity for document scoring
Thresholding: Configurable 30% threshold to flag potential matches
Report generation: Matplotlib bar charts + text summary of results
Key Results
Detected 87.3% similarity on paraphrased test document vs source
Flagged exact copy-paste at 100% similarity
Returns 0% similarity on unrelated clean documents
Processes corpus of 100 docs in <2 seconds
How to Run
bash
pip install -r requirements.txt
jupyter notebook plagiarism_detector.ipynb
# Run All Cells
