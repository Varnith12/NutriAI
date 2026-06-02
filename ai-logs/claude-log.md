##Prompt

I am building a mobile-first web app called NutriAI. Before implementing functionality, create a complete UI/UX prototype using HTML, CSS and JavaScript. The app should include:

* Dashboard with calories, water intake, steps, health score, streak and reward points
* AI Food Scanner page
* AI Coach section
* Food Swap AI recommendations
* Diet Plan page
* Meal History page
* Progress Tracking page
* Challenges & Rewards page
* Restaurant Finder page
* Profile page
Use a modern health-tech design, glassmorphism, smooth animations, mobile-first layout, bottom navigation, sidebar menu, and professional dashboard cards.
Use dummy data only. Focus on UI and navigation. Generate the entire project structure and code.

##Response

Here's your complete NutriAI mobile-first prototype — a single self-contained HTML file with everything wired up.
What's included:
10 fully designed pages — all navigable via bottom nav, sidebar menu, and in-page cross-links:

🏠 Dashboard — health score rings, calorie/water/steps/points stat cards, streak banner, macro progress bars, today's meals, AI tip
📷 Food Scanner — animated scanning frame, detected food result card, full nutrition breakdown, recent scans
🤖 AI Coach — live chat interface with Coach Nova, insight cards, quick-question chips, functional send button
🔄 Food Swap AI — 3 side-by-side swap cards with before/after nutrition diffs and weekly savings summary
🥗 Diet Plan — active plan header, day tabs (Mon–Sun), 4 meal slots with ingredients
📋 Meal History — filter tabs, multi-day grouped log with macros and timestamps
📈 Progress — bar charts, weight/BMI/fat/muscle stats, metric cards with trend arrows, goal progress bars
🏆 Challenges — active challenge cards with progress, leaderboard, rewards store
🍽️ Restaurants — map placeholder, cuisine filter chips, health-scored restaurant cards
👤 Profile — avatar, stats, health goals grid, account settings rows

Design system: Dark health-tech theme with glassmorphism, Clash Display + Satoshi typography, animated ambient background blobs, gradient
accent system (green/cyan/purple/amber), scanning line animation, toast notifications, and smooth page transitions throughout.

##Prompt

Convert this NutriAI UI into a functional application. Start with the AI Food Scanner. Integrate Gemini Vision API so users can upload a 
food image and receive:

* Food name
* Calories
* Protein
* Carbs
* Fat
* Health Score (1–10)
If the health score is below 7.5, automatically trigger AI Coach recommendations and Food Swap AI suggestions.
Implement this feature first before any other feature.

##Response

Now I have a clear picture of the full app. I'll rebuild the scanner page with full Gemini Vision integration, plus dynamic AI Coach + Food
Swap panels that auto-trigger on low health scores.Ran a command, edited a fileRan a command, edited a fileNow add the spinner CSS and all
the scanner JS logic:
