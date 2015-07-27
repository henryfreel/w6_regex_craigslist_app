# Scrape CraigsList with Nokogiri & Regex

Your task is to write a **Puppy Scraper**. Your scraper will search Craigslist for all pets in the SF area and use regex to return the date, title, and location for any posting that matches the words "pup", "puppy", "puppies", or "dog".

<img src="http://images.craigslist.org/00G0G_3iU0WdkbvPy_600x450.jpg">

## Challenges

1. Use regex to only return results where the title matches "pup", "puppy", "puppies", or "dog".

2. In addition to matching the keywords above, only return results where the title DOES NOT include "house", "item", "boots", "walker", or "sitter".

3. **Bonus:** Only return results that have an image.
  * **Hint:** This will involve scraping an extra page element in `get_page_results` as well as updating the logic in `filter_links`. You will need to visit <a href="http://sfbay.craigslist.org/sfc/pet">http://sfbay.craigslist.org/sfc/pet</a> in the browser and use `Inspect Element` to find the page element containing the image flag (`pic`).

## How to Get Started

1. Fork this repo, and clone it onto your local machine.
2. From the terminal, run `ruby scraper.rb`.