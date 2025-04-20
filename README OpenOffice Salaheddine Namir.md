# 📄 README OpenOffice

**Product Title:** OpenOffice.org 2.4  
**Release Date:** 2008  
**Version:** 2.4  
**Maintained By:** OpenOffice.org Community  
**Website:** [www.openoffice.org](http://www.openoffice.org)

---

## 🧭 Introduction

Welcome to OpenOffice.org 2.4!  
This document contains essential information about the software, system requirements, known issues, and ways to participate in the OpenOffice.org project.

🔗 For the latest version of this readme file, visit:  
[http://www.openoffice.org/welcome/readme.html](http://www.openoffice.org/welcome/readme.html)

📘 New users are encouraged to start here:  
[Introduction to OpenOffice.org](http://www.openoffice.org/about_us/introduction.html)

---

## 🆓 Licensing and Freedom to Use

OpenOffice.org is **free to use** by anyone—individuals, businesses, government agencies, and educational institutions.

📜 Full license text: [www.openoffice.org/license.html](http://www.openoffice.org/license.html)

---

## 💻 System Requirements

**Supported Operating Systems:**

- Windows 98, ME, NT (SP6+), 2000, XP
    

**Minimum Hardware:**

- Pentium-compatible PC
    
- 64 MB RAM
    
- 250 MB free disk space (300 MB for CJK versions)
    
- 800x600 screen resolution, 256 colors
    
- 500 MB required post-installation for temp file cleanup
    

**Note:** Administrator rights are required to install OpenOffice.org.

---

## ⚠️ Known Issues and Troubleshooting

### Program Startup Issues

- Problems like application hang or display errors often stem from outdated **graphics card drivers**.
    
- If 3D rendering fails, disable OpenGL:  
    `Tools → Options → OpenOffice.org → View → 3D View`
    

### Java on Windows 98

- If installing Java during setup, the installer may prompt a reboot.  
    ➜ Ignore the message or rerun the installer after reboot.
    

### Clipboard Compatibility

- Copy-paste between OpenOffice.org 1.x and 2.4 may fail.  
    ➜ Use `Edit → Paste Special` and select a different format.
    

### Email Integration

- Sending documents via email (e.g. PDF attachments) might crash due to **MAPI** issues.  
    ➜ Visit Microsoft KB and search “mapi dll” for fixes.
    

### Touchpad Scrolling

- **ALPS/Synaptics users (Windows):** scrolling may not work.  
    ➜ Add the following to `SynTPEnh.ini` and restart:
    

ini

CopierModifier

`[OpenOffice.org] FC = "SALFRAME" SF = 0x10000000 SF |= 0x00004000`

### ZoomText Compatibility

- **Ai Squared ZoomText 7.11 or later** is required.  
    Only versions released **after June 12, 2002** are supported.
    

---

## ⌨️ Keyboard Shortcuts

- Conflicts may occur if shortcuts overlap with those used by your OS.  
    ➜ Adjust system or OpenOffice.org shortcuts as needed.  
    📖 More info available in OpenOffice.org Help or your OS documentation.
    

---

## 📤 Registration & User Survey

**Registration (Optional but Recommended):**

- Helps improve software and user support.
    
- Privacy is strictly respected.
    
- Register at: [www.openoffice.org/welcome/registration-site.html](http://www.openoffice.org/welcome/registration-site.html)
    

**User Survey:**

- Contribute feedback to shape future development.
    
- Participation is anonymous and protected under our privacy policy.
    

---

## 🆘 Support Resources

- 📧 Mailing List: `users@openoffice.org`  
    ➜ [Mailing List Info](http://www.openoffice.org/mail_list.html)
    
- 💬 Community Discussions & Archives
    
- 📚 FAQ: [http://user-faq.openoffice.org](http://user-faq.openoffice.org)
    

---

## 🐞 Bug Reporting

Found a bug? Help improve OpenOffice.org:  
📍 Report issues via our tracker: **IssueZilla**  
➜ [http://www.openoffice.org](http://www.openoffice.org)

---

## 🤝 Get Involved

You’re already contributing by using OpenOffice.org.  
Here’s how to dive deeper:

### ✅ First Steps

- Subscribe to a mailing list
    
- Explore the archives
    
- Send a self-introduction
    

👀 To-Do list for contributors:  
[http://development.openoffice.org/todo.html](http://development.openoffice.org/todo.html)

### 📬 Mailing Lists

Subscribe at: [www.openoffice.org/mail_list.html](http://www.openoffice.org/mail_list.html)

- Announcements: `announce@openoffice.org` (low traffic)
    
- General User Discussion: `discuss@openoffice.org` (high traffic)
    
- Marketing: `dev@marketing.openoffice.org`
    
- Development: `dev@openoffice.org`
    

### 🌍 Join a Project

Not a developer? No problem!

- 📚 Documentation
    
- 🌐 Localization
    
- 🗣️ Marketing (including cross-cultural efforts)
    

Help promote OpenOffice.org in your community:  
[Marketing Contact Network](http://marketing.openoffice.org/contacts.html)

---

## 🧩 Included/Modified Source Code

- Portions © 1998–1999 James Clark
    
- Portions © 1996, 1998 Netscape Communications Corporation
    

---

**We hope you enjoy using OpenOffice.org 2.4 and look forward to meeting you in the community.**  
— _The OpenOffice.org Community_