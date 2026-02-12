# CleanSweep ♻️

> **A smarter, cleaner future for our cities.**  
> *Report illegal dumping, track waste, and connect with recyclers—all in one app.*

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Contributors](https://img.shields.io/badge/contributors-welcome-orange.svg)

---

## 🌟 Overview

**CleanSweep** is a progressive web application designed to empower citizens to take action against illegal dumping and waste mismanagement. By leveraging real-time geolocation, camera integration, and a community-driven marketplace, CleanSweep bridges the gap between citizens, waste collectors, and municipal authorities.

## ✨ Key Features

- **📸 AI-Powered Reporting**: Instantly capture and report illegal dumping spots. The app automatically tags the location and uploads the evidence.
- **🗺️ Interactive Map**: View reported hotspots and verified clean-up zones on a live, interactive map.
- **🏪 Recycler Marketplace**: Connect with local waste collectors and scrap dealers to sell recyclable materials (paper, plastic, e-waste) directly.
- **🔐 Secure Authentication**: User profiles and reports are securely managed via Supabase.
- **⚡ Modern UI**: A sleek, dark-mode-first interface built with Glassmorphism principles for a premium user experience.

## 🛠️ Tech Stack

- **Frontend**: HTML5, Vanilla JavaScript, Tailwind CSS
- **Backend / Database**: Supabase (PostgreSQL, Auth, Storage)
- **Maps**: Leaflet.js & OpenStreetMap
- **Icons**: Lucide Icons
- **Deployment**: Vercel / Netlify (Static hosting)

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Edge, Firefox, Safari).
- An active internet connection.
- Camera permissions enabled for the app.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/CleanSweep.git
   cd CleanSweep
   ```

2. **Configure Supabase**
   - Create a `supabaseClient.js` file in the root if it doesn't exist.
   - Add your Supabase URL and Anon Key:
     ```javascript
     const supabaseUrl = 'YOUR_SUPABASE_URL';
     const supabaseKey = 'YOUR_SUPABASE_ANON_KEY';
     const supabaseClient = supabase.createClient(supabaseUrl, supabaseKey);
     window.supabaseClient = supabaseClient;
     ```

3. **Run Locally**
   - Simply open `index.html` in your browser.
   - Or use a simple HTTP server:
     ```bash
     npx serve .
     ```

## 📱 Screenshots

| Camera UI | Marketplace |
|:---:|:---:|
| *(Add Screenshot)* | *(Add Screenshot)* |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Built with ❤️ for a cleaner planet.
</p>
