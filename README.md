# Larvel
A one script to find all larvel sites out there in internet.

* THIS SCRIPT MIGHT CAUSE FINANCIAL DAMAGE TO WEBSITE TARGETING AND MAY END UP LEAVING YOU IN HANDS OF COP, MADE FOR EDUCATIONAL PURPOSE ONLY *

But before starting let me clear you what is larvel &

# Larvel #

Laravel is a well-known open-source PHP framework for creating online apps and websites.Laravel makes development easier by offering a simple and expressive syntax, a modular framework, and built-in capabilities for tasks like as routing, database administration, and caching. It adheres to the Model-View-Controller (MVC) architectural paradigm, which encourages concern separation and code organisation.Laravel also includes a sophisticated ORM (Object-Relational Mapping) called Eloquent, a configurable routing system, automated testing capabilities, built-in login and authorisation systems, and caching, queuing, and job scheduling support. It also has a thriving ecosystem with a diverse set of community-driven packages and extensions.

# Why We targeting Larvel? 

It was clear that the main use of larvel php framework was to store auth of different plugins and api's related to site. such as smtp data, database password, admin creds, payment secret, api's related to all tasks being performed in site.
So we will find website that are wordpress first of all, then test them to see if they larvel or not.

# System requirement
A server is a must,
Ubuntu latest or 20.04 will work super fine for it & Windows are also good for it. 
Some part contains windows only working tool outsourced from online free available.

# Process

1. First process is pretty simple to obtain domains. PUBLIC DOMAINS list. And well this can be obtained by simply alex 1 milion top domain or just using a search engine and headers to crawl through pages and collect domain. using dork is the best way to get preferred target. 
2. When we got domains we save it into a text file and do a quick dns lookup for all domains and quickly convert them to their respective ips. now you may have a question why we need to convert them to ip. i'll explain it in next step.
3. The saved ips list, we are gonna ranged them by /16 and find all subnet of it. for eg. 104.76.0.1 is rnaged into 104.76.0.[1-254]. Now by doing this way we are expanding our search , in simple terms a big hosting company usually hold all subnets of a ip and if we range them and reverse lookup them we will find all the domains corresponding to those ips so in short we will increase our domain list.
4. By doing larvel we need to find wordpress site then we look for larvel to exploit /.env into them and export creds. so more the number of domains more the chances of getting larvel sites and more the creds. [ # THIS IS FOR EDUCATIONAL PURPOSE SO THAT ANYONE IF USES LARVEL FRAMEWORK WILL SECURE THEIR SITE BY LIMITING ACCESS TO /.ENV ] 
5. Open finder.py attached in repository and use command  python3 finder.py domains.txt 200
 in above code, python3 is running script finder.py which reads domain from domains.txt and 200 shows its multi thread and asyncrous processing.
6. The script will automatically run and find the culprit aka larvel sites :D 

THATS ALL FOR LARVEL CRACKING
follow my github account for more of such contents.
keep learning, keep exploring.
