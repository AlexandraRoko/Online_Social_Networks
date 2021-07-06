# Online Social Networks (OII)


This repository contains the code written for the course _Online Social Networks_ taken at the Oxford Internet Institute in partial fulfillment for of the MSc Social Data Science programme.

## Analysis & Dataset

For this analysis, I scraped data from GitHub by querying GitHub’s REST API. From this, I constructed two different networks: First, a network of collaboration (Who collaborates with whom on a repository?) and second, a response network based on data from the issue tracker (Who answers whom how quickly?). 

## Notebooks

* `Scraping_issue_tracker_GitHub.ipynb` contains python code to scrape the issue tracker
* `Scraping_of_Contributors_to_repos.ipynb` contains python code to scrape a GitHub organisation

* `Network_of_Contributors.ipynb` contains python code to construct the network of contributors
* `Constructing_Issue_Tracker_Network.ipynb` contains python code to construct the network of respondense. 

## Script requirements (versions used)

* jupyter (6.1.4)
* python (3.8.5)
* numpy (1.19.5)
* requests (2.24.0)
* json (2.0.9)
* matplotlib (3.3.2)
* pandas (1.2.4)
* re (2.2.1)

#### Network analysis
* networkx (2.5)
* seaborn (0.11.0)
* community (0.15)
