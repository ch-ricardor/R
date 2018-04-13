# Wordcloud
R (programming language)

Small program to create wordclouds and csv files with the the 10 most freuent words.

Edit the program and change the specifi i_ variables to adapt the program to your environment.

 Working Directories
   i_workingPath - Initial Working directory
       i_pdfPath - Path where the pdf documents to process are.
   i_dataExport  - Directory to save the images with the result wordcloud
   i_dataExportTags  - Directory to save the frequency tags for the document

Edit your specific "stop words" that you want to remove, like mexicanisms as an example

my_stopwords <- c("e-ii","can","due","will","yes", 
                  "tm","figs","figure","online", 
                  "rapid", "physical", "review", 
                  "http","https",
                  "chancla","cacle","rola","chela","orale"
)    
   
Edit the uri_list.txt files with the URIs that you want to process.
Files could be local or retrieved from the web.

Example:

https://fluxicon.com/disco/files/Disco-Tour.pdf
https://www.esri.com/library/brochures/pdfs/arcgis.pdf
D:\Git_Projects\R\R_WordCloud\code\data\documents\my_pdfFile.pdf


![Alt text](./Strategy_Map.png?raw=true "WordCloud")


