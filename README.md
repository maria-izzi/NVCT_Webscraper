# NVCT_Webscraper
A simple web scraper that extracts names and mailing addresses of parcel owners in multiple Northern Virginia counties. Developed for the Northern Virginia Conservation Trust in summer 2021, to reach out to owners of land parcels that are identified as high priority for environmental conservation.

This is what the first screen of the GUI looks like:
![image](https://user-images.githubusercontent.com/32143977/137040756-1cfc9fdc-74fe-47c9-92d4-0b1da9eb858e.png)

After that, the web scraper will run for a while, exporting the output to a file titled webscraper_output.csv. That file will look like this:
![image](https://user-images.githubusercontent.com/32143977/137040968-f64c3916-eb50-475d-bedf-702c2f4a6dd4.png)

Then, this final screen of the GUI will appear, after which the program is complete.
![image](https://user-images.githubusercontent.com/32143977/137040842-ab842526-700a-47d6-a825-9f0f76fcab5b.png)

Done in Jupyter Notebook for readability. Converted Python file to an executable file including dependencies for usability.

[Link](https://tinyurl.com/nvctscraper) to webscraper guide for users: https://tinyurl.com/nvctscraper
Used [auto-py-to-exe](https://pypi.org/project/auto-py-to-exe/) to convert Python file to executable
Used [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) to scrape data
