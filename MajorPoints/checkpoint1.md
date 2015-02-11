# Matthew Dodd: What the Government wants you to know
*Checkpoint 1: Initial thoughts & data*
--------

*Primary Data*: https://twitter.com/gccaedits ; With over 1,800 tweets regarding the edits to Wikipedia from "Canadian Government IP addresses" this information, when gathered into a massive .json file can provide a variety of information about what the government and its employees are editing and changing on Wikipedia.

*Collection method*: I intend to use TWARC (still need to get fully setup) on a Linux (Ubuntu) machine to grab the data (in a .json or .geojson format). 

*Repository structure*: https://github.com/matthewdodd/hist3907b/tree/master/gccaedits ; This folder will contain: a subfolder with all of the raw data grabbed using TWARC, another subfolder with the cleaned data, and a third subfolder with the actual analysis and visualizations. In the root of the folder will be the primary writings about the subfolders.

*Secondary Readings*: https://github.com/matthewdodd/hist3907b/tree/master/gccaedits/notes

*Initial thoughts on what you might find/explore/puzzle over:*
- I'm hoping to see a pattern by Government Entity (DND, DFAIT, Shared Services, etc) or by pages edited (military, sports, etc.). 
 - I'm expecting to get back some 1,800 tweets with a good chunk of information, which I'll compare to the list of IP addresses that GCCAedits is using to determine which IP addresses are the ones in greatest use.
 - From this point I'll generate a .csv if possible by topic (general), article, IP address, Government Entity.
 - Once I have the .csv I'll run it through Palladio and see what it tells me, if anything.
- Reflect on the Posner video you watched as well:
 - Given the collection, analysis/visualization, and presentation stages I intend to spend the greatest deal of time on the analysis/visualization
 - I won't be making a map because I do not believe that will provide any useful information.
- What kinds of exploratory visualizations/analyses might be useful for you to try?
 - Palladio will be useful I think if I can format the .csv properly.
 - Just creating a large table/.csv to explore the data, without a grander visualization might be the end result.
- Where do you think this project might go?
 - I'm not sure yet, but it could end up being a wonderful template for additional twitter analysis.
 - This is also something that could provide for an article to be written detailing what it is the government/employees are writing about (expose the inner details)