v1.2.6
------

  * Added test coverage for most modules using pytest
  * Refactored large portion of 'html_pbp.py' and corrected minor parser fixes in regards to penalties
  * Added the module 'save_pages.py' which allows one to saves scraped files
  * Added keyword arguments 'rescrape' and 'docs_dir' to the three main scraping functions. Specifying a valid directory
    using 'docs_dir' will make us check if a file was already scraped and saved before getting it from the source. It will
    also provide a location for us to save it if we don't have it yet. 'rescrape' only applies when a valid directory
    is provided with 'docs_dir'. Setting 'rescrape' equal to True will have us scrape the file from the source even if
    it's saved and save this new one.

v1.2.7
------

  * Added functionality to easier scrape live games
  * Fixed user warnings


v1.3
----

  * Added functionality to scrape NWHL data

v1.31
-----

  * Added functionality to automatically create docs_dir
  * Added folder to store csv files

v1.34
-----
  * Fixed bug with nhl changing contents of eventTypeId
  * Updated ESPN scraping after they changed the layout of the pages
