<pre>

The competition has been organised by the <a href= 'https://datahack.analyticsvidhya.com/contest/enigma-codefest-machine-learning/'>Analytics Vidhya</a>.

Here,
Public LB= 147
Private LB= 58

The dataset has based on regression type machine learning models. Here, we have to predict the no. of upvotes using the given features.

For more info <a href= 'https://datahack.analyticsvidhya.com/contest/enigma-codefest-machine-learning/'>visit</a>.

My Approach

1. First I tried with ANN network but not worked well and I got error.

2. 2nd I tried with the CatBoost ml model, on validation dataset that algo worked well but on the other hand it didn't worked on the test dataset.

3. Then tried with XGBoost algorithm it looked quite effective in case of validation dataset as well as testing dataset.

4. Then I created some arftificial features using the given features like ratio of two features, scaling with mean of the given feature, etc.

5. After, when I tried with XGBoost, it again showed efective result than previous one.

6. After, I tried with LightGBM but it didn't worked well in that.

Thus, the XGBoost Algorithm worked well in that dataset.

For more info visit the notebook.

</pre>
