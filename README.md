# YouTube Trending Video Analysis   [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Installation
### Modules
pip install these modules
- pandas: data processing
- numpy: linear algebra
- seaborn: data visualization
- matplotlib: data visualization
- re: regular expression
- datetime: manipulate date time types of data
- os: create folders
- PTL: image processing
- wordcloud: word cloud creating
### Data Source
[Trending YouTube Video Statistics from Kaggle](https://www.kaggle.com/datasnaek/youtube-new)    
Focus on the US dataset
## Project Motivation
Through analyzing the YouTube trending videos data, I was aiming to answer these questions：
1. What types of videos are more likely to be trending?
2. Do descriptions or tags matter?
3. How long does it take for a video to go viral?
## File Description
### Datasets
- USvideos.csv   
Information about trending videos on YouTube dated from 2017-11-14 to 2018-06-14.    
Shape: (40949, 16)
- US_category_id.json   
Category names
### DataWrangling_Visualization.ipynb    
- Data wrangling
- Explorary data analysis
- Data visualization
### img
Includes all images used for word cloud, and output visualizations

## Results
My blog on Medium:   
[Data-Driven Tips to Make aVideo Go Viral on YouTube](https://zhaoyiw.medium.com/data-driven-tips-to-make-avideo-go-viral-on-youtube-e7117f51fc2f)

## License
This project is under [MIT License](https://github.com/git/git-scm.com/blob/master/MIT-LICENSE.txt).

## Author
[Zhaoyi Wang](https://github.com/ZhaoyiW)
