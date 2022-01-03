README
------

Directory Structure:

static
  |___ style.css (Style Sheet for html files)
templates
  |___ home.html (Renders the default home page)
  |___ manual.html (Renders the manual entry page for review data)
  |___ result.html (Renders the result page after model prediction)
LogReg.pkl (The saved Logistic Regression model that generates the predictions under the hood
download_sentence_transformer.py (Commands used to download and save st_model folder) 
run.py (The main python file running the Flask application which carries out all the computation)
gibberish_classifier.py (The Python classifier which checks if review text entered is gibberish - if yes, it asks user to re-enter review data)
st_model (The Sentence Transformer model that is used to generate paragraph embeddings from text data in run.py)
