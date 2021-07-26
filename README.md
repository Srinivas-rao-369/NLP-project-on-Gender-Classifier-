# NLP-project-on-Gender-Classifier-

For the detailed description of the dataset provided please refer to the following link.

https://www.kaggle.com/crowdflower/twitter-user-gender-classification

1)	How cleaning/EDA was performed:We need to read the data description in order to understand what each column means.
After understanding the data description ,find out the 
      a)	missing values , outliers , relation between independent and dependent features.
      b)	Here I used heatmap ,Correlation Matrix to find out the relation and outliers.
      c)	Filling missing values 
      d)	Dropping nan rows
      e)	Normalizing text 
      f)	CLEANING text with REGULAR EXPRESSION
      g)	removing stop words, removing punctuations

2)	Your independent and dependent feature;

3)	

      a)	independent feature: '_golden', '_unit_state', '_trusted_judgments',
          '_last_judgment_at', 'gender:confidence', 'profile_yn', 'profile_yn:confidence', 'created', 'description', 'fav_number',
          'link_color', 'name', 'profile image', 'retweet_count', 'sidebar_color', 'text', 'tweet_count', 'tweet_created', 'tweet_id', 'text_norm',  ‘description_norm'
 
      b)	Dependent feature:     ‘Gender’

4)	Why and how selection/engineering/scaling was performed:
      
      i)	Normalizing text
      
      ii)	Feature selection with Correlation Matrix with Heatmap and feature importance

5)	Which activation function was chosen and why?

      a)	It is used to determine the output of neural network like yes or no. It maps the resulting values in between 0 to 1 or -1 to 1 etc. (depending upon the function).
      
      b)	Here we are using Logistic function (sigmoid function).
      
      c)	The main reason why we use sigmoid function is because it exists between (0 to 1).
      
6)	Which optimizer was chosen and why?
      a)	 optimizers shape and mold your model into its most accurate possible form by futzing with the weights.
      
      b)	Optimizers are related to model accuracy.
      
7)	Which neural network and why? Describe how your neural structuring? 

      a)	 sigmoid neuron
      
      b)	In the sigmoid neuron, a small change in the input only causes a small change in the output as opposed to the stepped output.
      
      c)	 The used function is the logistic function.

                            Model 	        Accuracy Score
                        MLPClassifier	    0.3277310924369748
                        Naive bayes	      0.4534917415241959



