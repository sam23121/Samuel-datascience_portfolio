## Samuel-datascience_portfolio
data science portfolio

# [Project 1: ethiopian currency classification](https://github.com/sam23121/ethiopian_currency_classification)
using convolution neural networks I classified ethiopian new currency with great accuracy
- by using different trained models and fine tuning them vgg16 and mobilenet yeild the greatest result but since the mobilenet model was much smaller in size than the vgg16 mobilenet was the model with the best outcome                                                 . 
- Data was hand collected from banks and consited of different types(all 4 notes 10, 50, 100, 200 that are new torned sherreded and written)                           - there is a gui that was bulit using tkinter for display                                                                                                                - ongoing work is exceding this to counterfiet detection and trying to close the data imbalance between real and counterfiet data by GAN and changing the GUI to an andriod app....The dataset can be found here https://drive.google.com/drive/folders/1XpsgRghZlKChTGABNOv1nee3lYbLhQDL?usp=sharing

![](/images/resized_gui.jpg)

# [Project 2: smart-anti-theft-system](https://github.com/sam23121/smart-anti-theft-system)
a smart anti theft system by using computer vision that can be used for one door way room or small office
this system uses a microcontroller and an ultrasonic sensor to sense if there is some one or object outthere
if there is it sends a signal to the camera which captures what it is in front of it and if there is a person it extracts
its face converts to and 128 column vector and  compares it with the database (for example the owners relative) if it is not
known it will send a message to the owner and captured photo of the robber through email to the owner

![](/images/resized_Capture.jpg)

# [Project 3: chest-X_ray_web_app](https://github.com/sam23121/chest-X_ray_web_app)
a chest X-ray web app that is able to classify if the image is COVID-19, Pneumonia and NORMAL
- the dataset was trained on multple pre trained model but DenseNET yelid with the best performance with 93.3% accuracy
- the web app was bulit by flask (a python framework for lightweight website) 
- after the user(doctor, radiologist...) has choose an x-ray image it classify it if it's whether COVID, PNEUMONIA or NORMAL
- the tools that was used were basic html, css, javascript for the frontend and flask on the backend as well as keras and opencv
- the pretrained model we bulit is on this repositery but for own use of the dataset its on kaggle through this link kaggle.com/prashant268/chest-xray-covid19-pneumonia  

![](/project.PNG)

# [Project 4: crop-recomendation](https://github.com/sam23121/crop-recomendation)
a classification problem that is able to predict which crop is good for which type of soil
- it recieves 4 different kind of data from the microcontroller sensors which are  temprature, humidity, ph value, mosture process it and
then sends it to the python script and trains it based 6 diffrent machine learning algortihms
- finally it recommends the crop with the highest count

# [Project 5: Summarization](https://github.com/sam23121/summarization)
a natural languguage problem that recieves long story and output a summary of the story

# [Project 6: online_ads_recommendation system](https://github.com/sam23121/online_ads)
its an online_ads recommendation system that used Reinforcement learning. It uses two algorithms which are Upper bound Confidence and Thompson sampling. a dataset has been used as stimulation for the online process

![](/images/UCB.PNG)![](/images/thompsn.PNG)


# [Project 7: sentiment_analysis](https://github.com/sam23121/sentiment_analysis)
sentiment analysis done on amazon customer that did
- Data analysis and visualization
- data cleaning
- model training and prediction with logistic regression
- handling data imbalancing
- doing cross validation by using gridsearch and then doing predictions
- automating the model...for the dataset follow this link https://www.kaggle.com/joychakraborty2000/amazon-customers-data

![](/images/analysis.PNG)

# [Project 8: Clustering](https://github.com/sam23121/clustering_mall.git)
it's a project that clusters specfic groups of mall customers to use for target marketing. it clusters the mall customers using Unsupervised learning specifically
it uses two different algorthims Kmeans and heriarchial clustering

![](/images/the_elbow_method.PNG)
![](/images/cluster_centriod.PNG)
![](/images/dentograms.PNG)
![](/images/clustering_using_by_heriarchial.PNG)

# [Project 9: stock_headlines](https://github.com/sam23121/stock_head)
it predicts if the stock has gone up or down based on the headlines of a newspaper that has 25 topics(headlines). 
it does data preprocessing, data wrangling and merging, data visualization. it was trained on random forest and naive bayes











