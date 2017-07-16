# TwitterSentimentAnalysis
A Data Science and JSON Processing project, focused on sifting through real-world data (downloaded from Twitter servers), to get relevant information. This project uses JavaScript, jQuery, Bootstrap, 3rd party libraries: Hightcharts, Porter Stemmer and Corpus, HTML, and CSS.

Given a large collection of Twitter data in JSON format, the task was to understand the data structure of Twitter API and use that to traverse through, and isolate the following information: 
- User Name
- User Handler
- User Photo
- Tweet Body
- Date Tweeted
- Country of Origin

From here, the tweets had to be analysed and given a mood rating of Happy, Neutral, or Bad/Sad. The Porter Stemmer library is applied to the tweets to strip each word down to its root. The "stemmed" roots are then cross-referenced with the Corpus library to obtain the individual mood rating of the words. The average mood of the tweet is computed, and together with the rest of the isolated information, is printed in a Twitter feed-like page.

Each mood has an emoji representing it:
<div>
<img src="https://user-images.githubusercontent.com/29102307/28251087-6ca03a94-6aa8-11e7-9130-88a432158cd0.gif">
<img src="https://user-images.githubusercontent.com/29102307/28251090-6ca72c1e-6aa8-11e7-9712-e686f7a36951.gif">
<img src="https://user-images.githubusercontent.com/29102307/28251089-6ca3fcf6-6aa8-11e7-8c01-9ebbb2e97f51.gif">
&emsp;&emsp;&emsp;&nbsp     Happy    &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;  Neutral   &emsp;&emsp;&emsp;&emsp;&emsp;   Sad/Bad
</div>

<div>
<h3>Main Page - "Tweetdom"</h3>
<img src="https://user-images.githubusercontent.com/29102307/28251076-4d962690-6aa8-11e7-831b-cf483cbaa55f.png" width="900">
<p>The visibility of the emoji may be toggled via button.</p>
<p>As per the project specifications, only 10 tweets are allowed on dispaly at a time. Users may click the "<b>Back</b>" and "<b>Next</b>" buttons endlessly, to display the previous or the next set of tweets. However, whenever the user is on the first set of 10 tweets, the "<b>Back</b>" button is <b>disabled</b>.</p>
<img src="https://user-images.githubusercontent.com/29102307/28251078-4d97c0a4-6aa8-11e7-85b0-3b8e34f0a100.png" width="900">
<p>If a user has a broken image, a default thumbnail is assinged to take its place in the feed.</p>
<img src="https://user-images.githubusercontent.com/29102307/28251088-6ca0d24c-6aa8-11e7-97e9-f8db08f7ff03.png">
<p>Default User Photo</p>
</div>

<div>
<h3>Happiest Countries</h3>
<img src="https://user-images.githubusercontent.com/29102307/28251077-4d96f3ea-6aa8-11e7-8458-3d208a413bd6.png" width="900">
<p>Using the geographic tags included in tweets, the average tweet mood was computed per country.</p>
<p>This was an algorithm we had to try to develop on our own, and the top five I got are shown above.</p>
</div>

<div>
<h3>Top 10 Hashtags and Words</h3>
<img src="https://user-images.githubusercontent.com/29102307/28251075-4d95eb08-6aa8-11e7-8df4-77c2acf5e810.png" width="900">
<p>Another algorithm we developed on our own. Frequency calculations were made on the data to identify the top used hashtags and words.</p>
<img src="https://user-images.githubusercontent.com/29102307/28251074-4d8d5024-6aa8-11e7-9248-f9484f335c68.png" width="900">
</div>

<h4>Available Links to Resources, Notes</h4>
<p>Porter Stemmer: https://github.com/kristopolous/Porter-Stemmer</p>
<p>Corpus: Given as soft copy, as far as I can recall</p>

<p>Molang gifs: http://www.funnyjunk.com/Molang/funny-pictures/5549251#a1540c_5548807</p>
<p>Default user photo: I can't locate the link anymore, I'm sorry! Please let me know if you have it.</p>
