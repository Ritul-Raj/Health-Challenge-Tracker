# 🏋️ Health Challenge Tracker  

A **Single Page Application (SPA)** built with **Angular 14+** that helps users track their workouts. The app allows users to add workouts, search and filter data, paginate the list, and visualize progress with charts.

---

## 🚀 Live Demo  
🔗 **[Health Challenge Tracker](https://health-challenge-tracker-nine.vercel.app/)**  

## 📂 GitHub Repository  
🔗 **[GitHub Repository](https://github.com/Ritul-Raj/Health-Challenge-Tracker)**  

---

## 📌 Features  

✅ **User Registration:** Add users along with workout details (workout type & duration).  
✅ **Workout Tracking:** Displays workouts in a structured table grid.  
✅ **Search Functionality:** Quickly search users by name.  
✅ **Filter Workouts:** Filter workouts based on type.  
✅ **Pagination:** Ensures a smooth experience for larger datasets (applies when users exceed 5).  
✅ **Local Storage Persistence:** Stores data locally so that progress isn't lost on refresh.  
✅ **Charts (Bonus Feature):** Displays users' workout progress visually using **Chart.js**.  

---

## 🛠️ Tech Stack  

### **Frontend**  
- **Angular 14+** - Framework for building the SPA  
- **Angular Material** & **PrimeNG** - UI component libraries for enhanced user experience  
- **Tailwind CSS** - Styling framework for responsive design  

### **Data Handling**  
- **LocalStorage** - Persists data on the browser  

### **Visualization**  
- **Chart.js** - For graphical representation of workout progress  

---

## 🏗️ Installation Guide  

### **1️⃣ Clone the Repository**  
Open your terminal and run:  
```sh
git clone https://github.com/Ritul-Raj/Health-Challenge-Tracker.git
cd Health-Challenge-Tracker
```

### **2️⃣ Install Dependencies**  
Run the following command to install required packages:  
```sh
npm install
```

### **3️⃣ Run the Application**  
Start the development server with:  
```sh
ng serve
```
Now, open **[http://localhost:4200](http://localhost:4200)** in your browser.

---

## 📜 Usage Guide  

1️⃣ **Adding a Workout Entry:**  
   - Enter the **User Name**  
   - Select the **Workout Type**  
   - Enter **Workout Minutes**  
   - Click **"Add Workout"**  

2️⃣ **Search for a User:**  
   - Use the search bar to filter by user name  

3️⃣ **Filter by Workout Type:**  
   - Select a workout type from the dropdown filter  

4️⃣ **Pagination:**  
   - The list is paginated if there are more than 5 users  

5️⃣ **View Progress with Charts (Optional Feature):**  
   - Displays total minutes spent on different workout types  

---
🧪 Testing

✅ Run Unit Tests
```sh
ng test
```
📊 View Code Coverage Report
```sh
ng test --code-coverage
```
🔹 The coverage report will be generated inside the /coverage folder.
---

## 📌 Assumptions  

✅ The app starts with **3 default users** to demonstrate functionality.  
✅ **LocalStorage** is used to **persist data** across sessions.  
✅ **Pagination is applied for lists with more than 5 users**.  
✅ **Workout progress visualization (charts) is optional** and can be enabled if needed.  
✅ **Tailwind CSS** is used for styling to maintain a clean and responsive UI.  

---



