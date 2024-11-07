# sms_spam_detector

# Module 21 Challenge, SMS text classification solution :

The assignment is to refactor sms_text_classification_solution source code that constructs a SVC model, train the model, and use Gradio app to enable users to test text messages based on the model.

# Setup
- Created new repository in GitHub called sms_spam_detector
- CLoned new repository to my computer
- Download files and update source files to GitHub to begin development

# Step 1:  Create the SMS Classification Function
- Set feature variable to X
- Set target variable to y
- Split data into training and test set; set text_size to 33%
- Build pipeline to transform test set to the training set
- Fit the model to transformed training data and return model
- Lastly, load the csv file to a dataframe and call sms_classification, set results to text_clf

# Step 2: Create the SMS Prediction Function
- Use sms_prediction function to predict the classification of a new text:
    -- Create variable to hold the prediction of new text
    -- Use conditional logic to determine if text message is "ham" or "spam"

# Step 3: Create the Gradio Interface Application
- Create interface application with a text box for input and one for output
- Launch the appllication and share the URL for the application: https://fb6a7696c79841425e.gradio.live/
___
Assignment copmpleted by Louis Canjar with assistance from Xpert Learning Assistant.