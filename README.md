# DataCleaningProject
Following is a Data Cleaning Challenge on Kaggle.


Challenge 1 - Handle missing values in a dataset.
   Dataset consists of SF Building permits downloaded from Kaggle.
   After analyzing data missing values are treated using dropna and fillna functions in pandas and imputation methods.
   
Challenge 2 - Scaling and Normalizing data.
              Dataset consists of kickstarter data.
  Scaling is done for changing the range of the data.
  This means that you're transforming your data so that it fits within a specific scale, like 0-100 or 0-1. 
  You want to scale data when you're using methods based on measures of how far apart data points, 
  like support vector machines, or SVM or k-nearest neighbors, or KNN. With these algorithms, a change of "1" in any numeric 
  feature is given the same importance.
  Tools/libraries used - numpy,seaborn,mlxtend for minmax scaling
  
  Normalization is done for changing the shape of the distribution of your data.
  Generally,we only want to normalize the data if we're going to be using a machine learning or statistics technique that assumes the data is normally distributed. 
  Some examples of these include t-tests, ANOVAs, linear regression, linear discriminant analysis (LDA) and Gaussian naive Bayes
  Tools/libraries - Scipy for Box cox transformation
  
Challenge 3 - Parising Date.
  Many datasets comes with inconsistent date formats.Here we look for datatype of date columns and change its format accordingly.
  Dataset used earthquakes,landslides.
  
Challenge 4 - Character encodings
  Character encodings are specific sets of rules for mapping from raw binary byte strings (that look like this: 0110100001101001)
  to characters that make up human-readable text (like "hi"). There are many different encodings, and if you tried to read in 
  text with a different encoding that the one it was originally written in, you ended up with scrambled text called "mojibake" 
  (said like mo-gee-bah-kay).
  Tools/libraries used - chardet for character encoding
  
Challenge 5 - Inconsistent Data Entry
  Data captured from internet consists a lot of inconsistent data like typos,spelling mistakes,capitalization.
  In this challenge we are going to treat them.
  Dataset used - Pakistan Suicide Bombing Dataset.
  Tools/libraries used - numpy,pandas,fuzzywuzzy,chardet
  
  We use the fuzzywuzzy package to help identify which string are closest to each other. This dataset is small enough that we could probably
  could correct errors by hand, but that approach doesn't scale well. (Would you want to correct a thousand errors by hand? 
  What about ten thousand? Automating things as early as possible is generally a good idea. Plus, it’s fun!
  
  Challenge 6 - Outlier Detection and Removal.
  Data collected from internet consists of ooutliers too.Outlier is basically a point that is far away from the mean.
  When such dataset with outliers are used in machine learning models the ouput is largely affected with it producing errors.
  
  We will be detecting the outliers using interquartile range and simply remove data beyond the interquartile range.
  
 
  
  
  
  
