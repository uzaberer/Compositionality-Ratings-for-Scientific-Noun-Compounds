

`code` contains all scripts relevant for reproducing results as well as some pre-calculated feature files so you don't have to re-run any long-running code.
 * To reproduce classification results: Run `models.ipynb`. You do not need to re-run feature extraction, the provided `all_features.json` (and/or CCOHA equivalent) is sufficient.
 * To reproduce analysis: Run the relevant cells in `analysis.ipynb` or `models.ipynb`. For vector space analysis a Word2Vec model is required, for the rest `all_features.json` (and/or CCOHA equivalent) is sufficient. 
 * To re-run feature extraction: Word2Vec models, topic model(s) and a surprisal model have to be trained first. The code to train all of these is included in the feature extraction scripts.

IMPORTANT: The directory structure may be different here to when the code was running. You may have to adjust paths in the code to get the scripts running.

IMPORTANT: The notebooks are not necessarily meant to be run in full every time and you may want to skip cells depending on what you want to do. 
For example, you may want to run the feature extraction without training any Word2Vec models. Code may be commented out.