# DAMU
### Using NLP to synthesize new insights from research publications.
Named after a Babylonian god of healing and exorcism ("Damu binds the torn ligaments" Ebeling 1938: 115), the intent of the code in this repository is three-fold:
<ol>
  <li>To scrape the text of research journals within different sites and searches.</li>
  <li>Since specific areas of research will contain a lot of terminology specific to themselves, to create a corpus of text from the scraped journals.</li>
  <li>Vectorize the text and analyze using NLP. Analysis will focus on relationships between factors that may not have been previously recognized, but which become apparent when a corpus of text formed from thousands of research journals on a topic can be analyzed using NLP.</li>
</ol>  

The initial focus of this code will be on research journals relating to cellular senescence and the mitigation of negative factors associated with aging; however, my intent is for this code to be easily applied to other areas of research.

Files are as follows:
<ul>
  <li><b>Webscrape.ipynb</b></li>
  <p><b>Current stage.</b> This code takes the url returned from a search of aresearch journal site and scrapes the text from the journals returned. This text will be saved to disk.</p>
  <li>BuildCorpus.ipynb</li>
  <p>Builds a corpus from the text saved by the webscraper to be utilized in NLP</p>
  <li>Vectorize.ipynb</li>
  <p>Uses the corpus to vectorize the text.</p>
  <li>Analyze.ipynb</li>
  <p>Analyis of the vectorized text will be conducted here.</p>
</ul>

