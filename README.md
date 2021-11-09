# Fake_News_Detector

___To Download the Dataset click [here](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)___

__Fake news__ refers to misinformation, disinformation or mal-information which is spread through word of mouth and traditional media and more recently through digital forms of communication such as edited videos, memes, unverified advertisements and social media propagated rumours.Fake news spread through social media has become a serious problem, with the potential of it resulting in mob violence, suicides etc as a result of misinformation circulated on social media.

---
### Requirements
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Regex
- NLTK
- Scikit-learn
- Pickle
- Word Cloud
- Warnings
---
> Store the downloaded dataset and the Detector.ipynb notebook in the same folder

### Import Dataset
- Data Selection
### Visualize the dataset
> ### True_news.csv
![Fake News Detector 1](https://user-images.githubusercontent.com/79501547/140863629-8b5521f4-19aa-498c-8477-b195b6d0edb2.PNG)

### Preprocess the dataset
> #### Combined dataset with additional feature named `Target`, 0 for fake news and 1 for true news

![Fake News Detector 2](https://user-images.githubusercontent.com/79501547/140863875-774e38e6-4753-4850-8dc0-98e422f4db0a.PNG)

### Cleaning
![Fake News Detector 3](https://user-images.githubusercontent.com/79501547/140864029-433c36a4-f0fb-4c2b-a1d0-492224ec2e69.PNG)

> #### Combination of `clean_title` and `clean_text`
![Fake News Detector 4](https://user-images.githubusercontent.com/79501547/140864161-d48291b3-6982-4c82-a788-fe6b000e1ab0.PNG)

### Word Clouds
![Fake News Detector 5](https://user-images.githubusercontent.com/79501547/140864337-5c6203bb-f8d5-44d0-9a47-7e2779449675.png)
![Fake News Detector 6](https://user-images.githubusercontent.com/79501547/140864341-d76e0ae8-860e-4a4c-a20f-ef269fef88d5.png)

### Metrics
![Fake News Detector 7](https://user-images.githubusercontent.com/79501547/140864583-5da56880-9714-4e12-9ab5-5702a14997ec.PNG)
