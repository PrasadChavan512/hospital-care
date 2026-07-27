# CarePlus Multispeciality Hospital Website

A complete, professional, responsive hospital website built with **HTML5**, **CSS3**, and **Vanilla JavaScript** (no frameworks).

## Project Structure

```
careplus-hospital/
├── index.html              # Homepage
├── about.html              # About Us page
├── doctors.html            # Doctors listing with search/filter
├── doctor-details.html     # Individual doctor profile
├── specialities.html       # All specialities listing
├── speciality-details.html # Individual speciality details
├── services.html           # Patient services page
├── facilities.html         # Hospital facilities with lightbox
├── health-packages.html    # Health checkup packages
├── appointment.html        # Online appointment booking
├── contact.html            # Contact form & map
├── css/
│   ├── style.css           # Main stylesheet
│   ├── responsive.css      # Responsive design
│   └── animations.css      # Scroll & hover animations
├── js/
│   ├── main.js             # Core functionality
│   ├── navigation.js       # Header, mobile menu, sticky nav
│   ├── doctors.js          # Doctor data, search, filtering
│   ├── appointment.js      # Appointment form validation
│   └── contact.js          # Contact form validation
├── images/                 # Image assets
└── README.md               # This file
```

## How to Run

1. Open the project folder in VS Code
2. Install Live Server extension
3. Right-click index.html > "Open with Live Server"

## How to Replace Images

Replace placeholder images in the `images/` folder with your own.

## How to Change Hospital Name

Search for "CarePlus" across all HTML files and replace.

## How to Change Phone Numbers

Search for "+91 98765" across all HTML files and replace.

## How to Connect Forms to Backend

Edit `js/appointment.js` and `js/contact.js` - replace the mock success functions with fetch() API calls to your backend endpoint.

---

## Deployment

### Deploy to GitHub

1. Create a new repository on [GitHub](https://github.com/new)
2. Open a terminal in the project folder:
   ```bash
   cd careplus-hospital
   git init
   git add .
   git commit -m "Initial commit - CarePlus Hospital website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

### Deploy to Vercel

#### Option 1: Via Vercel Dashboard (Recommended)
1. Go to [vercel.com](https://vercel.com) and sign in with your GitHub account
2. Click **Add New** → **Project**
3. Import your GitHub repository (`careplus-hospital`)
4. **Framework Preset**: Select `Other` (static site — no build step needed)
5. **Root Directory**: Keep as `./` (or select `careplus-hospital` if you pushed the entire parent folder)
6. Click **Deploy**
7. Done! Vercel will auto-detect the `vercel.json` config

#### Option 2: Via Vercel CLI
```bash
npm install -g vercel
vercel login
cd careplus-hospital
vercel --prod
```

**Note:** The included `vercel.json` sets up caching headers, security headers, and clean URLs automatically.
