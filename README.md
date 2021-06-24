# fullstack Challenge

Hi,
Your challenge, if you accept, is to design and implement a e commerce web app with a shopping cart that would allow users to add items to their basket and checkout when they’re ready.

For this exercise you’ll have full ownership of a Google Cloud Project to help you in your development.

You can use any typed language you want and use any library you want to complete this project

## Requirements
* The project should be able to run locally with docker compose
* The project should be deployed on Google Cloud and be accessible publicly
* User stories should be done in order and following the designs in [this figma file](https://www.figma.com/file/n4WlvWZefXti26xLd1mX34/Somm---marketplace?node-id=0%3A1). You can seed the products you’ll need by creating fake products. The expectation is at least 2000 items seeded.

### User story 1
As a user I can see a list of products the web app is selling

<img width="1116" alt="image" src="https://user-images.githubusercontent.com/1434359/123333766-2a409280-d510-11eb-8de3-cac05ef89714.png">


### User story 2
As a user I can add or remove a product to a shopping cart. 
I should be able to see how many items are in my shopping cart as I add them

<img width="220" alt="image" src="https://user-images.githubusercontent.com/1434359/123333658-054c1f80-d510-11eb-8163-8f2b8c3006c1.png">


### User story 3
As a user I can see my shopping cart while still shopping. When I click on the shopping cart icon, a drawer should open with the content of my shopping cart 

<img width="578" alt="image" src="https://user-images.githubusercontent.com/1434359/123333816-3a587200-d510-11eb-9b6b-6ef5741966cd.png">

### User story 4
As a user I can see the items I previously ordered at the top of the page so I can buy them again if I want.
For this story, users need to be able to have an account and check out products. 
* Keep signup very simple. It doesn't have to be secured. The app needs only needs to recognize a user.
* Check out can be simulated and a simple click on the `Check Out` button can be enough.

<img width="221" alt="image" src="https://user-images.githubusercontent.com/1434359/123333849-46443400-d510-11eb-94d2-7462e14d03f7.png">


### User story 5
As a user I can search for a product by its name and only the products that have a name close to my query should be shown

<img width="221" alt="image" src="https://user-images.githubusercontent.com/1434359/123333849-46443400-d510-11eb-94d2-7462e14d03f7.png">


## What will you be evaluated on?

For us, quality matters more than quantity. We respect your time, so please only complete as much as you can in a reasonable time frame and we will continue our discussion should you be selected to come in for an interview.

## You’ll be evaluated on the following:
* The code you write should be a reflection of what you’d do for a real production application. Or if you take shortcuts, you should be able to explain during the interview why those shortcuts have been taken and what you would have done otherwise.
* Components have a single and clear responsibility
* Components are unit tested
* Code is easy to read
* Challenge does NOT have to be entirely finished
