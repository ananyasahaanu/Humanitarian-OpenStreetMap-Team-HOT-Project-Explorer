
# 🗺️ Humanitarian OpenStreetMap Team (HOT) Project Explorer

## 🌐 Website

[https://ananyasahaanu.github.io/Humanitarian-OpenStreetMap-Team-HOT-Project-Explorer/](https://ananyasahaanu.github.io/Humanitarian-OpenStreetMap-Team-HOT-Project-Explorer/)

---

## 📘 Project Overview

The **HOT Project Explorer** is a dynamic, user-friendly web application designed to showcase and interact with humanitarian mapping projects. Users must **sign up and log in** to access the dashboard, ensuring a protected experience. Built with modern web technologies, it offers a visually appealing interface reminiscent of Apple’s design aesthetics, ensuring an engaging user experience.

---

## 🧩 Features

* **Protected Access**: Users must sign up and log in to see the content.
* **Responsive Design**: Optimized for desktop and mobile devices.
* **Interactive Dashboard**: Shows total explorers, projects completed, and milestones.
* **See More Buttons**: Navigate to detailed pages for Explorers, Projects, and Milestones.
* **Animated Counters**: Dynamic counting for statistics.
* **Confetti Animation**: Celebratory effect for user engagement.
* **Floating Circles Animation**: Smooth moving background circles for aesthetic effect.
* **Interactive Map**: Leaflet world map showing humanitarian mapping locations.
* **Sign Out Functionality**: Clear session and redirect to login page.

---

## 🛠️ Technologies Used

* **HTML5**: Structuring content
* **CSS3**: Styling and animations
* **JavaScript**: Interactivity, localStorage, animations, map
* **Leaflet.js**: Interactive world map
* **GitHub Pages**: Hosting

---

## 📁 Project Structure

```
/Humanitarian-OpenStreetMap-Team-HOT-Project-Explorer
│
├── index.html         # Login / Signup page
├── welcome.html       # Main dashboard with cards, animations, and map
├── explorers.html     # Detailed explorers info
├── projects.html      # Detailed projects info
├── milestones.html    # Detailed milestones info
├── styles.css         # CSS file (if separated)
├── script.js          # JavaScript file (if separated)
├── README.md          # Project documentation
└── LICENSE            # MIT License
```

---

## 🚀 Getting Started

1. **Clone the Repository**:

```bash
git clone https://github.com/ananyasahaanu/Humanitarian-OpenStreetMap-Team-HOT-Project-Explorer.git
cd Humanitarian-OpenStreetMap-Team-HOT-Project-Explorer
```

2. **Open `index.html`** in your preferred browser.
3. **Sign Up** with a username and password.
4. **Log In** to access the dashboard and explore content.

---

## 🔐 User Authentication

* **Sign Up / Login**: Users must create an account to access content.
* **LocalStorage**: Stores username and password (basic implementation).
* **Sign Out**: Button clears session and redirects to login page.

> ⚠️ Note: For production, a secure authentication backend is recommended.

---

## 🧭 Purpose & Inspiration

This project aims to:

* **Educate** users about humanitarian mapping.
* **Showcase** HOT’s projects and impact worldwide.
* **Encourage Participation** in humanitarian mapping initiatives.

The application combines learning, interactivity, and visual appeal to engage users with open mapping projects.

---

## 📌 Future Enhancements

* **Markers on Map**: Show explorers, projects, and milestones with popups.
* **API Integration**: Fetch live data for projects and explorers.
* **User Profiles**: Track contributions.
* **Multilingual Support**: Expand global accessibility.
* **Animations & Celebrations**: More interactive effects.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 📑 Lab Report (Summary)

**Project Title**: Humanitarian OpenStreetMap Team Project Explorer
**Date**: 2025
**Objective**: To design an interactive web application showcasing HOT’s humanitarian mapping projects with authentication, statistics, animations, and maps.

**Procedure**:

1. Designed a **login/signup page** with username & password authentication.
2. Implemented a **protected dashboard** (`welcome.html`) accessible only after login.
3. Created **cards** showing explorers, projects, and milestones with animated counters.
4. Added **“See More” buttons** to navigate to detailed pages.
5. Integrated **Leaflet.js world map** with interactive zoom & pan.
6. Applied **animations**: moving circles, confetti, hover effects for cards/buttons.
7. Added **sign-out button** to clear session and redirect to login.

**Observations**:

* Login/signup mechanism works and protects content.
* Animated counters improve user engagement.
* Map visualization enhances global awareness of HOT projects.
* Confetti and floating animations add fun aesthetic appeal.

**Conclusion**:
The HOT Project Explorer demonstrates a secure, interactive, and visually appealing platform for exploring humanitarian mapping projects, providing educational value and encouraging participation.

---

