# twinger
Database for the known manuscripts that transmit the [chronicle of Jakob Twinger von Königshofen](http://www.geschichtsquellen.de/werk/3006?mark=%28%3Fis%29%28twinger%29).
  
The database derives from my research for my PhD, which I conducted between 2013 and 2017 at the University of Freiburg (Germany). The thesis was defended in summer 2018 and published in 2020 with De Gruyter: [Ina Serif: Geschichte aus der Stadt. Überlieferung und Aneignungsformen der deutschen Chronik Jakob Twingers von Königshofen. Berlin/Boston 2020.](https://doi.org/10.1515/9783110636475)
  
I have been using [nodegoat](nodegoat.net) for several years now as my working and data storing environment. As it is a relational database, the export for this repository consists of two files: the main file, [manuscripts.csv](https://github.com/wissen-ist-acht/twinger/blob/main/manuscripts.csv), which contains the manuscripts and their metadata, and a content file, [content.csv](https://github.com/wissen-ist-acht/twinger/blob/main/content.csv), which contains the relations between texts and manuscripts, using "nodegoat_ID" as identifier. As of 2022, the main file consists of 128 records, the content file of 1220 entries. You should be able to import it to the software you prefer, linking the content to the manuscripts through "nodegoat_ID".

The metadata fields for the manuscripts are the following:  
nodegoat ID,	Institution,	Call no.,	Sigle,	Folio no.,	Material,	Language,	illustrated,	Exact date of origin,	Date of origin,	Place of origin,	Place certain,	Chronicle Version,	Additional info  
The information about the single codices derives from manuscript catalogues, research articles, and own analyses. For a complete bibliography of the used literature see my [thesis, pp. 215–245](https://doi.org/10.1515/9783110636475-006).

As this is a finished research project, the database gets updated only on an irregular basis. I am also maintaining an online article about the known manuscripts and existing digital versions: [Ina Serif: Der zerstreute Chronist. Zur Überlieferung der deutschsprachigen Chronik Jakob Twingers von Königshofen](https://mittelalter.hypotheses.org/7063), 12/2015, last update 10/2021. The [record for the chronicle in the Handschriftencensus](https://handschriftencensus.de/werke/1906) does not list all manuscripts that I consider to be textual witnesses (as of October 2021, it lists 115 manuscripts), but contains additional information regarding single codices. 
  
