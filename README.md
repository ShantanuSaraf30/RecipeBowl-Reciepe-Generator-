# Homemade RecipeBowl:Your Ingredients Our Recipes


## Instructions:

### For running the Frontend in React:

#### Create a **new folder** for react frontend:

- Installing npm: $npm install -g create-react-app
- Creating react project: $create-react-app \&lt;project\_name\_all\_in\_lower\_case\&gt;
- Copy (by replacing) all the files in the &quot;Website&quot; folder into the newly created react project folder.
- Run the backend server (given below) in a separate command prompt.
- Activating the environment, in &quot;Website\api&quot; folder: $venv\Scripts\activate
- Return to parent folder, i.e., react project folder: $cd ..
- Running react project: $npm start

### For running the Backend server in Flask:

#### In **&quot;Website Front End\api&quot;** folder:

- Creating virtual environment, i.e. venv, : $python -m venv venv (replace already present venv folder in &quot;Website\api&quot;, if prompted)
- Activating environment : $venv\Scripts\activate
- Running flask file: $flask run --no-debugger


**What is Homemade RecipeBowl:**

<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/Homemade-Recipebowl.png" width="35%" height="35%">

We aim to make a user aware of the various dishes which can be cooked from available set of ingredients or an input image given by a user.
Thus, systems like this never get their place in real life. We’ve developed a Recipe Generation model by applying Neural Network on it. The tools used for developing the project are Python, React, CSS, JavaScript & Flask.
- A dynamic website incorporating machine learning techniques.
- Search options:
  - Search by Ingredients
  - Search by food image
  - Search by cuisine
- Output: self generated recipes
- It is a recipe generator system and not a recommender system!!!
- An additional feature for sharing food related content in the form of posts.


Following is our approach divided into different phases about the solution of the problem.

<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/Workflow.PNG">

<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/Flow%20chart%201.png">

## WEB APPLICATION:

**Website Homepage:**

The website first opens up the homepage, which is the central point of use for the user. There are three options available here: Recipe by Ingredients, Recipe by Image & Recipe by Cuisine.

<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/Homepage1.png">
<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/Homepage2.png">

**Login:**

The user can login with his Username and Password.

<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/login1.png">

Also, they can sign up or register if they don’t have an account already.

<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/login2.png">

**Dashboard:**

After user login, we can open the dashboard. Here the user can change the profile picture, change password, change bio, and view his/her favorite Recipes and his/her posts.


<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/dashboard2.png">
<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/dashboard3.png">

**Feed for Sharing your Ideas, recipes and many more in the form of Posts:**

Now here’s something which made our project even more interesting. As you all must have seen feed in all social media platforms, we thought why not to add the same in our website, but in a different context. Here, people can share food related memes, recipes, images, and can also comment on one-another's post. A Random recipe is also shown in the feed using an API.


<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/feed2.png">

**Prediction Time:**

Now let’s give ingredients input to the website and get the generated recipes as output.

<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/prediction-time.png">

After getting the desired results:

<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/prediction-time2.png">
<img src="https://github.com/ankitgoyal0301/Homemade-RecipeBowl-Your-Ingredients-Our-Recipes/blob/master/Documentation/Images/prediction-time3.png">

## DISCUSSION:

Through this project, we have made a system that has the potential to generate recipes out of the given set of ingredients. Also, this project has the potential to get implemented in different parts of the world helping users with making delicious recipes at their disposal.

Also, the image to recipe feature can be widely used to help generate the recipes of the most delicious looking recipe images.

Also, As you all must have seen feed in all social media platforms, we thought why not to add the same in our website, but in a different context. Here, people can share food related memes, recipes, images, and can also comment on one-another's post.


**CURRENT BUGS / CHALLENGES:**

- The Ingredients-to-Recipe generator produces some irrelevant outputs sometimes.

**FURTHER SCOPE:**

- Getting access of MIT dataset and training the Ingredients-to-Recipe generator to improve it further.
- The Post’s feed can be further developed to recommend posts based on user’s choices.
- Discussion forum for Q/A among the users.
- Peer to peer direct chat communication.
