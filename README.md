# Easy Lend

### Problem Statement-
Loan Approval Systems are data biased and service is not available everywhere and requires lot of time investment.

### What it does
The Loan Approval System takes the application of loans submitted bu various people and predicts the chances of the loan getting approved without any bias.

There are three ways to access it: a. Through a Web Application b. Through a WhatsApp Chat Bot c. Through Direct SMS

In the App, it provides an in-depth analysis of the different factors such as income, past experience, and many others. It will provide a detailed report through which a person can have a better chance next time.

For people with less technical knowledge or no internet also, we have the WhatsApp Chat Bot method and the Direct SMS method respectively. The chances of approval is sent after a thorough analysis without any bias to the user on the respective channel through which he/she applied.

### How we built it
1) Extracted Loans and Demographics Dataset from Finastra Cloud Service.
2) Trained different models on the dataset to detect and reduce both Algorithmic and Physical Biases.
3) Selected the best model based on F1 Score and Roc-Auc Curves of different models.
4) Integrated the Random Forest model on three gateways: Web App, SMS Bot, and WhatsApp Bot. ## Challenges we ran into

a) Data Science :
1) Selecting the best models from the six models we trained on Finastra’s Dataset.
2) Integrating the visualization of the result from the model on WebApp.

b)Direct SMS and WhatsApp Bot :
1) Sending the text message back from the Flask server to the SMS bot running on NodeJS code after making loan approval predictions.

2) Integrating the full-fledged WhatsApp bot with the backend server to get the predictions.

### Made by
1. [Akshay Singhal](https://www.github.com/akshsinghal "Akshay Singhal")
2. [Punit Lohia](https://www.github.com/punitlohia "Punit Lohia")
3. [Saksham Pandey](https://www.github.com/Saksham-510 "Saksham Pandey")
4. [Ketan Bansal](https://www.github.com/bansalketan "Ketan Bansal")
5. [Ashlesha Kumar](https://www.github.com/thecodeeagle "Ashlesha Kumar")
6. [Ashutosh Sharma](https://www.github.com/ashucrma "Ashutosh Sharma")

Credits - Kunal Goyal for template of WebApp.
