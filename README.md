# HTML-Registration-Form

readme_content = """
HTML Course Registration Form README
------------------------------------

Overview:
This HTML script is designed for a course registration form titled "HTML Course Registration Form". It is structured to allow users to register for a professional HTML certificate course.

Structure:
- The form, identified by 'survey-form', includes input fields for full name, email, phone number, and age.
- It features a dropdown menu for selecting reasons to learn HTML, radio buttons for preferred learning methods, and checkboxes for prior coding experiences.
- There's a textarea for additional comments and a submit button.
- The form also includes contact information and a link to LinkedIn at the bottom.

Styling:
- The webpage uses external styling from Google Fonts and a linked CSS stylesheet ('styles.css').
- The layout is organized with `div` elements classed as 'form-container' for form fields, ensuring a clean and user-friendly interface.

Purpose:
The form serves as an interactive tool for users to sign up for an HTML course, providing various fields to collect necessary information for registration.
"""

# Save to a file
file_path = '/mnt/data/README.txt'
with open(file_path, 'w') as file:
    file.write(readme_content)

file_path
