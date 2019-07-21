# DAMU
### Using NLP to synthesize new insights from research publications.
Named after a Babylonian god of healing and exorcism ("Damu binds the torn ligaments" Ebeling 1938: 115), the intent of the code in this repository is three-fold:
<ol>
  <li>To scrape the text of research journals within different sites and searches in order to create a corpus of text from research on a particular topic.</li>
  <li>Vecorize the corpus using NLTK or SpaCy.</li>
  <li>Analyze using GenSim. Analysis will focus on relationships between factors that may not have been previously recognized, but which become apparent when a corpus of text formed from thousands of research journals on a topic can be analyzed using NLP.</li>
</ol>  

The initial focus of this code will be on research journals relating to cellular senescence and the mitigation of negative factors associated with aging; however, my intent is for this code to be easily applied to other areas of research.

Files are as follows:
<ul>
  <li><b>Webscrape.ipynb</b></li>
  <p><b>Current stage.</b> This code uses the BeautifulSoup library. It takes the url returned from a search of aresearch journal site and scrapes the text from the journals returned. This text will be saved to disk.</p>
  <li>Vectorize.ipynb</li>
  <p>This code will make use of either NLTK or SpaCy to vectorize the text and tag parts of speech. This step may be divided out into more sub-steps. For instance, it may be non-trivial to ensure that chemical formulas are recognized as such. Some kind of reference may be necessary so that medical terminology can be parsed grammatically.
  <li>Analyze.ipynb</li>
  <p>The GenSim library will be used to analyze the vectorized text. Various methodologies should be explored to determine what is the most effective.
</ul>

