# 🗣️ Public Speaking Club Website

Welcome to the official website for the **Public Speaking Club** at **Bunker Hill Community College (BHCC)**!  
This site serves as a hub for club information, announcements, leadership details, event schedules, and membership.

---

## 🌐 Live Demo

View the live site here:  
👉 https://pscbhcc.github.io/Public-speaking-club/

N:B: For good view use a desktop 🖥 not a phone 📱 

---

## 📁 Project Structure

public-speaking-club/
|--
\ index.html # Main HTML file
\ README.md # This documentation file
\ image/ # Folder containing all images (logo, member photos, announcements)
\ PSC LOGO.jpg
\ homepage.jpg
\ Lee_An_Reth.jpg
\ ... (other images)


> 💡 **Note**: All assets are self-contained in a single HTML file with embedded CSS and JavaScript — no external dependencies.

---

## ✨ Features

- **Responsive Design**: Works beautifully on mobile, tablet, and desktop.
- **Interactive Calendar**: Displays Fall 2025 meeting schedule with clickable event details.
- **Modal System**:
  - Join form for new members
  - Contact form for the leadership committee
  - Member bio modals (click any leader to learn more)
  - Event detail popups
- **Accessibility**:
  - Semantic HTML
  - Keyboard navigation support
  - ARIA labels for screen readers
  - Focus management in modals
- **Modern UI**:
  - Bold red theme (`#FF2D2D`) representing energy and confidence
  - Clean typography and spacing
  - Hover and focus states for interactivity

---

## 🛠️ How to Use

### To View Locally:
1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. No server or build tools needed — it runs directly from your file system!

### To Customize:
- **Update content**: Edit text directly in `index.html`.
- **Change emails**: Search for `psc.bhcc@gmail.com` and update as needed.
- **Add new announcements**: Duplicate an `.announcement-item` block.
- **Update team bios**: Modify the `committeeMembers` object in the `<script>` section.

> 🔒 **Security Note**: The contact and join forms currently show an `alert()` on submit. For production, connect them to a backend (e.g., Formspree, Google Forms, or a custom API).

---

 ## 🧑‍💻 Built By

Ronewa Masindi with the help of Nhan Lien, Julie Dorchhuon, and Arturo Li.  
— Public Speaking Club Website Committee, BHCC Fall 2025

Special thanks to the club leadership and members for their support!

## 📄 License

&copy; 2025 Public Speaking Club, BHCC. All rights reserved.



