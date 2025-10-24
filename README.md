# 🧮 Flask Age Calculator

A simple **Flask web app** that calculates a user's age (in years, months, and days) based on their **Date of Birth (DOB)**.

---

## 🚀 Features

- User inputs their date of birth using an HTML date picker.  
- Calculates and displays the exact age (Years, Months, Days).  
- Handles invalid inputs (like future dates).  
- Uses **Flask**, a lightweight Python web framework.  

---

## 🛠️ Technologies Used

- **Python 3**
- **Flask**
- **HTML / CSS**
- **Jinja2 Templates**




## ⚙️ Installation and Setup

1. **Clone the repository** 

   ```bash
   git clone https://github.com/<your-username>/flask-age-calculator.git
   cd flask-age-calculator 
  **or download the folder**
  
## 📂 Project Structure

age_calculator/
│
├── app.py # Main Flask application file
├── templates/
│ └── index.html # HTML template for input and output
├── static/ # (Optional) Folder for CSS/JS files
└── README.md # Project documentation

  
Install dependencies
pip install flask

Run the app
python app.py

Open in your browser

Go to 👉 http://127.0.0.1:5000/

🧠 How It Works
The user enters their Date of Birth (DOB).

The form sends the DOB to the /submit route via POST.

Flask extracts the year, month, and day from the DOB.

The /calc route calculates the age by comparing with today’s date.

The result (years, months, days) is displayed on the same page.

🖼️ Example Output

Input:
📅 Date of Birth: 2005-05-28

Output:

🎉 You age 20 years, 4 months, 26 days.

🧩 Notes
Make sure your HTML form uses method="POST" and includes an input named dob.

The app uses redirect(url_for()) to safely pass DOB values as URL parameters.

app.secret_key is used for Flask’s session and flash features.

📜 License
This project is open source under the MIT License.

❤️ Author
Praveenkanth G
📍 Villupuram
Built with 💖 using Flask and Python.








