# 🎱 Snooker Diary

A comprehensive web app to track your snooker matches, practice sessions, statistics, and progress. Works perfectly on both mobile and desktop.

![Version](https://img.shields.io/badge/version-1.0.0-green)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## ✨ Features

### 📊 Match Tracking
- Record match scores (frame wins/losses)
- Track high breaks for you and opponents
- Add match details: venue, date, duration, format
- Competition types: Friendly, League, Tournament, Ranking
- Handicap tracking
- Match notes

### 📈 Statistics & Analytics
- **Streaks**: Current win/loss streak, longest win streak
- **Frame Statistics**: Total frames won/lost, frame win percentage
- **Break Distribution**: Visual charts of your break ranges
- **Venue Performance**: See which locations you play best at
- **Competition Analysis**: Performance by match type
- **Automatic Milestones**: Badges for achievements (centuries, streaks, matches played)

### 👥 Opponent Tracking
- Head-to-head records against each opponent
- Frame statistics per opponent
- High break vs each opponent
- Match history with each player

### 🏆 High Breaks
- Ranked list of your top 20 breaks
- Century break counter
- Average break calculation

### 🎯 Practice Sessions
- Log practice sessions with title and date
- Track high breaks during practice
- Record session duration and focus areas
- Practice notes

### 📅 Upcoming Matches
- Schedule matches in advance
- "Unknown Opponent" option for tournaments
- Add venue, time, and notes
- Convert to results when match is played

### 🎨 User Experience
- Dark/Light mode toggle
- Search functionality
- Filter by opponent
- Edit any entry
- Delete with confirmation
- Responsive mobile-first design
- Works offline (PWA)

### 💾 Data Management
- CSV export for backups
- CSV import to restore data
- All data stored locally (privacy-first)

---

## 🚀 Quick Start

### For Users (Install the App)

**On iPhone:**
1. Open the app URL in Safari
2. Tap the Share button (□↑)
3. Scroll and tap "Add to Home Screen"
4. Tap "Add"
5. App appears on your home screen!

**On Android:**
1. Open the app URL in Chrome
2. Tap the menu (⋮)
3. Tap "Add to Home Screen" or "Install App"
4. Tap "Install"
5. App appears on your home screen!

**On Desktop:**
Just bookmark the URL or use it in your browser!

---

## 🛠️ For Developers - Deployment Guide

### Prerequisites
- A text editor
- Git (optional, for GitHub Pages)
- GitHub account (for GitHub Pages) OR
- No account needed (for Netlify Drop)

### Step 1: Get the Code
1. Download or copy the `index.html` file from this repository
2. The file contains the complete React application
3. No build process needed - it's ready to deploy!

### Step 2: Deploy

#### Option A - Netlify Drop (Easiest)
```bash
# No installation needed!
1. Go to: https://app.netlify.com/drop
2. Drag and drop index.html
3. Get instant URL: https://random-name.netlify.app
4. Share with friends!
```

#### Option B - GitHub Pages
```bash
# 1. Create a new repository
# 2. Upload index.html
# 3. Enable GitHub Pages in Settings

# Your app will be at:
https://your-username.github.io/repository-name
```

#### Option C - Vercel
```bash
# 1. Install Vercel CLI (optional)
npm i -g vercel

# 2. Deploy
vercel

# Or use the Vercel web dashboard to upload your file
```

#### Option D - Any Web Host
Simply upload `index.html` to any web hosting service. No server-side code needed!

---

## 📱 Technical Details

### Technology Stack
- **Frontend Framework**: React 18
- **Language**: JavaScript (JSX with Babel)
- **Styling**: Tailwind CSS (CDN)
- **Icons**: Inline SVG (Lucide icons converted)
- **Storage**: Browser localStorage API
- **Deployment**: Static HTML (no build process)

### Browser Support
- ✅ Chrome/Edge (latest 2 versions)
- ✅ Safari (latest 2 versions)
- ✅ Firefox (latest 2 versions)
- ✅ iOS Safari (iOS 12+)
- ✅ Chrome for Android (latest)

### Storage
- All data stored in browser's localStorage
- Typical storage limit: 5-10MB (enough for thousands of matches)
- Data persists across sessions
- Private - never sent to any server

### PWA Features
- Works offline after first load
- Can be installed to home screen
- App-like experience on mobile
- No app store needed

---

## 📖 User Guide

### Adding a Match
1. Tap the green **+** button
2. Select or add an opponent
3. Enter frame scores (e.g., 5-1)
4. Add high breaks (optional)
5. Fill in venue, match type, format (optional)
6. Add notes (optional)
7. Tap **Save**

### Scheduling an Upcoming Match
1. Go to **Upcoming** tab
2. Tap **New**
3. Select opponent (or "Unknown Opponent")
4. Set date and time
5. Add venue and notes
6. When match is played, tap **✓ Add Result**

### Logging Practice
1. Go to **Practice** tab
2. Tap **New**
3. Add title (e.g., "Long potting")
4. Record high break and duration
5. Note focus areas
6. Tap **Save**

### Viewing Statistics
1. Go to **Stats** tab
2. View streaks, milestones, frame stats
3. See break distribution chart
4. Check venue performance
5. Analyze competition type breakdown

### Exporting Data
1. Tap menu (≡) in top right
2. Select **Export CSV**
3. File downloads to your device
4. Save as backup!

### Importing Data
1. Tap menu (≡) in top right
2. Select **Import CSV**
3. Choose your backup file
4. Data will be merged with existing data

---

## 🔒 Privacy & Security

- **100% Local**: All data stored on your device only
- **No Server**: No data sent anywhere
- **No Tracking**: No analytics or tracking scripts
- **No Account**: No login required
- **Your Data**: Export anytime, you own it

---

## 🐛 Troubleshooting

**App not loading?**
- Clear browser cache and reload
- Make sure JavaScript is enabled
- Try a different browser

**Data disappeared?**
- Check if you're using the same browser
- Check if browser data was cleared
- Restore from CSV backup if available

**Can't add to home screen?**
- iOS: Must use Safari browser
- Android: Must use Chrome browser
- Make sure you're using HTTPS URL

**Slow performance?**
- App performs best with under 1000 matches
- Export old data and start fresh if needed
- Close other browser tabs

---

## 🗺️ Roadmap

Future features under consideration:
- [ ] Cloud sync (optional)
- [ ] Statistics graphs/charts
- [ ] Goal setting and tracking
- [ ] Photo attachments
- [ ] Multi-language support
- [ ] Social features (compare with friends)
- [ ] Advanced analytics

---

## 🤝 Contributing

This is an open-source project! Contributions welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

---

## 📄 License

MIT License - Free to use, modify, and distribute!

---

## 💬 Support

Having issues or questions?
- Check the troubleshooting section above
- Open an issue on GitHub
- Review the user guide

---

## 🙏 Acknowledgments

Built with:
- React (Facebook)
- Tailwind CSS
- Lucide Icons
- Love for snooker! 🎱

---

## 📊 Stats

- **Lines of Code**: ~2000
- **Features**: 25+
- **Dependencies**: 0 (all CDN-based)
- **Build Time**: Instant (no build needed!)
- **Load Time**: <2 seconds

---

Made with ❤️ for snooker players worldwide

**Version 1.0.0** | Last Updated: 2025