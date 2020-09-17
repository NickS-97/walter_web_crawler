# Walter the Wikipedia Web Crawler

A fun web scraping project.

One project I was interested in doing involved visualizing IPOs and their performance in the months succeeding their IPO date. One of the places I found potential data for the project was on Wikipedia. I reviewed Wikipedia's terms and conditions and found that the site allows bots and crawlers, as long as they are slowed down and nice to the site.

I built the web crawler, which I nicknamed Walter, to click through every IPO company in 2000 (link: https://en.wikipedia.org/wiki/Category:2000_initial_public_offerings). Once a company is clicked on, Walter scrapes certain information such as industry, founded, and headquarters, and then returns to the starting page and selects the next company. Once all of the companies on the page have been scraped, Walter then proceeds to the next year (2001) and performs the same functions through 2019. 

This is basically an automation project using web scraping. It was fun to code and certainly fun to run (takes a few hours to complete on my computer). Unfortunately, I determined that the Wikipedia information was too incomplete as far as IPOs, and so I did not proceed with the project. However, I thought the web crawler was still worth showing off. 

I may return to the IPO project in the future using an API. 