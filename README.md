- hozzunk létre a következő mappákat:
  - data
  - resources
  - models
  - results
    - discourse_matrices
  - vizs
    - colored_text
    - punchcard_per_discourse
    - topic
  
  
- töltsük le a data mappába a Drive-ról a "combined_transcripts_freeConv" mappát, amely a dialógusokat tartalmazza
- töltsük le a resources mappába a Drive-ról az alábbi file-okat: stopwordlist.txt, colors.txt-t
- ha az 1. notebook indításakor nem akar betölteni a huspacy és nem tudunk lemmatizálni vagy egyáltalán nem akarjuk futtatni az 1. notebookot, mert ezt a lépést ki akarjuk hagyni, akkor töltsük le a resources mappába a Drive-ról az alábbi file-okat: stopword_filtered.pkl, lemmatized.pkl, meta.pkl, docs.pkl
- ha a modelt sem akarjuk megcsinálni, csak használni, azaz ki akarjuk hagyna a 2. notebookot, akkor töltsük le a models mappába a bert_probabilites_merged.pkl-t és a results mappába a prob_matrix.csv, bert_probabilities_merged_85_new_names.csv-t.
