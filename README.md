🎉 Build an Event RSVP App

A simple React-based web application that allows users to RSVP to an event by submitting their details through an interactive form.

🚀 Features
Collect user information (name, email, number of attendees)
Optional dietary preferences input
Checkbox for additional guests
Form validation (e.g., minimum attendees)
Dynamic confirmation display after submission
Built using React functional components and hooks
🛠️ Technologies Used
React (useState hook)
JavaScript (ES6+)
HTML5
CSS3
📂 Project Structure
Build-an-Event-RSVP/
│── index.html
│── styles.css
│── index.jsx
⚙️ How It Works
The form captures user input using React state (useState)
On submission:
Prevents default page reload
Stores input data in state
Displays a confirmation message with submitted details

Installation & Setup
Option 1: Run in Browser (Simple)
Clone the repository:
git clone https://github.com/Yasser514/Build-an-Event-RSVP.git
Open index.html in your browser
Option 2: Run with React (Recommended)
Create a React app:
npx create-react-app rsvp-app
cd rsvp-app
npm start
Copy logic into src/App.js
Event RSVP
Name
John Doe

Email
example@example.com

Number of attendees
2

Dietary Preferences
None

Additional guests?
Submit
RSVP Sent!

Name: John Doe

Email: example@example.com

Email Status: ✓ Valid

Number of attendees: 2

Dietary Preferences: None

Additional guests?: Yes



🌐 Live Demo

(Add deployed link here — e.g. Vercel / Netlify)

💡 What I Learned
Managing form state using React hooks
Handling user input and events
Conditional rendering after form submission
Building interactive UI components
⚡ Challenges
Handling multiple inputs efficiently
Preventing page reload on submit
Managing and displaying submitted data
🔮 Future Improvements
Store RSVPs in a database (Firebase / MongoDB)
Add authentication (login/signup)
Create multiple events
Improve UI with Tailwind CSS or Material UI
Deploy as a full-stack application
👤 Author

Yasser
GitHub: https://github.com/Yasser514
