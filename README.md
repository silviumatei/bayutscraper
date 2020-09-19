# bayutscraper
scraper for properties listed for rent on bayut.com

Developed for jupyter notebooks, this app 1) collects all the links for the properties listed for rent on bayut.com and then 
2) scraps all the details available about these properties and saves them into a csv file

The first file to scrap the links to the properties works on a local machine while the second file should be run on Google colab.
The issue I had was that the list of properties was too big and it was gettign stuck on my local machine. It was doing the same on Google colab. 
The solution was to split the list into sublists of maximum 10,000 links.
Therefore, on the free version of Google colab, you need to restart the session after running the scrapper 
for every 2 sublists - comments are present in the program.

