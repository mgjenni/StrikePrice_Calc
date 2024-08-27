# StrikePrice_Calc

<h1>Strike Price Calculaor</h1>


<h2>Description</h2>
I recently completed a project that allowed me to blend two of my passions: cloud technology and stock trading. I developed a web-based calculator that helps determine the optimal strike price for a CALL option, based on the current stock price and a target percentage.
<br />


<h2>Services and Languages used</h2>

- <b>AWS Lambda</b> 
- <b>AWS IAM</b>
- <b>AWS Amplify</b>
- <b>AWS CloudWatch</b>
- <b>AWS Dynamodb</b>
- <b>AWS API Gateway</b>
- <b>Pyton</b>
- <b>Javascript</b>
- <b>JSON</b>
- <b>HTML</b>
- <b>CSS</b>

<h2>Key Learnings </h2>
- Gained practical experience with AWS services like Lambda, IAM, Amplify, CloudWatch, DynamoDB, and API Gateway.
- Deepened my understanding of database operations and how to effectively set up APIs with API Gateway and JavaScript.
- Overcame challenges in debugging HTML scripts and writing Python code for Lambda functions, particularly in database interactions.


<h2>Environments Used </h2>

- <b>Amazon Web Services</b>

<h2>Program walk-through:</h2>

<p align="center">
Create a CloudWatch alarm to keeo track of resource usage: <br/>
<img src="https://i.imgur.com/Lxysfby.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<br />

<p align="center">
Creat new user separate from root user for security purposes: <br/>
<img src="https://i.imgur.com/FMJfobZ.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<img src="https://i.imgur.com/5yw5Xhr.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<br />

<p align="center">
Use Amplify to host web page: <br/>
<img src="https://i.imgur.com/pvvUMym.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<br />

<p align="center">
Create Dynamodb database to hold strike prices: <br/>
<img src="https://i.imgur.com/ATLNTts.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<br />

<p align="center">
Write Lambda function and test: <br/>
<img src="https://i.imgur.com/nqD0iDc.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<img src="https://i.imgur.com/CPaHMpt.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<img src="https://i.imgur.com/K8VyztA.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<br />

<p align="center">
Give Lambda function permission to write to the database: <br/>
<img src="https://i.imgur.com/IixAft6.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<br />

<p align="center">
Set up API Gateway so that the lambda function can be called from Javascript <br/>
<img src="https://i.imgur.com/Xj7o8eF.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<br />

<p align="center">
Front End Walkthrough and Results<br/>
<img src="https://i.imgur.com/c9OGKyo.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<img src="https://i.imgur.com/ogY79Wh.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<img src="https://i.imgur.com/ahtghKF.png" height="80%" width="80%" alt="StrikePriceSteps"/>
<br />



