```markdown
# Near Duplicate Detection using Jaccard's Index

This Jupyter notebook demonstrates how to create a machine learning model trained on Jaccard's Index. The goal is to quickly and accurately determine how similar input text compares to stored text. The definition of "duplicate" includes similarity in words, sentences, or paragraphs even if they have been rearranged.

## Colab Notebook Link
[Open in Colab](https://colab.research.google.com/github/anjal-amin/dedupe/blob/main/near_dupe_detection.ipynb)

## Dependencies
Ensure you have the required dependencies installed:
```bash
pip install faiss-gpu
pip install nltk
```

## Usage
1. Run the notebook cells sequentially.
2. The notebook uses a sample dataset and computes Jaccard similarity.
3. The model is trained using a K-Nearest Neighbors Regressor.
4. Mean Squared Error is calculated for evaluation.

Feel free to customize the notebook for your specific use.