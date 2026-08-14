COMPLETE HACKATHON PROMPT - HOSTEL ENERGY LEADERBOARD

Project Name: Hostel Energy Leaderboard - Gamified Sustainability Dashboard

Time Constraint: 30-minute hackathon - focus on frontend only, zero backend

Problem Statement:
Hostel students waste significant electricity because they have no visibility or incentive to conserve. A competitive, gamified leaderboard with public rankings and tangible rewards can drive behavioral change through social competition and achievement unlocking.

Solution Overview:
Build an interactive, mobile-first dashboard that displays a real-time energy leaderboard for hostel rooms, ranks students by electricity efficiency, awards badges/achievements, and unlocks perks for top performers. Make it visually striking, fast, and instantly understandable.

Tech Stack (Required):

React with Vite or Next.js
Tailwind CSS for styling (must look polished)
Recharts or Chart.js for energy consumption graphs
Mock/hardcoded data only (no backend API)
Responsive design (mobile-first approach)

Mock Data Structure:

50 hostel rooms (Room 101-105, 201-205, etc.)
Each room has:
Current daily kWh consumption (random between 50-150 kWh)
Last 7 days consumption history (for graphs)
Current rank (1-50)
Last week rank (to show movement)
Eco-streak counter (consecutive days below 80 kWh)
Unlocked perks list
Achievement badges earned
Student name (generate random names)

MUST BUILD - Core Features:

1. Leaderboard View (Main Page)
Display top 10 rooms ranked by energy efficiency (lowest consumption = highest rank)
Show for each room: Rank position, Room number, Student name, Daily kWh usage, Weekly average
Visual rank badges: Gold medal icon for #1, Silver for #2, Bronze for #3
Color-coded usage indicators:
Green (50-80 kWh) = "Efficient"
Yellow (80-120 kWh) = "Average"
Red (120-150 kWh) = "High Usage"
Clickable rows - click any room to see detailed view
Smooth sorting animations when ranks update
Total campus energy savings counter at the top (sum of all rooms' weekly savings vs baseline 120 kWh/room)
2. Individual Room Detail View

Shown when user clicks a room from leaderboard:

Large room card with room number prominently displayed
Student name and current rank (e.g., "Rank #7 of 50")
Current daily consumption vs. target (target = 80 kWh, show as progress bar)
7-day consumption line graph (x-axis: Mon-Sun, y-axis: kWh, target line at 80)
Eco-streak counter: "🔥 12 consecutive days under 80 kWh"
Achievement badges grid (see badge list below)
Unlocked perks section with icons:
☕ Coffee voucher ($5)
🅿️ Prime parking spot (1 week)
🧺 Laundry credits ($10)
📚 Library access (extended hours)
🎮 Gaming room access
"Challenge a Friend" button (mockup - shows modal with shareable message)
Back button to return to leaderboard
3. Gamification Elements
Progress Bar: Shows progress to "next perk unlock" (e.g., 6 more efficient days to unlock next perk)
Achievement Badges: Users earn badges for:
7-day streak (🔥 Fire Badge)
14-day streak (⭐ Star Badge)
Top 5 ranking (🏆 Crown Badge)
Biggest weekly improvement (📈 Trending Badge)
First day under 80 kWh (🌱 Seedling Badge)
3 days of zero-waste (perfect score)
Celebration Animations: When achievement unlocks, show confetti effect or badge pop animation
Leaderboard Movement Indicator: Show ↑ or ↓ arrows next to rank if position changed from last week
Global Counter: Display total community kWh saved this week
4. Responsive Mobile Design
Mobile layout: Stack everything vertically, leaderboard card shows only Rank, Room #, kWh
Touch-friendly: Large tap targets (min 44px), no hover-only interactions
Fast load: Optimize animations, lazy-load images
Viewport: Test at 375px (iPhone SE), 768px (tablet), 1440px (desktop)
Navigation: Simple tab or drawer for switching between Leaderboard and My Room views
5. Visual Design Requirements
Color Scheme:
Primary (action/rank): Electric blue (
#2563EB) or vibrant green (
#10B981)
Success/efficient: Green (
#22C55E)
Warning/high usage: Amber (
#F59E0B)
Danger: Red (
#EF4444)
Neutral/background: Light gray (
#F3F4F6) or dark (
#1F2937)
Typography: Use bold sans-serif for headers (Poppins, Inter, or Geist), readable body text (14-16px)
Card Design: Rounded corners (8-12px), subtle shadows, good spacing (16-24px padding)
Animations: Smooth transitions (300-400ms), avoid jank, use CSS animations or Framer Motion
Icons: Use simple, recognizable icons (Lucide React or Heroicons)

Design Tone:

Energetic and playful (not corporate or dull)
Encouraging and positive (celebrate efficiency, not shame waste)
Modern and clean (no clutter, breathing room)
Gamified but authentic (badges and perks feel real, not gimmicky)

NICE-TO-HAVE (If Time Permits):

Dark mode toggle (with localStorage to persist)
Filter/sort leaderboard by floor or building
"Share your rank" button (shows mockup social media post)
Energy-saving tips carousel (rotating tips like "Unplug devices," "Use LED bulbs")
Animated ranking transitions (smooth bar chart animation when ranks update)
Confetti or celebratory effects when badges unlock
Pulse animation on top 3 ranked rooms
"My room history" chart showing 30-day trend

Data to Generate (Hardcoded):

Generate 50 rooms with:
- Room IDs: 101-105 (floor 1), 201-205 (floor 2), 301-305 (floor 3), etc.
- Student names: Random realistic names (15-20 variations, repeat as needed)
- Daily kWh: Random 50-150 (use Math.random() * 100 + 50)
- 7-day history: Array of 7 random values in same range
- Eco-streak: Random 0-21 days
- Achievements: Randomly unlock 2-4 badges per room
- Perks: Based on rank (top 5 get more perks)

Success Metrics for Judging:
✅ App loads instantly and feels fast
✅ Leaderboard is immediately understandable (you instantly know who's winning and why)
✅ Mobile experience is smooth, no lag, no layout breaks
✅ Visual design is polished and looks professional (not a template)
✅ Gamification elements feel motivating (badges, perks, streaks feel rewarding)
✅ Animations are smooth and purposeful (not distracting)
✅ The sustainability angle is genuine (solves real problem, not forced)

Real-World Problem (Why This Matters):
According to Stanford Energy Research, gamified leaderboards reduce dorm energy consumption by 15-20%. Your app makes energy conservation competitive and rewarding for hostel students, addressing a genuine sustainability gap on campuses. Unlike guilt-based conservation campaigns, this uses social proof and achievement unlocking—proven motivators for behavior change.

Deployment Hint:

Host on Vercel (Next.js) or Netlify (React) for instant deploy
No environment variables needed (all mock data)
Should go live in 2 minutes

Judging Talking Points:

"This solves real hostel energy waste through proven psychological triggers: competition, achievement, and reward."
"The frontend is polished and mobile-optimized because students check ranks between classes."
"Mock data allows us to focus on UX instead of wasting time on backend setup."
"Genuinely unique angle: not another energy tracker, but a competitive social game."
"Perks are realistic—actual campus benefits that dorms could actually offer."

DO's:

✅ Focus 90% of effort on frontend beauty and smooth interactions
✅ Use mock data liberally—don't waste time on APIs
✅ Make animations smooth and purposeful
✅ Test on mobile early and often
✅ Polish the visual design (this wins hackathons)
✅ Make the leaderboard feel alive (smooth updates, celebration effects)

DON'Ts:

❌ Don't build a backend or API
❌ Don't use outdated UI libraries (no Bootstrap 4)
❌ Don't add features not listed above
❌ Don't ignore mobile responsiveness
❌ Don't make it look generic or templated
❌ Don't waste time on loading states for data (use instant mock data)

File Structure (Recommended):

hostel-energy-leaderboard/
├── src/
│   ├── components/
│   │   ├── Leaderboard.jsx
│   │   ├── RoomDetail.jsx
│   │   ├── Badge.jsx
│   │   ├── Chart.jsx
│   │   └── Navigation.jsx
│   ├── data/
│   │   └── mockData.js (all 50 rooms with data)
│   ├── App.jsx
│   └── index.css (Tailwind setup)
├── package.json
└── vite.config.js

Start Command:

npm create vite@latest hostel-energy-leaderboard -- --template react
cd hostel-energy-leaderboard
npm install
npm run dev

Copy this entire prompt and paste it directly into OpenPort. It's detailed, actionable, and focused. Good luck with your hackathon! 🚀




Claude is AI and can make mistakes. Please double-check responses.
