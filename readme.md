HOSTEL ENERGY LEADERBOARD
Gamified Sustainability Dashboard

We are building a 30-minute frontend hackathon prototype called “Hostel Energy Leaderboard.”

The goal is not just to make a beautiful dashboard. The product should clearly solve a real hostel problem and demonstrate enough functionality that judges can immediately see its usefulness, innovation, technical execution and potential real-world impact.

CORE IDEA

Hostel students often waste electricity because they cannot easily see how much energy they are consuming and there is little immediate incentive to reduce it.

Our solution turns electricity conservation into a friendly competition.

Students can:

SEE their electricity consumption
→ COMPARE their room with others
→ CLIMB the leaderboard
→ BUILD eco-streaks
→ EARN achievements
→ UNLOCK campus rewards

The product should feel like a real campus sustainability platform, not a static college project.

==================================================
JUDGING / RUBRIC PRIORITY
==================================================

Optimize the entire application around these judging factors:

1. PROBLEM UNDERSTANDING
2. SOLUTION RELEVANCE
3. INNOVATION
4. FUNCTIONALITY
5. UI/UX QUALITY
6. TECHNICAL IMPLEMENTATION
7. SUSTAINABILITY / REAL-WORLD IMPACT
8. SCALABILITY
9. PRESENTATION / DEMO EXPERIENCE

Every major feature should support at least one of these points.

Do not add random features just to make the application larger.

==================================================
1. PROBLEM → SOLUTION CLARITY
==================================================

The dashboard should make the problem and solution obvious within seconds.

Show a clear message such as:

“Hostel energy waste is invisible.
We make it measurable, competitive and rewarding.”

The main dashboard should communicate:

- How much energy is being used
- Who is performing best
- How much energy the community has saved
- What the student can do to improve
- What reward they can unlock next

This gives judges a clear problem → solution connection.

==================================================
2. MAIN LEADERBOARD
==================================================

Create 50 hostel rooms.

Examples:

101–105
201–205
301–305
401–405
...

Display the TOP 10 on the main screen.

Each room should have:

- Rank
- Room number
- Student name
- Daily kWh
- Weekly average
- Rank movement
- Efficiency status

Efficiency:

50–80 kWh → Efficient → Green
80–120 kWh → Average → Amber
120–150 kWh → High Usage → Red

Top three:

🥇 #1
🥈 #2
🥉 #3

Make the top three visually prominent.

The leaderboard must be immediately understandable.

==================================================
3. COMMUNITY IMPACT
==================================================

Do not only show individual performance.

Show the impact of the entire hostel.

Example KPI cards:

12,480 kWh
COMMUNITY ENERGY SAVED

8.7%
REDUCTION THIS WEEK

50
ROOMS PARTICIPATING

72%
ROOMS BELOW TARGET

These numbers should come from the mock data rather than being meaningless static numbers.

This helps demonstrate real-world sustainability impact.

==================================================
4. PERSONAL PERFORMANCE
==================================================

Include a “My Room” experience.

Show:

- Current rank
- Previous rank
- Daily consumption
- Weekly average
- Target consumption
- Eco streak
- Next reward
- Achievement progress

Example:

“Room 304”

#7 OF 50

68 kWh TODAY

🔥 12 DAY ECO STREAK

“6 more efficient days → Coffee Voucher”

This makes the product personally motivating rather than just informational.

==================================================
5. ROOM ANALYTICS
==================================================

When a room is selected, show a detailed view.

Include:

- 7-day consumption graph
- 80 kWh target line
- Current consumption
- Weekly average
- Improvement percentage
- Rank movement
- Eco streak

The graph should make trends obvious.

Example:

“↓ 14% less energy than last week”

This demonstrates that the application is helping students understand behavior, not just displaying numbers.

==================================================
6. GAMIFICATION
==================================================

Make the competition meaningful.

Achievements:

🔥 Fire Badge
7-day efficient streak

⭐ Star Badge
14-day efficient streak

🏆 Crown Badge
Top 5 ranking

📈 Trending Badge
Biggest weekly improvement

🌱 Seedling Badge
First day below 80 kWh

♻️ Zero-Waste Badge
3 perfect days

Show locked and unlocked badges.

This creates a visible progression system.

==================================================
7. REAL-WORLD REWARDS
==================================================

Connect achievements to realistic campus perks.

Examples:

☕ $5 Coffee Voucher

🧺 $10 Laundry Credits

🅿️ Prime Parking — 1 Week

📚 Extended Library Hours

🎮 Gaming Room Access

Show:

CURRENT PROGRESS
████████████░░░ 80%

“6 efficient days until next reward”

This demonstrates how the product can influence real behavior.

==================================================
8. SOCIAL COMPETITION
==================================================

Add:

“Challenge a Friend”

Clicking it opens a modal.

Example message:

“I’m #7 on the Hostel Energy Leaderboard.
Think you can beat me?”

Add a mock copy/share button.

No backend is required.

This demonstrates the social mechanism behind the concept.

==================================================
9. INNOVATION
==================================================

Do not present this as another electricity-monitoring dashboard.

The key innovation is the combination of:

ENERGY DATA
+
SOCIAL COMPETITION
+
STREAKS
+
ACHIEVEMENTS
+
REAL CAMPUS REWARDS

Visually communicate this as the product's core loop.

TRACK
↓
COMPARE
↓
COMPETE
↓
ACHIEVE
↓
REWARD
↓
SAVE MORE

This should be one of the strongest visual sections of the application/presentation.

==================================================
10. TECHNICAL IMPLEMENTATION
==================================================

Use:

React + Vite
Tailwind CSS
Recharts
Lucide React
JavaScript mock data

No backend.

However, structure the frontend cleanly so that mock data could later be replaced by real APIs.

Keep components modular:

Leaderboard
RoomDetail
StatsCard
Badge
RewardCard
EnergyChart
Navigation
ChallengeModal

Generate 50 rooms using deterministic mock data.

Do NOT use Math.random() directly during every render.

The leaderboard should remain consistent after refresh.

==================================================
11. FUTURE SCALABILITY
==================================================

The prototype should visually suggest how the system could scale.

Future integration:

SMART METERS
↓
ENERGY DATA PLATFORM
↓
AI ENERGY INSIGHTS
↓
HOSTEL LEADERBOARD
↓
CAMPUS REWARDS

Potential future features:

- Smart meter integration
- Real-time consumption
- AI-generated energy-saving recommendations
- Hostel/floor competitions
- Campus-wide rankings
- Carbon footprint tracking
- Admin analytics

Do not build these now.

Show them only as future scalability.

==================================================
12. PREMIUM UI / UX
==================================================

Use a premium PURPLE technology aesthetic.

Primary:

#6D28D9
#8B5CF6
#A78BFA
#EDE9FE

Supporting:

#22C55E
#F59E0B
#EF4444
#17111F
#FFFFFF

Design language:

- Premium SaaS
- Gamification
- Sustainability technology
- Purple energy glow
- Clean cards
- Strong typography
- Subtle gradients
- Soft shadows
- Large numbers
- Clear data visualization
- Plenty of whitespace

Avoid:

- Generic admin dashboard
- Excessive cards
- Stock photos
- Cartoon graphics
- Overloaded screens
- Unnecessary animations
- Generic Bootstrap appearance

The UI should look like a product that could actually be launched.

==================================================
13. RESPONSIVE DESIGN
==================================================

Test for:

375px
768px
1440px

Mobile leaderboard:

Rank | Room | kWh

Room details can contain the remaining information.

All buttons should have comfortable touch targets.

Do not depend on hover interactions.

==================================================
14. MICRO-INTERACTIONS
==================================================

Use purposeful animations:

- Leaderboard rank movement
- Progress bar animation
- Badge unlock animation
- Subtle top-three pulse
- Confetti after achievement unlock
- Smooth room-detail transition

Animations should improve the demo rather than distract from it.

==================================================
15. DEMO EXPERIENCE
==================================================

The application should be extremely easy to demonstrate to judges.

Recommended demo flow:

STEP 1
Open dashboard.

Judge immediately sees:
“12,480 kWh saved”

STEP 2
Show the top 3 rooms.

STEP 3
Click Room 304.

STEP 4
Show:
68 kWh
#7 rank
12-day streak
7-day graph

STEP 5
Show:
“6 days until Coffee Voucher”

STEP 6
Open achievements.

STEP 7
Click “Challenge a Friend.”

This should take less than 60 seconds and demonstrate the majority of the product.

==================================================
16. MOCK DATA
==================================================

Generate 50 realistic rooms.

Each room:

{
roomNumber,
studentName,
dailyKwh,
weeklyHistory,
currentRank,
previousRank,
ecoStreak,
achievements,
perks
}

Keep the rankings logically consistent.

Example:

Room 304 — 58 kWh — #1
Room 102 — 63 kWh — #2
Room 407 — 67 kWh — #3
Room 203 — 69 kWh — #4
Room 501 — 72 kWh — #5

Make the data believable.

==================================================
17. IMPORTANT 30-MINUTE CONSTRAINT
==================================================

Do NOT waste time on:

- Backend
- Database
- Authentication
- API integration
- IoT integration
- Admin dashboard
- Complex settings

90% of effort should go into:

FUNCTIONALITY
+
UI POLISH
+
DEMO EXPERIENCE

The prototype should feel complete even though the data is mocked.

==================================================
FINAL PRODUCT MESSAGE
==================================================

The application should communicate this idea clearly:

“Instead of simply telling students to save electricity,
we make saving electricity visible, competitive and rewarding.”

The final product should score strongly on:

✓ Clear problem
✓ Relevant solution
✓ Innovation
✓ Working interactions
✓ Strong UI/UX
✓ Technical execution
✓ Sustainability impact
✓ Scalability
✓ Strong demo

Do not build a generic energy dashboard.

Build a product that makes judges think:

“This could actually work in a college hostel.”
