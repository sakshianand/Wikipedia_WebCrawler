# Wikipedia_WebCrawler
A python script to crawl through various wikipedia pages,searches and extract the first link from the main body.

This script will work till the following condition has occured:

1.A target page has been reached (Which in this script is [https://en.wikipedia.org/wiki/Philosophy](this))
2.The search has gone on suspiciously long(Default maximum count has been initialized to *25*)
3.We have arrived at an article we have already seen

---

### Framework Information

---
* Python 3.6.0
	* [https://www.crummy.com/software/BeautifulSoup/bs4/doc/](Beautiful Soup Library v4)

### Installation Steps

---
1. Python 3.6.0 need to be installed [https://www.python.org/downloads/](Download here)
2. Install the following libraries by running the below commands on command prompt:
   * ```pip3 install requests```
   * ```pip3 install bs4```

### Steps Running the application

---
``` >>> python wikipediacrawler.py ```

### References

*[https://classroom.udacity.com/courses/ud1110](Udacity tutorial)
*[https://www.crummy.com/software/BeautifulSoup/bs4/doc/](Beautiful Soup v4 - Python library)
*[http://docs.python-requests.org/en/master/](Requests API)

---




