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
