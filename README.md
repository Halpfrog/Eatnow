Milestone 2 Orbital 2021

Proposed Level of Achievement: 

Gemini 

Motivation 

When you want to order food online, it is a hassle to figure out which food delivery service gives you the best deal. Having to sift through multiple applications in search of the cheapest option can be troublesome, especially with surge pricing causing prices of food delivery services to be inconsistent.

Many of us have simply gone with the first option we find simply to avoid the hassle of using multiple applications and we hope to change this by giving consumers a way to get the best bang for their buck in the shortest time possible. 

Aim 

We hope to make the comparison between ordering services easier with the use of a simple website that will link you to the various delivery options available. 

User Stories

1. As someone in a rush I want to be able to get the best value for my delivery while spending the least amount of time searching through different applications. 

2. As a senior citizen who may not be very tech savvy, I would prefer to be able to view the cheapest option for ordering food instantly without having to open several applications

3. As a university student who is trying to save money, I would like to know the best deal offered for a particular restaurant by the different food delivery services.

4. As an administrator, I would like to clarify the authenticity of the deals offered in the delivery applications such that the orders placed would be successfully delivered.

Scope

A website capable of displaying the delivery prices of each food delivery option and directing you to the application with the cheapest delivery price will be the main deliverable. 


Website


Allow users to view a breakdown of the price of food delivery from different applications so that they make an informed decision on which food delivery service to use.

Provide Users with a most popular Restaurant in their area to act as a suggestion into what they can order. 



Problems faced:

We faced issues using the API that grab distributes to its partners. We were refused access as we were not looking to use the grab delivery network. Due to this we had to change our idea on how we were going to grab the detailed delivery costs for a certain restaurant. We attempted to make contact with grab to allow us access for this project but have not heard back from them. The API for foodpanda however does not provide this information regardless. 

Another issue we faced is that most delivery websites will automatically block you if you attempt to access it via any sort of scraper. Due to this they redirect you to a captcha that cannot be solved thus leading us to another roadblock. At the same time grab uses a measure of requiring logging in along with not keeping your basket in a separate url. This makes most methods of HTML scraping unusable as the final delivery price is always locked behind a log in as well as a url that will redirect to its home page if accessed directly. 

Possible Solutions:

We are working towards perhaps reworking the web app to provide users with the links of different delivery options for the same restaurant within a certain radius around them. This would thus not require us to scrape prices from any food delivery company along with providing a time saving feature to users. While this is a step down from what we originally envisioned, it seems like the initial idea is not feasible as most food delivery services are not designed to allow for access to delivery prices. 

	

Poster link: https://drive.google.com/file/d/1X4jX5AFzbi1WddDCjFDgb9DUUd9Ski_u/view?usp=sharing
Video link: https://drive.google.com/file/d/1iaeWAsgxNPhzju_tblBrj4inLd8KFesF/view?usp=sharing

Tech Stack
1. Grab API
2. HTML/CSS/Javascript
3. Python
4. Foodpanda API
5. Telegram API
 

