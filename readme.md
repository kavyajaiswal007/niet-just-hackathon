HOSTEL ENERGY LEADERBOARD
Gamified Sustainability Dashboard

We’re building a frontend-only hackathon project called “Hostel Energy Leaderboard.”

The basic idea is simple: hostel students usually don’t know how much electricity their room is using, and there isn’t much motivation to save it. We want to turn this into a small competition where students can see their usage, compare themselves with other rooms, maintain eco-streaks, earn badges, and unlock campus rewards.

This is a 30-minute hackathon, so keep the project focused on the frontend. No backend, authentication, database, APIs, or real IoT integration. Use realistic mock data.

TECH STACK

- React + Vite
- Tailwind CSS
- Recharts for graphs
- Lucide React for icons
- Hardcoded/mock data
- Responsive design
- Deployable on Vercel

MAIN EXPERIENCE

The first screen should immediately show the hostel leaderboard.

Students should be able to understand within a few seconds:

- Who is currently #1
- How much electricity they are using
- Where their own room stands
- Who improved this week
- How much energy the hostel community has saved

LEADERBOARD

Create around 50 rooms, such as:

101–105
201–205
301–305
and so on.

For each room, generate:

- Room number
- Student name
- Current daily consumption
- 7-day consumption history
- Current rank
- Previous week's rank
- Eco streak
- Badges
- Unlocked perks

Show the top 10 rooms on the main leaderboard.

Each row should contain:

- Rank
- Room number
- Student name
- Daily kWh
- Weekly average
- Rank movement

Use clear visual indicators:

50–80 kWh → Efficient → green
80–120 kWh → Average → amber
120–150 kWh → High Usage → red

For the top three:

🥇 Gold
🥈 Silver
🥉 Bronze

Also show a large community statistic near the top:

“12,480 kWh saved this week”

The exact number can come from the mock data.

ROOM DETAILS

When someone clicks a room, open a detailed room view.

Show:

- Large room number
- Student name
- Current rank, e.g. “#7 of 50”
- Current daily usage
- Target: 80 kWh
- Progress toward the target
- 7-day consumption graph
- 80 kWh target line
- Eco streak
- Achievements
- Unlocked rewards

Example:

“🔥 12-day eco streak”

The graph should show Monday to Sunday and make it easy to understand whether the room is improving.

GAMIFICATION

The app should feel like a competition, not an electricity monitoring tool.

Include badges such as:

🔥 Fire Badge — 7-day streak
⭐ Star Badge — 14-day streak
🏆 Crown Badge — Top 5
📈 Trending Badge — Biggest improvement
🌱 Seedling Badge — First day below 80 kWh
♻️ Zero-Waste Badge — 3 perfect days

Also show progress toward the next reward.

Example:

“6 more efficient days → Coffee Voucher unlocked”

REWARDS

Use realistic campus rewards:

☕ $5 Coffee Voucher
🧺 $10 Laundry Credits
🅿️ Prime Parking for 1 Week
📚 Extended Library Hours
🎮 Gaming Room Access

The rewards should feel like something a real college could offer.

CHALLENGE FEATURE

Add a “Challenge a Friend” button.

It doesn’t need a backend.

When clicked, simply open a nice modal containing something like:

“I’m currently #7 on the Hostel Energy Leaderboard.
Can you beat my score?”

Include a copy/share button as a visual mockup.

DESIGN

Make the UI look premium and modern.

I want a strong purple visual identity rather than a generic green sustainability dashboard.

Use:

- Deep purple: #6D28D9
- Violet: #8B5CF6
- Lavender: #A78BFA
- Light purple: #EDE9FE
- White
- Dark charcoal
- Green for efficient usage
- Amber for average usage
- Red for high usage

The overall feeling should be:

PURPLE + ENERGY + GAMIFICATION + PREMIUM TECH

Use subtle gradients, glowing purple accents, clean cards, rounded corners, strong typography and lots of breathing space.

Avoid making it look like a normal college project.

It should feel closer to a polished startup product.

Use Inter, Geist or Poppins.

Keep the UI clean. Don't fill every empty space with cards or text.

DASHBOARD STYLE

The main dashboard can have:

1. Community energy saved
2. My room rank
3. My eco streak
4. Next reward progress
5. Top 3 rooms
6. Full leaderboard

The top three rooms should have a slightly larger visual treatment so the competition is obvious.

RESPONSIVE DESIGN

The app must work properly on:

- 375px mobile
- 768px tablet
- 1440px desktop

On mobile, simplify the leaderboard to:

Rank | Room | kWh

Everything else can be viewed inside the room detail page.

Buttons should be easy to tap. Don't rely on hover interactions.

ANIMATIONS

Use animations only where they actually improve the experience.

Good examples:

- Smooth leaderboard movement
- Rank up/down animation
- Progress bar animation
- Badge pop animation
- Subtle pulse on top 3
- Confetti when a badge is unlocked

Don't overdo animations.

MOCK DATA

Generate 50 rooms with realistic-looking data.

Keep the data consistent between refreshes. Don't randomly change the leaderboard every time the page loads.

The top rooms should have genuinely low consumption so the rankings make sense.

Example:

Room 304 — 58 kWh — #1
Room 102 — 63 kWh — #2
Room 407 — 67 kWh — #3

Generate different student names and realistic 7-day usage histories.

Each room should have 2–4 badges and perks based on performance.

IMPORTANT

This is a prototype, so don't waste time building:

- Backend
- Database
- Authentication
- Real-time APIs
- IoT integration
- Admin panels
- Complicated settings

Focus on making the frontend look extremely polished.

The judge should understand the idea immediately.

The story of the product is:

Students don't see their electricity usage
↓
We make usage visible
↓
Rooms compete
↓
Students build eco-streaks
↓
They earn badges
↓
They unlock real campus rewards
↓
The hostel saves energy

The main goal is to make saving electricity feel competitive, visible and rewarding.

PROJECT STRUCTURE

Keep the code simple and organized:

src/
├── components/
│   ├── Leaderboard.jsx
│   ├── RoomDetail.jsx
│   ├── Badge.jsx
│   ├── Chart.jsx
│   └── Navigation.jsx
├── data/
│   └── mockData.js
├── App.jsx
└── index.css

Start with:

npm create vite@latest hostel-energy-leaderboard -- --template react

Then:

cd hostel-energy-leaderboard
npm install

Install whatever small libraries are needed for the charts/icons and run:

npm run dev

FINAL EXPECTATION

I don't want a generic dashboard template.

I want something that looks like a real product a college could actually launch.

The first impression should be:

“Okay, this is an energy-saving competition for hostel students.”

Keep the interface beautiful, fast, simple and fun.
