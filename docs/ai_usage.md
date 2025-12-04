# AI Use Log
- Tool/model & version: Colab's Gemini
- What I asked for: graphing data
- Snippet of prompt(s): "Create a series of bar graphs to compare the performance metrics [of trained models]"
- What I changed before committing: Deleted some of the output cells that weren't relevant to my question (e.g., step-by-step explanations, interpreting graphs)
- How I verified correctness (tests, sample data): N/A
---
- Tool/model & version: GPT-5.1
- What I asked for: graphing data
- Snippet of prompt(s): "How would coloring UMAP work if labels/classes are overlapping"
- What I changed before committing: Adapted/personalized graphing code for the data and the intended purpose
- How I verified correctness (tests, sample data): N/A
---
- Tool/model & version: GPT-5.1
- What I asked for: error handling
- Snippet of prompt(s): "help with this error 

      ---------------------------- UFuncTypeError Traceback (most recent call last)
      /tmp/ipython-input-2899040328.py in <cell line: 0>() 
      5 y_prob=chain.predict_proba(X_test) 
      6 
      ----> 7 jaccard_score(Y_test, y_pred, labels=list(df.columns)[-6:], average='samples')
  [...]"

- What I changed before committing: removed indicated error in code (the `labels` argument)
- How I verified correctness (tests, sample data): N/A
---
- Tool/model & version: GPT-5.1
- What I asked for: modifying existing code
- Snippet of prompt(s): "I want to investigate overfitting, but accuracy is super harsh in this context, I want to change to jaccard_score, what the best way to do that?"
- What I changed before committing: personalizing code for data and intended purpose
- How I verified correctness (tests, sample data): N/A
---
- Tool/model & version: GPT-5.1
- What I asked for: modifying existing code
- Snippet of prompt(s): "Would this work for a PCA scree plot:

      ...
      pca = PCA(n_components=80,random_state=1203)
      pca_fit = pca.fit(X_train_scaled)

      PC_values = np.arange(pca.n_components_) + 1

      plt.plot(PC_values, pca.explained_variance_ratio_, marker='o')
      plt.title('Scree Plot')
      plt.xlabel('Principal Component')
      plt.ylabel('Variance Explained')
      plt.show()
  "
- What I changed before committing: adding np.cumsum() to make plot curve easier to interpret
- How I verified correctness (tests, sample data): N/A
---
