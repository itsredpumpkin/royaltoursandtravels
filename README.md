# Royal Tours & Travels

A professional travel and tourism website built with modern web technologies.

## 🌍 About
Royal Tours & Travels is a comprehensive tourism booking platform offering curated travel packages, destination guides, and booking management.

## 📁 Project Structure

```
/
├── index.html              # Homepage
├── pages/                  # Additional pages
├── assets/                 # Images, icons, media
├── css/                    # Stylesheets
├── js/                     # JavaScript files
├── config/                 # Configuration files
└── README.md              # This file
```

## 🚀 Getting Started

### Local Development
1. Clone the repository
   ```bash
   git clone https://github.com/itsredpumpkin/royaltoursandtravels.git
   ```

2. Open in your browser
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

3. Navigate to `http://localhost:8000`

## 🌐 Hosting with Hostinger

### Option 1: Upload via FTP (Recommended for Hostinger)
1. Log in to your Hostinger account
2. Go to **File Manager** or use **FTP credentials**
3. Navigate to your domain's public folder (usually `public_html/`)
4. Upload all files and folders from this repository
5. Access your site at `yourdomain.com`

### Option 2: Git Integration (if available on your Hostinger plan)
1. In Hostinger control panel, enable Git deployment
2. Connect this GitHub repository
3. Set deployment branch to `main`
4. Hostinger will auto-deploy on pushes

### Option 3: GitHub Pages (Free Alternative)
- Repository is already configured for GitHub Pages
- Enable in Settings → Pages
- Access at `https://itsredpumpkin.github.io/royaltoursandtravels`

## 🔧 Configuration

### Domain Setup with Hostinger
1. Go to Hostinger → Domain Manager
2. Point your domain to this repository/hosting:
   - **Option A (FTP Upload)**: Upload files to public_html
   - **Option B (Git)**: Enable Git deployment
   - **Option C (GitHub Pages)**: Update nameservers

3. DNS Records (if needed):
   ```
   A Record: 75.75.75.75 (GitHub Pages IP)
   CNAME: yoursubdomain.example.com → itsredpumpkin.github.io
   ```

4. Wait for DNS propagation (24-48 hours)

## 📝 Features

- Responsive design for all devices
- Fast loading performance
- Professional tour packages
- Booking system
- Destination guides
- Customer reviews

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Responsive Design
- Mobile-first approach

## 📧 Contact
For inquiries: [Your contact information]

## 📄 License
This project is private and for personal use.

---

**Status**: Ready for production deployment ✅

**Last Updated**: September 3, 2026
