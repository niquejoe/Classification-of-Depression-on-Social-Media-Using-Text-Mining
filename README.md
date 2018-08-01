<center><h1>Classification of Depression on Social Media 
	<br>Using Text Mining</h1></center>

<h4><a href="#about">About me</a> | <a href="#introduction">Introduction</a> | <a href="#project">The Project</a> | <a href="#reference">Reference</a></h4>


<h2 id="about">About Me  -  나에 대해서 </h2>

<img src="https://lh3.googleusercontent.com/_WfiyUWgmJQ3Gn1KPb7IeBENpT6hapDD6eViS0XX3K5Xitx6koiTvPI4wzaKPHSJSoyt4XyA0dWcQhi-cXtx0EcjvQpiwAPjBkJ4rj9Sbx9vdGuriAdzdcxVIoCQiWbPouzZ6d0CBDnhDB0F_ypvVd-uF3tr162BTpCVd-016Nqnz7SkZZ308SJd6EeOTaLZyT4ZmH1EKELmck-3k5AIvS8H-UwavkRVMtKYrScpYaVL4mC42CmtRE3Lua_jFxPAAt5vh6SP1bfxJn43o4Kt5PDcpiGdbzCgX_AbX42Ps0_KFHTzCSbMn6zM0fQB9V4aP_qvL5ZDCeOyWO4YO4P__42lZKBZpm17Yo1qByC-ZtEalgRAtSlIdGXDbdtbdQ4VsX6qIc2r7o0G1hu4w9f518mvNrT_QxVzW2sPUvmDlYP-RRTIsdyateJ7_580cKFGBbbpclj4u6n7XxyNfA1tqDxlZTWODWDEA4agK7bNf4-iomdXjjKIJBQ4XBdbEBls4PWfdCHgZ6q2-M_euppM3-2D0cmZ4MTI4oTR5c31XalMMlxWdQ4GRsa24VeZzIEb1TuCnDgLrzwSOd-KPz5BgCYMKjX4Soemh4nSyRq_Zz4pSY577KPFQoCa4rq9FhKCC8KXAL6zhSg2bai-v90qoqgVMsjYIMs7=w876-h1312-no" width="200" align="left" style="border: 2px solid #000"/>

<p>
	<p><strong>Name:</strong> Nikie Jo Elauria Deocampo</p>
	<p><strong>Country:</strong></h4> Philippines</p>
	<p><strong>Educational Background:</strong>
		<p>
			<p><u>Undergraduate:</u></strong> Bachelor of Science in Information System</p>
			<p><u>Graduate:</u></strong> Masters in Information Technology</p>
			<p><u>School:</u></strong> West Visayas State University</p>
		</p>
	</p>
	<p><strong>Mentor:</strong> Dr. Bobby Gerardo</p>
	<p><strong>Motto:</strong> I work hard so my dog can have a better life.</p>
</p>


<h2 id="introduction">Introduction  -  소개</h2>

<p>Mental illness has been prevalent in the world, depression is one of the most common psychological problem i know and i would like to help as much as i can. Being a fan of Anthony Bourdain and Robin Williams, It has propel me to explore in this study. With the use of the Large amount of data tweets and Facebook post online i can use machine learning to data mine it and be able to produce a meaningful and useful outcome.</p><p>Social media generates countless data every day because of millions of active users share and communicate in entire
community, it changes human interaction. For this project, I will be using Python and various modules and libraries.</p>


<h2 id="project">The Project  -  프로젝트</h2>

<strong>Requirements:</strong>
<p>
	<ul>
		<li>Python 3.6.1 or Higher</li>
		<li>Twitter developer account</li>
		<li>A bunch of modules</li>
		<li>and A whole lot of patience</li>
	</ul>
</p>

<p>The aim of the project is to predict early signs of depression through <strong>Social Media</strong> text mining. Below are the steps to run the python codes using the data sets uploaded in the repositories or you can download your own.</p>

<strong>Follow steps below:</strong>
<ol>
	<li>Create a twitter developers account (<a href="https://developer.twitter.com/">LINK</a>), From that account your would need 4 things (consumer_key, consumer_secret, access_token and your access_secret)</li>
	<li>Using the file "Download_twitter_Api.py" insert the credentials and you can download current tweets using keywords such us depression, anxiety or sadness. When data sets are ready you may proceed on the preprocessing stage. </li>
	<li>Run "preprocessor.py", This stage will go through your data sets and the given dictionary. The dictionary contain words with their corresponding polarity, which is essential to calcualting the sentiment of each tweet, each word will be seperated, tokenized and given its polarity. Every tweet will consist of the summation of all polarity of each word and devided by number of words in that tweet.</li>
	<li>Once preprocess is done. You can find the file in the directory "processed_data/output.xlsx". Opening it you will find that the ID (tweet) and Sentiment of each tweet is seperated into 2 columns. With this output you now have a twitter data set and its corresponding sentiment filtered by depress keywords. (Positive, Neutral and Negative).</li>
	<li>Now for training and Predicting. Make sure all files are located in proper folders, Run "depression_sentiment_analysis.py". The code will run through the output.xlsx file and at the same time recover the tweet corresponding to the id of each sentiment. using this we use the original data and feed them to our classifiers. When everything is done you should have all the AUC of each classifier listed in the console.</li>
	<li>But wait, There's more. TO BE CONTINUED</li>
</ol>





<h2 id="reference">Reference  -  참고</h2>

<ul>
	<li>https://www.researchgate.net/publication/318136574_Extracting_Depression_Symptoms_from_Social_Networks_and_Web_Blogs_via_Text_Mining</li>
</ul>
