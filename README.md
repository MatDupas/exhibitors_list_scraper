# Scraper for tradeshows

** GOAL : **
Get the list of profile of exhibitors at a tradeshow.

I typically use it either:
 - before attending an exhibition : it allows me to check every startup attending and list only the best ones to see on day D
 - if I can't get to the exhibiton : perform a check of all exhibitors to verify if some could have been interesting to discuss with

How to use it:
--------------
1. Fill in  the BASE_URL(base of tradeshow website)
2. Fill in the  LIST_TO_SURF variable : put the links of the pages where the companies profile appear
3. Modifiy classes and tags in the get_exhibitors_list() and get_exhibitors_profile() functions to adapt to website to scrape
4. Run the cells : it will save a csv file with all the results in the current folder

