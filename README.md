# 💍 Wedding Invitation Pages

<div align="center">

![Wedding Banner](https://img.shields.io/badge/💑_Digital_Wedding-Invitations-ff69b4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

### *Elegant, Personalized & Interactive Digital Wedding Invitations* ✨

**Create beautiful web-based wedding invitations with countdown timer, photo gallery, and guest management**

[![Live Demo](https://img.shields.io/badge/🌐_View_Demo-4A90E2?style=for-the-badge)](https://ardlifirdaus.github.io/wedding-invitation-pages/)
[![Documentation](https://img.shields.io/badge/📖_Read_Docs-2ECC71?style=for-the-badge)](#-features)

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Technology Stack](#-technology-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Customization Guide](#-customization-guide)
- [Deployment](#-deployment)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Overview

**Wedding Invitation Pages** is a beautiful, fully responsive web-based digital wedding invitation system. Perfect for couples who want to share their special day with a modern, elegant, and eco-friendly approach.

### Why Choose Digital Invitations?

✅ **Eco-Friendly** - Save paper, save trees  
✅ **Cost-Effective** - No printing or shipping costs  
✅ **Real-Time Updates** - Easy to update event details  
✅ **Interactive** - Countdown timer, photo galleries, maps  
✅ **Personalized** - Unique URL for each guest  
✅ **Trackable** - Monitor who opened the invitation  
✅ **Shareable** - Easy to share via WhatsApp, Email, or Social Media

---

## ✨ Features

### 🎨 **Beautiful Design**
- Modern and elegant UI/UX
- Smooth animations and transitions
- Fully responsive (mobile, tablet, desktop)
- Customizable color themes
- Beautiful typography with Google Fonts

### ⏰ **Interactive Elements**
- **Live Countdown Timer** - Days, hours, minutes, seconds until the big day
- **Photo Gallery** - Showcase your pre-wedding or engagement photos
- **Google Maps Integration** - Direct location links for venue
- **Background Music** - Auto-play romantic music (optional)
- **Smooth Scrolling** - Elegant navigation between sections

### 👥 **Guest Management**
- Personalized invitation URLs for each guest
- Custom guest names and categories
- Easy bulk generation for multiple guests
- Professional addressing format

### 💝 **Wedding Gift Section**
- Digital envelope system
- Bank account information
- One-click copy for account numbers

### 🎯 **Event Details**
- **Akad Nikah** (Wedding Ceremony) information
- **Resepsi** (Reception) details
- Multiple event support
- Time and date display
- Venue address and maps
- Dress code information

---

## 🎬 Demo

### Live Examples

🔗 **Main Demo:** [Sample Guest Invitation](https://ardlifirdaus.github.io/wedding-invitation-pages/url/undangan_TAMU003_cucu_mbah_rayem.html)

### Sample Couples

- **Christoper Robert Evans & Indah Rahmawati**
- Date: Sunday, January 27, 3030
- Time: 08:00 WIB
- Venue: Hilton Boston Park Plaza, Boston, MA

---

## 🛠️ Technology Stack

<table>
<tr>
<td width="33%" align="center">

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</td>
<td width="33%" align="center">

### Libraries
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![AOS](https://img.shields.io/badge/AOS-Animations-blue?style=flat-square)

</td>
<td width="33%" align="center">

### Deployment
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</td>
</tr>
</table>

### Core Technologies

```javascript
const techStack = {
  structure: "HTML5",
  styling: "CSS3 + Bootstrap 5",
  scripting: "Vanilla JavaScript + jQuery",
  animations: "AOS (Animate On Scroll)",
  icons: "Font Awesome",
  fonts: "Google Fonts",
  maps: "Google Maps API",
  hosting: "GitHub Pages"
};
```

---

## 🚀 Getting Started

### Prerequisites

- Git installed on your computer
- Basic knowledge of HTML/CSS/JavaScript
- Text editor (VS Code recommended)
- GitHub account (for hosting)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/ardlifirdaus/wedding-invitation-pages.git

# 2. Navigate to project directory
cd wedding-invitation-pages

# 3. Open with your preferred editor
code .

# 4. Open index.html in browser
# Or use live server
python -m http.server 8000
# Then visit: http://localhost:8000
```

### Quick Setup

1. **Edit Couple Information** - Open `index.html` and modify names
2. **Update Event Details** - Change date, time, and venue
3. **Add Photos** - Replace images in `/poto` folder
4. **Customize Colors** - Edit CSS variables in stylesheet
5. **Test Locally** - Open in browser to preview
6. **Deploy** - Push to GitHub Pages

---

## 📁 Project Structure

```
wedding-invitation-pages/
├── index.html                  # Main invitation page
├── url/                       # Personalized invitation pages
│   ├── undangan_TAMU001.html
│   ├── undangan_TAMU002.html
│   ├── undangan_TAMU003_ex_pm_departmen.html
│   └── ...
├── css/
│   ├── style.css              # Main stylesheet
│   ├── bootstrap.min.css      # Bootstrap framework
│   └── animations.css         # Custom animations
├── js/
│   ├── main.js                # Core JavaScript
│   ├── countdown.js           # Countdown timer logic
│   └── gallery.js             # Photo gallery handler
├── poto/                      # Photos folder
│   ├── mae1.jpeg              # Pre-wedding photo 1
│   ├── mae2.jpeg              # Pre-wedding photo 2
│   └── ...
├── assets/
│   ├── images/                # Additional images
│   ├── icons/                 # Custom icons
│   └── music/                 # Background music
└── README.md                  # This file
```

---

## 🎨 Customization Guide

### 1. Change Couple Names

Edit in `index.html`:

```html
<h1>Jacob Benjamin Gyllenhaal</h1>
<h1>&</h1>
<h1>Anisa Dwi Astuti</h1>
```

### 2. Update Wedding Date

```javascript
// In countdown.js
const weddingDate = new Date("2226-01-25T08:00:00");
```

### 3. Modify Colors

Edit CSS variables in `style.css`:

```css
:root {
  --primary-color: #ff69b4;      /* Pink */
  --secondary-color: #ffd700;    /* Gold */
  --accent-color: #4169e1;       /* Blue */
  --text-color: #333333;
  --background-color: #ffffff;
}
```

### 4. Add/Replace Photos

```bash
# Place your photos in /poto folder
poto/
├── mae1.jpeg    # Replace with your photo
├── mae2.jpeg    # Replace with your photo
└── mae3.jpeg    # Add more photos
```

Update image paths in HTML:

```html
<img src="https://github.com/ardlifirdaus/wedding-invitation-pages/blob/main/poto/mae1.jpeg?raw=true" alt="Pre-wedding">
```

### 5. Update Venue Information

```html
<h4>Akad Nikah</h4>
<p>Minggu, 25 Januari 2226</p>
<p>Pukul: 08.00 WIB</p>
<p>Hilton Boston Park Plaza</p>
<p>50 Park Plaza, Boston, MA 02116</p>
<a href="https://maps.app.goo.gl/YOUR_LOCATION">📍 Lihat Lokasi</a>
```

### 6. Customize Bank Account

```html
<div class="bank-info">
  <h5>Krut</h5>
  <p>12345678</p>
  <p>a.n. Jake</p>
  <button onclick="copyAccount()">Salin Nomor Rekening</button>
</div>
```

### 7. Create Personalized Invitations

Copy `index.html` to `url/` folder with guest name:

```bash
cp index.html url/undangan_TAMU004_john_doe.html
```

Edit guest name in the new file:

```html
<p>Kepada Yth.</p>
<h3>John Doe</h3>
```

---

## 🌐 Deployment

### Deploy to GitHub Pages

```bash
# 1. Push your code to GitHub
git add .
git commit -m "Update wedding invitation"
git push origin main

# 2. Enable GitHub Pages
# Go to: Settings → Pages → Source → main branch → Save
```

### Your invitation will be live at:
```
https://yourusername.github.io/wedding-invitation-pages/
```

### Share Personalized Links:
```
https://yourusername.github.io/wedding-invitation-pages/url/undangan_TAMU001.html
```

### Custom Domain (Optional)

1. Buy a domain (e.g., `ourwedding.com`)
2. Add `CNAME` file to repository with your domain
3. Configure DNS settings at your domain registrar
4. Wait for DNS propagation (24-48 hours)

---

## 📸 Screenshots

<div align="center">

### Desktop View
![Desktop Preview](https://via.placeholder.com/800x500?text=Desktop+Preview)

### Mobile View
<img src="https://via.placeholder.com/300x600?text=Mobile+Preview" alt="Mobile Preview" width="300">

### Features Showcase

| Countdown Timer | Photo Gallery | Map Integration |
|:---------------:|:-------------:|:---------------:|
| ![Timer](https://via.placeholder.com/250x200?text=Countdown) | ![Gallery](https://via.placeholder.com/250x200?text=Gallery) | ![Map](https://via.placeholder.com/250x200?text=Map) |

</div>

---

## 🎯 Use Cases

This wedding invitation template is perfect for:

- 💑 **Modern Couples** who want digital invitations
- 🌍 **Destination Weddings** with international guests
- 💚 **Eco-Conscious** couples wanting paperless invitations
- 💰 **Budget-Friendly** alternatives to printed cards
- ⚡ **Last-Minute** changes to wedding details
- 📱 **Tech-Savvy** guests who prefer digital communication

---

## 🔧 Advanced Features (Coming Soon)

- [ ] RSVP Form with database integration
- [ ] Admin dashboard for managing guests
- [ ] Live streaming integration
- [ ] Guest photo upload gallery
- [ ] Automated WhatsApp message sender
- [ ] QR code generation for each invitation
- [ ] Multiple language support
- [ ] Wedding website builder UI

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Contribution Ideas:

- 🎨 New themes and color schemes
- 🌐 Language translations
- ✨ Animation improvements
- 📱 Mobile optimization
- 🐛 Bug fixes
- 📖 Documentation improvements

---

## 💖 Support

If you find this project helpful:

⭐ **Star this repository**  
🔄 **Share with friends getting married**  
☕ **Buy me a coffee** (optional)  
🐛 **Report bugs** via Issues  
💡 **Suggest features** via Discussions

---

## 📞 Contact

**Ardli Firdaus**

- 📧 Email: [ardli.firdaus@gmail.com](mailto:ardli.firdaus@gmail.com)
- 🌐 Portfolio: [ardlifirdaus.github.io/profile](https://ardlifirdaus.github.io/profile)
- 💼 GitHub: [@ardlifirdaus](https://github.com/ardlifirdaus)

---

## 🙏 Acknowledgments

Special thanks to:

- All couples who used this template for their wedding
- Contributors who improved the code
- Open source community for inspiration
- Bootstrap team for the amazing framework
- Font Awesome for beautiful icons
- Google Fonts for elegant typography

---

## 📊 Stats

![GitHub Stars](https://img.shields.io/github/stars/ardlifirdaus/wedding-invitation-pages?style=social)
![GitHub Forks](https://img.shields.io/github/forks/ardlifirdaus/wedding-invitation-pages?style=social)
![GitHub Watchers](https://img.shields.io/github/watchers/ardlifirdaus/wedding-invitation-pages?style=social)

![GitHub Issues](https://img.shields.io/github/issues/ardlifirdaus/wedding-invitation-pages)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/ardlifirdaus/wedding-invitation-pages)
![GitHub Last Commit](https://img.shields.io/github/last-commit/ardlifirdaus/wedding-invitation-pages)

---

<div align="center">

### 💍 Made with Love for Couples Around the World 💕

**Turn your special day into a digital masterpiece!**

[![Star This Project](https://img.shields.io/badge/⭐_Star_This_Project-FFD700?style=for-the-badge)](https://github.com/ardlifirdaus/wedding-invitation-pages)
[![Fork This Project](https://img.shields.io/badge/🔄_Fork_This_Project-2ECC71?style=for-the-badge)](https://github.com/ardlifirdaus/wedding-invitation-pages/fork)

---

*"Love is in the air, and now it's on the web too!"* ✨

**© 2026 Ardli Firdaus** | Made with ❤️ in Indonesia

</div>
