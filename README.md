# Consumer Reviews: How Much Weight do Words Hold?
This repository contains data, code, analysis, and results for my CSCE 676 Data Mining course project. Data is powerful, and we use it everyday to make informed decisions. However, a lot of the data we see and interact with is numerical, but textual data provides a unique layer to data analysis by allowing for multiple different areas of interpretability, leaving most topics subjective, and offering contrast from a strict numerical value. In consumer reviews especially, text mining can offer valuable insights into brand opinion. I chose to conduct my project over Porsche Consumer Reviews. A well established luxury brand such as Porsche wouldn't seem to be in immediate need of listening to consumer feedback. However, recent business markers prove that any company can face adversity, and what better way to advance than by using your own consumer data? 

## 💡 Main Research Questions:
  1. How does the overall customer sentiment towards the brand compare to the given numerical rating across all reviews?
  2. What topics are most prevalent across customer reviews?

## 💻 Deliverables:
  1. Main Notebook: [Sentiment Analysis & Topic Modeling of Porsche Consumer Reviews]
  2. Project Video: [Porsche Consumer Review Investor Pitch](https://www.youtube.com/watch?v=0WPqmGNa2hg)
  3. Dataset: [Web Scraped Porshce Reviews](data/Scraped_Car_Review_porsche.csv)

## 📈 Data:
Upon searching for datasets for this project, I was aware that all datasets would come with certain levels of bias since there is no way to ensure correct or even representation across all consumer groups. However, after finding a web-scraped dataset on [Kaggle,](https://www.kaggle.com/datasets/ankkur13/edmundsconsumer-car-ratings-and-reviews?select=Scraped_Car_Review_porsche.csv) I concluded it was a more solid approach since it detected reviews across the web. The format of the dataset is easy to load and run using simple read.csv commands into a dataframe. 

### Preprocessing:
Initially, I ensured that all empty fields had been dropped and tweaked the date of the reviews in order to plot findings by a certain time period.  The Preprocessing itself looked a bit different for both analyses. For sentiment analysis, no punctuation or stop words were removed since TextBlob relied on original text to get as accurate a reading of polarity and subjectivity as it could. Following the conclusion of this analysis, I did parse through the reviews field and remove miscellaneous characters and stop words for topic modeling. 

## 🎬 Reproducing The Environment
This project in its entirety was built on the Google Colab platform. 

## 🗒️ Versions & Dependencies
- Python 3.12.13
