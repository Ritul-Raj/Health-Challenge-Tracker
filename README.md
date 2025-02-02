Health Challenge Tracker
A single-page application (SPA) built with Angular 14+ to track users' workouts, featuring search, filtering, pagination, and optional charts for progress visualization.

🚀 Live Demo
Health Challenge Tracker

📂 Repository
GitHub Repository

📌 Features
Add users with workout details (workout type & duration)
Display workouts in a table grid
Search users by name
Filter workouts by type
Pagination for better data handling
Data persistence using localStorage
Bonus: Workout progress visualization using charts 📊
🛠️ Tech Stack
Framework: Angular 14+
UI Libraries: Angular Material, PrimeNG
Styling: Tailwind CSS
Data Storage: LocalStorage
Chart Library: Chart.js (if implemented)
🏗️ Project Setup
Clone the repository
sh
Copy
Edit
git clone https://github.com/Ritul-Raj/Health-Challenge-Tracker.git
cd Health-Challenge-Tracker
Install dependencies
sh
Copy
Edit
npm install
Run the application
sh
Copy
Edit
ng serve
Open http://localhost:4200 in your browser.
🧪 Testing
Run unit tests
sh
Copy
Edit
ng test
View code coverage report
sh
Copy
Edit
ng test --code-coverage
Coverage report is generated in the /coverage folder.
📌 Assumptions
Initial data contains 3 users with workouts.
Pagination is applied when the user list exceeds 5.
LocalStorage is used for data persistence.
UI components are styled with Tailwind CSS.
The app is deployed on Vercel.
📝 To-Do (Future Enhancements)
Implement authentication & user profiles.
Allow workout deletion & editing.
Enhance charts with more insights.
