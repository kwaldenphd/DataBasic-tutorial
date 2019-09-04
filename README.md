# DataBasic Tutorial

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
DataBasic tutorial by <a href="dlac.grinnell.edu" rel="cc:attributionURL">Katherine Walden, Digital Liberal Arts Specialist (Grinnell College)</a> is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

## What is DataBasic?

According to [its website,](https://databasic.io) “DataBasic is a suite of easy-to-use web tools for beginners that introduce concepts of working with data. These simple tools make it easy to work with data in fun ways, so you can learn how to find great stories to tell.” DataBasic is developed and supported by MIT’s [Center for Civic Media](https://civic.mit.edu/) and Emerson College’s [Engagement Lab.](https://elab.emerson.edu/) 


## Data

Download the Barrio_Fino_Lyrics.txt and Que_Vas_A_Ser_Sin_Mi_Lyrics.txt files from this repository and save to your Desktop. 

These files include plain-text lyrics of the songs on Daddy Yankee’s Barrio Fino album, as well as the lyrics from “Que Vas A Ser Sin Mi.” These lyrics were gathered using the [Genius Lyrics Tidy Data Extractor](https://dasil-jarren.shinyapps.io/genius-app/) Shiny app created by [Jarren Santos.](https://github.com/jarrenls) Additional cleaning and processing was done by [Katherine Walden](https://github.com/kwaldenphd/) using [OpenRefine.](http://openrefine.org/)

Open the Barrio Fino file in a text editor (Notepad on PC, TextEdit on Mac). 

From the text editor, you can get a sense of how the lyric data is structured.

## Getting Started with Data Basic

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_1.jpg?raw=true" alt="Capture" /></p>

Navigate to https://databasic.io/ in a web browser (preferably Chrome). 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_2.PNG?raw=true" alt="Capture" /></p>

&nbsp;
&nbsp;

The default site language is in English. The site is also available in Spanish and Portuguese. 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_3.jpg?raw=true" alt="Capture" /></p>

The remainder of this tutorial will use the Spanish-language version of the site. The tutorial instructions will be in English.

### WordCounter

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_4.jpg?raw=true" alt="Capture" /></p>

Click on the WordCounter icon to open the WordCounter tool. 

As described on the page, “WordCounter analyzes your text and tells you the most common words and phrases. This tool helps you count words, bigrams, and trigrams in plain text. This is often the first step in quantitative text analysis.”

Bigrams are two-word phrases or expressions. Trigrams are three-word phrases or expressions.

WordCounter gives you the option to use a sample text, paste in your own text, upload a file, or load text from a URL.

We will be using the lyrics from the Barrio Fino album in WordCounter. 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_5.jpg?raw=true" alt="Capture" /></p>

Click on the option to upload a file, and select the bario_fino_lyrics.txt file saved to your Desktop.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_6.jpg?raw=true" alt="Capture" /></p>

The default options selected in WordCounter will analyze the text without considering capitalization and stopwords.

Stopwords are commonly used words. English-language examples include “and,” “the”, and “this.”

Leave both options selected and click the Count icon.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_7.jpg?raw=true" alt="Capture" /></p>

The first visualization generated by WordCount is a word cloud of the most frequently occurring terms in the document you uploaded. Hover over specific words with your cursor to see how many times they appear in the document.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_8.jpg?raw=true" alt="Capture" /></p>

The tables below the word cloud on the results page include a list of words that appear most frequently in the document. WordCount has also generated a table with a list of bigrams and trigrams, as well as how many times they appear in the document.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_8a.jpg?raw=true" alt="Capture" /></p>

You can click on the arrow icon next to any of the table titles to download a CSV (comma-separate value) file with the data contained in that table. This file can be opened in a spreadsheet program like Microsoft Excel.

<blockquote> What is a CSV? 

A comma-separated value file (CSV) is a structured tabular data format in which column values are separated by a comma. Computer programs like Microsoft Excel parse those values and display the underlying data in a spreadsheet format. Saving tabular data as a CSV file type avoids much of the additional formatting added by programs like Microsoft Excel. </blockquote>

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_8c.jpg?raw=true" alt="Capture" /></p>

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_8b.jpg?raw=true" alt="Capture" /></p>

You can also click on the arrow icon next to the page title to get a link to your WordCounter results. Your results are available via that link for 60 days.

#### Reflection Questions

- What do you notice about the lyrics in the Barrio Fino album through the results displayed in WordCounter?
- How does WordCounter’s results shape your understanding of the lyrics?
- What additional questions do you have about the lyrics? 

### SameDiff

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_1.jpg?raw=true" alt="Capture" /></p>

Navigate back to the [DataBasic home page.](https://databasic.io)

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_9.PNG?raw=true" alt="Capture" /></p>

Click on the SameDiff icon to open the SameDiff tool.

As described on the page, “SameDiff compares two or more text files and tells you how similar or different they are. SameDiff compares one...text to another….to show you similarities and differences. It uses a cosine similarity algorithm to rate whether the documents are really similar or totally different.”

SameDiff gives you the option to use provided sample texts or upload your own documents.

In this tutorial, we will be comparing the lyrics from one song with the lyrics from the entire Barrio Fino album.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_10.PNG?raw=true" alt="Capture" /></p>

Select the barrio_fino_lyrics.txt file and the que_vas_a_ser_sin_mi_lyrics.txt files.

Click the Compare icon. 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_11.PNG?raw=true" alt="Capture" /></p>

The SameDiff report page summarizes the relative similarity of the documents you are comparing and provides a cosine similarity score.

The Cosine Similarity Score uses an algorithm to calculate the similarity of two documents based on the number of times words across the documents.

The three columns show what terms the two documents have in common, as well as what words are unique to each document. 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_12a.png?raw=true" alt="Capture" /></p>

You can click on the circle arrow icon to download a CSV file with your SameDiff results. The square arrow icon will give you a link to share your results (which will be saved for 60 days).

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_12.PNG?raw=true" alt="Capture" /></p>

#### Reflection Questions

- What do you notice about the lyrics in the specific song lyrics and the entire Barrio Fino album through the results displayed in SameDiff?
- How do the SameDiff results shape your understanding of the song and album lyrics?
- What additional questions do you have about the lyrics? 

### ConnectTheDots

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_1.jpg?raw=true" alt="Capture" /></p>

Navigate back to the [DataBasic home page.](https://databasic.io)

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_13.png?raw=true" alt="Capture" /></p>

Click on the ConnectTheDots icon to open the ConnectTheDots tool.

As described on the page, “ConnectTheDots shows you how your data is connected by analyzing it as a network. Analyzing the connections between the "dots" in your data is a fundamentally different approach to understanding it. This tool shows you a network diagram to reveal those links, and gives you a high level report about what your network looks like.”

<blockquote>What is a network? 

According to Miriam Posner, networks are “a finite set (or sets) of actors and the relations defined on them. It consists of three elements: (1) a set of actors; (2) each actor has a set of individual attributes; and (3) a set of ties that defines at least one relation among actors.” A network graph is “a common way to visually represent social networks, consisting of two dimensions: actors and relations (also called nodes and edges). Nodes are the entities in graph (also called vectors)..[edges] are the relationships between nodes.” 

Learn more via the [PDF included in this Repository.](https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/Posner_SocialNetworkAnalysisGlossary.pdf) </blockquote>

For ConnectTheDots, our network data is formatted as a list of edges, or connections, between a source and target node. 

In this tutorial, we will be using a list of nodes and edges of the artists featured in the Barrio Fino album.

[NEED TO ADD THIS FILE TO THE REPO]
[INCLUDE TABLE WITH SAMPLE DATA]

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_14.png?raw=true" alt="Capture" /></p>

ConnecTheDots gives you the option to use sample network data, paste your own data, or upload a file.

Upload the SPN320_BarrioFino_NetworkData.csv file and click the Graph icon.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_15.png?raw=true" alt="Capture" /></p>

The top of the ConnecTheDots results page provides an overview of your network. The network graph uses colors to indicate groups of nodes, and the graph caption provides a description of the network graph.

The table on the right-hand side of the page includes a list of nodes in your network, as well as the degree and centrality for each node.

<blockquote> Degree refers to the number of connections a node has. Centrality is a calculation of how central a node is within the network.</blockquote> 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_15a.png?raw=true" alt="Capture" /></p>

Clicking the square arrow icon at the top of the page gives you a link to your results (good for 60 days).

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_15b.png?raw=true" alt="Capture" /></p>

Clicking the Download button by the network graph gives you the option to download the graph as an image file (PNG or SVG) or a network graph file to use in a network analysis software program (GEXF). You can also download the table of nodes with degree and centrality metrics as a CSV file.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/DataBasic-tutorial/blob/master/screenshots/Capture_16.png?raw=true" alt="Capture" /></p>

#### Reflection Questions

- What do you notice about Daddy Yankee’s collaboration practices in the Barrio Fino album through the results displayed in ConnectTheDotes?
- How does ConnectTheDots’s results shape your understanding of the album’s content?
- What additional questions do you have about the album?

