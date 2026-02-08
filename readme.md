# Mpuza Job Portal - Home Page UI Recreation

This project is a pixel-perfect recreation of the Mpuza job portal home page using HTML and CSS only.

## 📁 Project Structure

```
mpuza-job-portal/
├── index.html              # Main HTML file
├── css/
│   ├── main.css           # Global styles and layout
│   ├── header.css         # Navigation bar styles
│   ├── sidebar.css        # Left sidebar (profile & company)
│   ├── feed.css           # Main feed and job cards
│   └── job-detail.css     # Right sidebar (job details)
└── README.md
```

## 🎨 Features Implemented

### Header Navigation
- Mpuza branding logo
- Navigation items: My Network, Courses, Notifications, Job Alerts
- Search bar
- User profile menu
- "Become Refresher" button
- More menu

### Left Sidebar
- **Profile Card**
  - Cover photo
  - Profile picture
  - User statistics (profile viewers, applications, interviews, saved offers)
  
- **Company Page Info**
  - Airtel company showcase
  - Page statistics
  - Create company page option
  
- **Professional Group**
  - Create new group option

### Main Feed
- **Post Creation Box**
  - "I have a Job, I can post to support Jobless!" input
  - Followers selector
  - Post options (image, price)
  - Jobless counter
  
- **Home Section**
  - Three job cards:
    - Airtel Rwanda - Network & System Administrator
    - Twapela - Machine Learning Engineer
    - Mpuza, Inc. - Legal Officer
  - Each with "Urgent Hiring!" button
  
- **Company Posts**
  - Job position details
  - Countdown timers (Days, Hours, Minutes)
  - Engagement buttons (Like, Comment, Share, Favourite)
  - One Acre Fund featured post

### Right Sidebar
- **Favourited Jobs Widget**
  - Purple gradient background
  - Star icon
  - Instructional text
  - Featured image
  
- **Job Detail Card**
  - Airtel Rwanda job listing
  - Full job description sections:
    - Job Description
    - Number of Positions
    - Direct Supervisor
    - Duties and Responsibilities
    - Qualifications
    - Experience
    - Certificate
  - Countdown timer with star icon
  - Close button

## 🎯 Design Highlights

- **Color Scheme:**
  - Primary Red: `#f55145`
  - Blue Accent: `#0073b1`, `#4fc3f7`
  - Purple Gradient: `#667eea` to `#764ba2`
  - Background: `#f3f6f9`

- **Typography:**
  - System fonts for optimal performance
  - Responsive font sizing
  - Proper hierarchy

- **Layout:**
  - Three-column grid layout
  - Sticky positioning for sidebars
  - Responsive design for mobile devices

- **Components:**
  - Rounded corners (4px, 8px, 20px)
  - Subtle shadows for depth
  - Hover effects on interactive elements
  - Verified badges with checkmarks
  - Time countdown displays

## 🚀 Setup Instructions

1. **Clone or Download the Repository**
   ```bash
   git clone [repository-url]
   cd mpuza-job-portal
   ```

2. **Open in Browser**
   - Simply open `index.html` in any modern web browser
   - No build process or server required

3. **Customize (Optional)**
   - Edit CSS files in the `css/` folder to modify styles
   - Replace placeholder images with actual assets
   - Update content in `index.html`

## 📱 Responsive Design

The layout is responsive and adapts to different screen sizes:
- **Desktop (>1200px):** Full three-column layout
- **Tablet (992px-1200px):** Slightly narrower columns
- **Mobile (<992px):** Single column, sidebars hidden

## 🎨 CSS Organization

Each CSS file handles a specific section:

1. **main.css** - Global resets, container grid, card styles, typography
2. **header.css** - Top navigation bar and all header elements
3. **sidebar.css** - Left sidebar profile and company sections
4. **feed.css** - Main content area with posts and job cards
5. **job-detail.css** - Right sidebar with job details and favorites

## 🌟 Key CSS Techniques Used

- CSS Grid for main layout
- Flexbox for component alignment
- Position sticky for sidebar behavior
- CSS variables could be added for theme customization
- Hover states for interactive feedback
- Media queries for responsiveness
- Custom scrollbar styling

## 📝 Notes

- Font Awesome icons are loaded from CDN for all icons
- Placeholder images use UI Avatars and Unsplash for demonstration
- All measurements approximate the original mockup
- Lorem ipsum text used for content placeholders
- No JavaScript required - pure HTML/CSS implementation

## 🔧 Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## 📄 Assignment Details

- **Objective:** Translate UI/UX mockup into HTML/CSS code
- **Focus:** Structure, layout, spacing, typography, visual accuracy
- **No Functionality Required:** Static HTML/CSS only
- **Deadline:** 05/02/2026 02:00 PM

## 👨‍💻 Development

This project demonstrates:
- Semantic HTML structure
- Modular CSS organization
- Attention to visual detail
- Responsive design principles
- Clean, maintainable code

---

**Created as part of UI/UX to Code assignment**