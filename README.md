# DS4002 Project 1 - Group 19
Brian Xiao, Elaine Shagdarjav, Jason Albanese
## Section 1: Software and Platform
* For the sentiment analysis, we used the pretrained VADER model [1] in the nltk package
* In order to obtain data, we used Arctic Shift (https://github.com/ArthurHeitmann/arctic_shift) [2] to scrape data from Reddit. This generated a JSON file in which we cleaned and turned into a CSV with Python.
* The CSV was then opened with Python to use the VADER Sentiment Analysis package.
* Additionally, we used the pandas, matplotlib, seaborn in Python.
* Windows and Mac were used to run the software.

## Section 2: Documentation Map
Within our main project folder, we have 3 folders:
### Scripts Folder
* plot_ipynb
* scrape_from_json.py
### Data Folder
* cleaned_comments.csv
* cleaned_posts.csv
* r_PoliticalDiscussion_comments.json
* r_PoliticalDiscussion_posts.json
* r_Republican_comments.jsonl
* r_Republican_posts.jsonl
* r_democrats_comments.jsonl
* r_democrats_posts.jsonl
### Output Folder
* posts_scored.png
* comments_scored.png
* posts_filtered.png
* comments_filtered.png
* ttest_summary.txt
* posts_filtered_before.png
* posts_filtered_after.png
* comments_filtered_before.png
* comments_filtered_after.png
## Section 3: Instructions
1. Clone this repo.
2. Install the latest version of Python
3. Download the following libraries/packages if you do not have them already *(pip install [library])*:
	* pandas
	* matplotlib
	* seaborn
	* nltk
	* vaderSentiment
		* If you are on Mac, you might run into an issue with certifications. Run this in terminal: bash '/Applications/Python 3.6/Install Certificates.command'
4. Run all of the code blocks in *plot.ipynb* in order
   	* In the latter half, you can find the results of running T-Tests between classes.
   	* All of the graphs are generated be found at the end of this python notebook
  
[1] “Welcome to Vadersentiment’s documentation!,” Welcome to VaderSentiment’s
documentation! - VaderSentiment 3.3.1 documentation,
https://vadersentiment.readthedocs.io/en/latest/ (accessed Sep. 13, 2024)

[2] Heitmann, A. (2023, August 3). Arthurheitmann/arctic_shift: Making Reddit data accessible to researchers, moderators and everyone else. interact with the data through large dumps, an API or web interface. GitHub. https://github.com/ArthurHeitmann/arctic_shift 
