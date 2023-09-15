# Challenge - https://chat.openai.com/

1. Prompt ChatGPT to create a pseudo language to create HTML forms

2. If you like the suggestions, 
use the pseudo language to create a form.
Ask for adjustments if necessary. 
If the language is too complicated, reprompt
with an instruction to keep it simple. 

## Prompt
Create a pseudo language that will help me quickly describe
to you how to provide sample code and styles for an HTML form.
Respond with a template I can use, as well as a sample element. 

_______________________________________________________________

# Pseudo Language for HTML Form Generation

form:
  attributes:
    action: "/submit-form"
    method: "POST"

  text_input:
    label: "First Name"
    name: "first_name"
    attributes:
      placeholder: "Enter your first name"
      required: true

  text_input:
    label: "Last Name"
    name: "last_name"
    attributes:
      placeholder: "Enter your last name"
      required: true

  password_input:
    label: "Password"
    name: "password"
    attributes:
      placeholder: "Enter your password"
      required: true

  submit_button:
    label: "Submit"

end_form: