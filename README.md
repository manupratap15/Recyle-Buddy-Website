# ♻️ Recycle Buddy Web Portal

A web-based dashboard designed for waste management facilities to efficiently handle user-submitted waste reports, schedule pickups, and oversee operations. This portal complements the Recycle Buddy mobile app developed during GRU Fest 2025.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

---

## 📝 Overview

The Recycle Buddy Web Portal serves as the administrative interface for waste management personnel. Built with HTML and CSS, it provides tools to:

- Authenticate and manage facility staff access.
- Visualize reported waste locations on an interactive map.
- Schedule and monitor waste pickups.
- Maintain facility profiles and operational data.

This portal is part of a larger ecosystem, including a React-based mobile application for users to report waste and request pickups.

---

## 🚀 Features

- **User Authentication**: Secure login system for facility staff.
- **Interactive Map View**: Display and manage reported waste locations.
- **Pickup Scheduling**: Create, view, and manage pickup schedules.
- **Pickup Tracking**: Monitor the status of scheduled pickups.
- **Facility Profile Management**: Update and maintain facility information.

---

## 📁 Project Structure

```plaintext
Recyle-Buddy-Website/
├── index.html                 # Landing page
├── login.html                 # Staff login interface
├── map-view.html              # Map displaying reported waste
├── schedule-pickup.html       # Form to schedule new pickups
├── my-scheduled-pickups.html  # List of scheduled pickups
├── track-pickup.html          # Track pickup statuses
├── facility-profile.html      # Facility information management
├── styles.css                 # Styling for the portal
└── README.md                  # Project documentation
```

---

## 🛠️ Installation

To set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/manupratap15/Recyle-Buddy-Website.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Recyle-Buddy-Website
   ```

3. **Open `index.html` in your preferred web browser**.

*Note*: As this is a static HTML/CSS project, no additional dependencies or servers are required.

---

## 📖 Usage

Upon opening the portal:

1. **Login**: Access the portal via `login.html` using authorized credentials.
2. **Dashboard**: Navigate through the dashboard to view maps, schedule pickups, and manage facility data.
3. **Map Interaction**: Use `map-view.html` to visualize and interact with reported waste locations.
4. **Scheduling**: Create new pickup schedules through `schedule-pickup.html` and monitor them via `my-scheduled-pickups.html`.
5. **Tracking**: Track the status of pickups in real-time using `track-pickup.html`.
6. **Profile Management**: Update facility information through `facility-profile.html`.

---

## 🎨 Customization

To tailor the portal to specific needs:

- **Styling**: Modify `styles.css` to change the visual appearance.
- **Content**: Edit the HTML files to update text, images, or layout.
- **Functionality**: Integrate JavaScript or backend services to add dynamic features or connect to databases.

---

## 🚀 Deployment

Since the project comprises static files, it can be deployed on various platforms:

- **GitHub Pages**: Host directly from the GitHub repository.
- **Netlify**: Drag and drop the project folder or connect the repository for continuous deployment.
- **Vercel**: Import the project for seamless deployment.

*Ensure that all relative paths are correctly set for the chosen hosting platform.*

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/YourFeature
   ```

3. **Commit your changes**:
   ```bash
   git commit -m "Add YourFeature"
   ```

4. **Push to the branch**:
   ```bash
   git push origin feature/YourFeature
   ```

5. **Open a Pull Request**.

Please ensure your code adheres to the project's coding standards and includes appropriate documentation.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
