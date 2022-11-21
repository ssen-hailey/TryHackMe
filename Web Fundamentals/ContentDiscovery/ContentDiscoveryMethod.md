


# ContentDiscoveryMethod 
>There are three main ways of discovering content on a website which we'll cover.
>1) Manually
>2) Automated
>3) OSINT (Open-Source Intelligence).

### 1. Manual Discovery
-1) Robots.txt
- The robots.txt file is a document that tells search engines which pages they are and aren't allowed to show on their search engine results or ban specific search engines from crawling the website altogether.
-2) Favicon 
- Sometimes when frameworks are used to build a website, a favicon that is part of the installation gets leftover, and if the website developer doesn't replace this with a custom one, this can give us a clue on what framework is in use
- 3) Sitemap.xml
- Unlike the robots.txt file, which restricts what search engine crawlers can look at, the sitemap.xml file gives a list of every file the website owner wishes to be listed on a search engine.
- 4) HTTP Headers
- When we make requests to the web server, the server returns various HTTP headers. These headers can sometimes contain useful information such as the webserver software and possibly the programming/scripting language in use. 
- 5) Framework Stack
- 

### 2. OSINT
-1) Google Hacking / Dorking
- Google hacking / Dorking utilizes Google's advanced search engine features, which allow you to pick out custom content.
-2) Wappalyzer
-3) Wayback Machine
- Archive of web pages
-4) GitHub 
-5) S3 Buckets

### 3. Automated Discovery
- Automated discovery is the process of using tools to discover content rather than doing it manually. 
- What are wordlists? Wordlists are just text files that contain a long list of commonly used words; they can cover many different use cases.
- Automation Tools :  ffuf, dirb and gobuster
