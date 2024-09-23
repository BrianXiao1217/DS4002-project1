# DS4002 Project 1 - Group 19
Brian Xiao, Elaine Shagdarjav, Jason Albanese
## Section 1: Software and Platform
* In order to obtain data, we used Arctic Shift (https://github.com/ArthurHeitmann/arctic_shift) to scrape data from Reddit. This generated a JSON file in which we cleaned and turned into a CSV with Python.
* The CSV was then opened with Python to use the VADER Sentiment Analysis package.
* Additionally, we used the pandas package in Python.
* Windows ?

Rubric:
- The type(s) of software you used for the project.
-The names of any add-on packages that need to be installed
with the software.
-The platform (e.g., Windows, Mac, or Linux) you used
## Section 2: Documentation Map
Within our main project folder, we have 3 folders:
### Scripts Folder
* scrape_from_json.py
	* Where we take the original JSON file and parse through it to create 3 CSVs:
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

Rubric:
- In this section, you should provide an outline or tree illustrating the
hierarchy of folders and subfolders contained in your Project Folder,
and listing the files stored in each folder or subfolder.
## Section 3: Instructions

Rubric: 
In this section, you should give explicit step-by-step instructions to
reproduce the Results of your study. These instructions should be
written in straightforward plain English, but they must be concise, but
detailed and precise enough, to make it possible for an interested user
to reproduce your results without much difficulty

