# AV_ripikai-hackfest-unleashing-ai-potential

### Competition hosted on <a href="https://datahack.analyticsvidhya.com/contest/ripikai-hackfest-unleashing-ai-potential/?utm_source=auto-email#About">Analyticsvidhya</a>

# About

### Develop a robust and high-performance model for classifying an image of a car into different types of damages automatically with the help of computer vision techniques. By accurately identifying the damages, the insurance company can assess the legitimacy of the claim and make informed decisions regarding payouts.

### The Final Competition score is 0.7861701844

### Final Leaderboard Rank is 36/204.

### The Evaluation Metric is macro f1 score.

### File information
 
 * EDA [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/hari141v/ripikai-hackfest-eda/notebook)
    #### Basic image information analysis
    #### Images RGB color analysis
    #### Image similarity analysis
    #### Packages Used,
        * seaborn 
        * Pandas
        * Numpy
        * Matplotlib
        * imagehash
        * distance
        * Image
        * cv2

* Model
  #### Trained the convnext_xlarge_384 model using the Fastai Vision Learner on stratified split training data with various augmentations. Two epochs were used for training, and early stopping was implemented to control overfitting by monitoring the validation log loss. The test data was predicted, and test-time augmentation was applied to ensure confident predictions.
