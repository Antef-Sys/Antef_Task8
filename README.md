🧺 Laundry Wallah
https://antef-sys.github.io/Antef_Task8/

📌 Project Overview
Laundry Wallah is a responsive front-end web project that provides a modern user interface for a laundry service. It allows users to explore services and interact with a clean and simple layout.

🚀 Features
Responsive design (Mobile, Tablet, Desktop)
Navigation bar with menu options
Sidebar menu using CSS :focus-within pseudo-class
Clean UI using Flexbox
Call-to-action button ("Book a Service today!")
🛠️ Technologies Used
HTML5
CSS3 (Flexbox + Media Queries)
No JavaScript used
🎯 Key Concept Used
🔹 :focus-within Pseudo-Class
This project uses the :focus-within pseudo-class to toggle the sidebar menu without JavaScript.

How it works:
The menu container becomes focusable using tabindex="0"
When the button inside it is clicked, the container gains focus
The sidebar becomes visible using:
.men:focus-within .sidebar {
    transform: translateX(0);
}
When the user clicks outside, focus is lost → menu closes
📱 Responsive Design
Desktop (>768px):

Full navigation bar visible
Tablet (555px - 768px):

Adjusted layout and font sizes
Mobile (<555px):

Navbar links hidden
Sidebar (hamburger menu) used
▶️ How to Run the Project
Download or clone the repository
Open the project folder
Open index.html in your browser
📂 Project Structure
LaundryWallah/
│── index.html
│── style.css
│── images/
│── icons/
💡 Future Improvements
Add JavaScript for better interaction
Add login/signup functionality
Connect with backend for real services
Add animations and transitions
👨‍💻 Author
Antef

⭐ Note
This project is built for learning purposes and demonstrates how to use CSS pseudo-classes like :focus-within to create interactive UI without JavaScript.