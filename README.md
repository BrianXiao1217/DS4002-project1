# DS4002 Project 1 - Group 19
Brian Xiao, Elaine Shagdarjav, Jason Albanese
## Section 1: Software and Platform
* In order to obtain data, we used Arctic Shift (https://github.com/ArthurHeitmann/arctic_shift) to scrape data from Reddit. This generated a JSON file in which we cleaned and turned into a CSV with Python.
* The CSV was then opened with Python to use the VADER Sentiment Analysis package.
* Additionally, we used the pandas, matplotlib, seaborn, nltk, and vaderSentiment in Python.
* Windows and Mac were used to run the software.

## Section 2: Documentation Map
Within our main project folder, we have 3 folders:
### Scripts Folder
* plot_ipynb
* scrape_from_json.py
### Data Folder
* all_comments.csv
* all_posts.csv
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
* posts_with_biden.png
* comments_with_biden.png
## Section 3: Instructions
1. Clone this repo.
2. Download the following libraries/packages if you do not have them already *(pip install [library])*:
	* pandas
	* matplotlib
	* seaborn
	* nltk
	* vaderSentiment
		* If you are on Mac, you might run into an issue with certifications. Run this in terminal: bash '/Applications/Python 3.6/Install Certificates.command'
3. Run *plot.ipynb* 