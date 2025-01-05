# **SyncSoc** 

### **A dynamic platform for managing societies, events, and fests!**  

---

## **📖 About the Project**  

SyncSoc is a **React-based web application** designed to help manage **societies, events, and fests** in a university setting. It provides an **interactive UI**, **user authentication**, and an **event management system** to facilitate collaboration among students and organizers.  

---

## **🚀 Features**  

✔️ **User Authentication** – Login/Signup functionality using Redux.  
✔️ **Role-Based Access Control** – Separate UI for **admins** and **users**.  
✔️ **Society & Event Management** – List, filter, and view societies and events.  
✔️ **Nested Dropdown Navigation** – Material-Tailwind-based optimized menus.  
✔️ **Mobile-Friendly Design** – Fully responsive UI with Tailwind CSS.  
✔️ **Secure API Integration** – Fetch event/society data dynamically.  

---

## **🛠 Tech Stack**  

### **Frontend**  
- **React.js** – Core UI framework  
- **Redux** – State management  
- **React Router** – Client-side navigation  
- **Material Tailwind** – UI components & dropdowns  
- **Tailwind CSS** – Styling framework  

### **Backend (Expected)**  
- **Node.js & Express.js** – REST API (Assumption)  
- **MongoDB / Firebase** – Database (Optional)  

---
## **📜 User Flow**  

Below is a representation of the **user flow** of the application:  

![User Flow](/images/userflow.png)  

---

## **🖼 Screenshots**  

Here are some screenshots of SyncSoc:  

### **🏠 Home Page**  
![Home Page](photos/landing.jpeg)  
### **🏠 All events list Page**  
![Home Page](photos/all_events.jpeg)  
### **🏠 Login page**  
![Home Page](photos/login.png)  
### **🏠 Society Page**  
![Home Page](photos/soc_page.jpeg)  
### **📋 Event details**  
![Societies](photos/event_details.jpeg)  

## More images are available in photos folder you can go and check

## **💻 Installation**  

## **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/mihiirsen/SyncSoc.git
cd SyncSoc
```

### **2️⃣ Install Dependencies**  
```sh
npm install
```

### **3️⃣ Set Up Environment Variables**  
Create a `.env` file in the root directory and add:  
```
REACT_APP_API_URL=http://localhost:3000
```
💡 Replace `http://localhost:3000` with your **backend API URL**.

### **4️⃣ Start the Development Server**  
```sh
npm start
```
The app will be available at **http://localhost:3000**.

---

## **🌍 Usage**  

- **Home Page** – Displays societies & events.  
- **Navigation Bar** – Optimized dropdown menu for societies.  
- **Login / Signup** – Authenticate users.  
- **Admin Panel** (If applicable) – Manage events and users.  

---

## **📂 Folder Structure**  

```
SyncSoc/
│── src/
│   ├── components/       # Reusable React components
│   ├── pages/            # Page-based components (Home, About, etc.)
│   ├── redux/            # Redux store & slices
│   ├── styles/           # Tailwind & custom CSS
│   ├── App.js            # Main component
│   ├── index.js          # Entry point
│── public/               # Static assets (Images, Icons, etc.)
│── .env                  # Environment variables
│── package.json          # Dependencies & scripts
│── README.md             # Documentation
```

---

## **📝 Contributing**  

Contributions are **welcome**! 🚀  

1. **Fork** the repository.  
2. **Create a new branch** (`feature-xyz`).  
3. **Make changes & commit** (`git commit -m "Added new feature"`).  
4. **Push to your fork** (`git push origin feature-xyz`).  
5. **Create a Pull Request**!  
