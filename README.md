# Dynamic Job Application Form

This project is a responsive job application form built with HTML, CSS, and JavaScript. It includes interactive features such as gender-based button styling, form validation, and dynamic input display based on user selections.

## 🧾 Features

- Input fields for Name, Surname, Email, and Gender
- Dropdown menu for selecting desired job position
- Conditional display of additional input field if "Other" is selected
- Gender-based button color:
  - 🔵 Blue if Male
  - 🌸 Pink if Female
- All fields are **required**
- On submission:
  - Form data is saved as a JSON object in a list
  - Form resets for a new entry

## 💡 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks)

## 🧪 How It Works

1. The user fills out the form.
2. If "Other" is selected in the job dropdown, a new text field appears.
3. The button color changes based on the selected gender.
4. When the **Guardar** button is clicked:
   - Data is validated
   - A JSON object is created and pushed into a list
   - The form is cleared for a new registration

## ▶️ Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Jeann1809/Dynamic-Job-Application-Form.git
