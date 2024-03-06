## Regex Matching Web App Development Project

## Objective:
<p>Your task is to replicate the core functionality of the website regex101.com. This entails creating a web application that allows users to input a test string and a regular expression (regex) and displays all the matches found.</p>

## Steps:
## 1. Create a new directory for your project and navigate into it.

## 2. Set up your virtual development environment:
   <p>- Install Flask, a Python web framework, using pip if not already installed: `pip install Flask`.</p>

## 3. Initialize a new Flask application:
   <p>- Create a new Python file named `app.py`.</p>
   <p>- Import Flask and create a new Flask app instance.</p>
   <p>- Define a route for the home page ("/") where users can input the test string and regex.</p>
   <p>- Render an HTML template containing a form with fields for the test string and regex, and a submit button.</p>

## 4. Create the HTML template:
   <p>- Create a new directory named `templates` within your project directory.</p>
   <p>- Inside the `templates` directory, create a new HTML file named `index.html`.</p>
   <p>- Design the HTML form with input fields for the test string and regex, and a submit button.</p>

## 5. Define a route to handle form submission:
   <p>- Define a new route ("/results") in your `app.py` file to handle form submission.</p>
   <p>- Extract the test string and regex submitted by the user from the form data.</p>
   <p>- Use Python's `re` module to perform regex matching on the test string.</p>
   <p>- Store the matched strings in a list.</p>

## 6. Render the results:
   <p>- Pass the list of matched strings to the HTML template.</p>
   <p>- Modify the HTML template to display the matched strings below the input form.</p>

## 7. Test your application:
   <p>- Run your Flask application (`python app.py`).</p>
   <p>- Open a web browser and navigate to http://localhost:5000 to access your application.</p>
   <p>- Input various test strings and regex patterns to ensure the application displays the correct matches.</p>

## 8. (BONUS) Implement a new route where a user can validate if a given email id is valid or not.

## 9. (IMPORTANT) Deploy the application on AWS Cloud.
