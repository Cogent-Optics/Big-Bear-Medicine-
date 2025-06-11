# 🐻 Big Bear Medicine Gathering - Sacred Circle Scheduler

A lunar-aligned scheduling system for our sacred men's circle gatherings in the Santa Cruz Mountains.

## Project Purpose

Bear Medicine Circle is a sacred brotherhood meeting monthly with each new moon for deep spiritual growth and authentic masculine transformation. This scheduler helps us:

- **Track New Moon Cycles**: Automatically calculates new moon dates with 5-day gathering windows
- **Coordinate Sacred Gatherings**: Members confirm attendance, select preferred dates
- **Assign Sacred Roles**: Host and circle leader assignments with randomization options
- **Share Circle Wisdom**: Meeting themes, locations, and spiritual focus areas
- **Honor the Rhythm**: Align our gatherings with natural lunar cycles

The app serves warriors of the heart ready for profound inner work through archetypal wisdom, shadow integration, and sacred masculine practices.

## How Circle Members Access the App

### 🌐 **Live Access**
Visit: [Your deployed URL will go here]

### 📱 **Mobile-Friendly**
- Works on phones, tablets, and computers
- Responsive design adapts to any screen size
- Save to home screen for app-like experience

### 🔄 **Real-Time Updates**
- All circle members see the same schedule
- Attendance updates sync instantly across devices
- No accounts needed - simple name-based access

### 🌙 **How to Use**
1. **Enter Your Name** when prompted (first time only)
2. **Select Your Availability** for each moon gathering window
3. **View Meeting Details** including host, leader, location, and theme
4. **Access Anytime** - your preferences are saved automatically

## Technical Details for Future Maintenance

### 🛠️ **Technology Stack**
- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Database**: Firebase Firestore (real-time NoSQL)
- **Hosting**: Firebase Hosting or GitHub Pages
- **Authentication**: Simple name-based identification

### 📂 **Project Structure**
```
big-bear-medicine-gathering/
├── index.html              # Main application file
├── firebase-config.js      # Firebase configuration
├── README.md              # This file
├── .gitignore            # Git ignore rules
└── deployment-notes.md   # Deployment instructions
```

### 🔧 **Key Functions**
- `getNewMoonDates(year)` - Calculates accurate lunar cycles
- `generateSchedule()` - Creates moon gathering cards
- `updateAttendance()` - Syncs member availability to Firebase
- `randomizeRoles()` - Assigns sacred roles with confirmation
- `exportSchedule()` - Downloads complete gathering plan

### 🚀 **Deployment**
Currently deployed on [Platform Name] at [URL]

### 🔄 **Updates & Maintenance**
- **Moon Calculations**: Accurate through 2030, may need updates for future years
- **Firebase Rules**: Check security rules annually
- **Browser Compatibility**: Tested on Chrome, Safari, Firefox, Edge
- **Mobile Testing**: Verified on iOS Safari and Android Chrome

### 🆘 **Troubleshooting**
- **Data Not Syncing**: Check Firebase connection and browser console
- **Missing Members**: Verify Firebase security rules allow read/write
- **Mobile Issues**: Clear browser cache and reload
- **Attendance Not Updating**: Check internet connection and refresh page

### 🔐 **Security Notes**
- No sensitive personal data stored
- Firebase rules restrict access to invited circle members only
- Meeting locations and themes visible only to authenticated users
- No payment or financial information collected

### 📞 **Support**
For technical issues or questions about the sacred circle, contact [Your Contact Info]

---

*"The bear teaches us that true strength comes from going within, that healing happens in sacred solitude, and that the greatest warriors are those who protect with fierce love."*
