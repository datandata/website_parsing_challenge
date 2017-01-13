# website_parsing_challenge
Website parsing challenge for engineering candidates.

##Goal
The file websites.txt contains a list of 500 websites that have been found by one of our search bots. Your objective is to parse these websites in order to answer the following two questions for each website:
  1. is it an e-commerce website?
  2. does it mention any of the following brands: Gucci, Rolex, Hermès, Dior, Chanel, Louis Vuitton?

Your result should be in tabular format: a tab separated file with the following columns: 
```
website            ecommerce   brands
solidswiss.cd      true        Rolex
stevemccurry.com   false          
```
If you have multiple brands, list them as follows:  ```Gucci, Rolex, Hermès```


##Constraints
####Implementation
Our only constraint is that you should use Python, ideally Python 3.x . Beyond that, use any tool that can help you get the job done better or faster.

####Compatibility
Your code should be easily deployable. We need to be able to run your code ourselves, in a Unix environment. Leave us explicit instructions for installing dependencies and getting your script up and running.


##Submission
Email us your repository URL at jobs@data-and-data.com. Your repository should contain the following files:
- result file
- source code
- a readme with both the instructions on how to install and run your code, and a description of how you approached the problem (key design choices, notes on current limitations and further improvements, etc.)


##Notes
Feel free to append to the output file any additional information that you think may be useful, or otherwise make any enhancement to your code or output that you think off.

You can shoot us any questions via email at: jobs@data-and-data.com
