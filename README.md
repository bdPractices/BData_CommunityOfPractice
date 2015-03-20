BData_CommunityOfPractice
=========================

Repository for the Big Data Community Of Practice group

Weekly tasks
-----------------
- Update documentation for Intertec Web page:
  - Vision (already done)
  - General White Paper
    - Services Offered (Accenture approach) [Richard]
    - Results for our clients (Sample from IBM <a href='http://www.ibm.com/big-data/us/en/'>page</a>) [Duvelis]
  - Big Data Projects Roadmap White Paper
    - The Journey to Actionable Insights (Refinement needed) [Richard]

- Proof of concept project (HDP Sandbox)
  - Implement the ingestion system (Apache Flume)
    - Implement Twitter Flume custom source [Leo]
    - Implement Github Flume custom source [Ignacio]

- Flume tutorials:
  - <a href='http://flume.apache.org/FlumeUserGuide.html#data-flow-model'>The Flow Model</a>
  - <a href='http://flume.apache.org/FlumeUserGuide.html#custom-source'>Flume custom sources</a>
  - <a href='http://blog.cloudera.com/blog/2012/09/analyzing-twitter-data-with-hadoop/'>Cloudera example</a>


User story 0
-----------------
- New
  As a recruiting user I will be able to see a dashboard-like interface with the candidate virtual identity to have a 360 degree view of the candidate that supports better our recruitment decisions.

- Old
  As a recruiting user I will be able to calculate the candidate availability scoring to determine the probability of the candidate to change jobs.


IPython Notebook Example
-----------------
<a href='http://nbviewer.ipython.org/github/bdPractices/BData_CommunityOfPractice/blob/master/notebookWeek1/Data%20Analysis%20Community%20of%20Practice.ipynb'>Notebook</a>

Harvard - Data Science course materials
-----------------
http://cs109.github.io/2014/


Hortonworks Tutorials
-----------------

Get started

http://hortonworks.com/get-started/?mkt_tok=3RkMMJWWfF9wsRouv67MZKXonjHpfsX67%2B0oWaK0lMI%2F0ER3fOvrPUfGjI4GT8FiI%2BSLDwEYGJlv6SgFT7TMMbFh1rgNUxc%3D

How to Process Data with Apache Hive

http://hortonworks.com/hadoop-tutorial/how-to-process-data-with-apache-hive/?mkt_tok=3RkMMJWWfF9wsRouuqvMZKXonjHpfsX67%2B0oWaK0lMI%2F0ER3fOvrPUfGjI4HTcNqI%2BSLDwEYGJlv6SgFT7TMMbFh1rgNUxc%3D

How To Process Data with Apache Pig

http://hortonworks.com/hadoop-tutorial/how-to-process-data-with-apache-pig/?mkt_tok=3RkMMJWWfF9wsRouuqvPZKXonjHpfsX67%2B0oWaK0lMI%2F0ER3fOvrPUfGjI4HTcNrI%2BSLDwEYGJlv6SgFT7TMMbFh1rgNUxc%3D

Interactive Query for Hadoop with Apache Hive on Apache Tez

http://hortonworks.com/hadoop-tutorial/supercharging-interactive-queries-hive-tez/?mkt_tok=3RkMMJWWfF9wsRouuqvOZKXonjHpfsX67%2B0oWaK0lMI%2F0ER3fOvrPUfGjI4HTsdmI%2BSLDwEYGJlv6SgFT7TMMbFh1rgNUxc%3D

Using Hive for Data Analysis

http://hortonworks.com/hadoop-tutorial/using-hive-data-analysis/?mkt_tok=3RkMMJWWfF9wsRouuqTJZKXonjHpfsX67%2B0oWaK0lMI%2F0ER3fOvrPUfGjI4HTsdnI%2BSLDwEYGJlv6SgFT7TMMbFh1rgNUxc%3D

How to Use Basic Pig Commands

http://hortonworks.com/hadoop-tutorial/how-to-use-basic-pig-commands/?mkt_tok=3RkMMJWWfF9wsRouuqTIZKXonjHpfsX67%2B0oWaK0lMI%2F0ER3fOvrPUfGjI4HTsdkI%2BSLDwEYGJlv6SgFT7TMMbFh1rgNUxc%3D

Word Counting with Apache Pig

http://hortonworks.com/hadoop-tutorial/word-counting-with-apache-pig/?mkt_tok=3RkMMJWWfF9wsRouuqTLZKXonjHpfsX67%2B0oWaK0lMI%2F0ER3fOvrPUfGjI4HTsVhI%2BSLDwEYGJlv6SgFT7TMMbFh1rgNUxc%3D

How to Use HCatalog, Pig & Hive Commands

http://hortonworks.com/hadoop-tutorial/how-to-use-hcatalog-basic-pig-hive-commands/?mkt_tok=3RkMMJWWfF9wsRouuqTKZKXonjHpfsX67%2B0oWaK0lMI%2F0ER3fOvrPUfGjI4HT8JnI%2BSLDwEYGJlv6SgFT7TMMbFh1rgNUxc%3D

Linkedin

https://developer.linkedin.com/documents/connections-api

https://developer.linkedin.com/documents/authentication

The information of the authentication for linkedin is in the email of the group.

Disadvantages:

The API needs that other API members of Linkedin accept your application to retrieve the members data.
We only can go to the first level of connections, this means that we cannot go to the connections of our friends.
Is very restrictive and does not permits to search the complete user information.

Right now I am trying to connect to Linkedin using the OAuth 2.0 protocol, but I am having problems because I did not understand it very well.

OAuth easy tutorial: http://tutorials.jenkov.com/oauth2/index.html

From what I saw, it seems like the API needs an human interactions because the protocol requeri the we send the authentication that can be provided by facebook, google, or another entity. So this makes me think that the API cannot be used to retrieve information automatically.

Crawling: http://www.quora.com/How-do-I-crawl-data-from-LinkedIn
