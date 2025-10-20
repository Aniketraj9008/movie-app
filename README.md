CineSearch (Movie App)
CineSearch is a supercharged movie discovery web app that lets users search, filter, sort, and explore movies using data from The Movie Database (TMDB) API. It features an elegant, responsive UI built entirely with Tailwind CSS and modern JavaScript — no frameworks required.

🚀 Features
Search & Discover – Instantly search for movies or browse curated lists such as Popular, Top Rated, and Upcoming.

Filter & Sort – Refine results by genre, release year, minimum rating, or sort order (popularity, revenue, rating, etc.).

Surprise Me! – Fetch a completely random movie for a pleasant discovery experience.

Detailed Movie Modal – View rich movie details such as runtime, rating, certification, and genre, enhanced by backdrop and poster visuals.

Responsive UI – Fully optimized for desktop and mobile devices.

Pagination System – Easily navigate through multiple pages of results.

Dynamic Filters Display – Shows your active filters as animated tags for quick filtering adjustments.

🧰 Tech Stack
Frontend: HTML5, Tailwind CSS, JavaScript (Vanilla)

API: TMDB API

Fonts: Inter (via Google Fonts)

Icons: SVG-based from Heroicons

⚙️ Setup Instructions
1. Clone the project
bash
git clone https://github.com/your-username/cinesearch.git
cd cinesearch
2. Open the file
Simply open the index.html file in your browser:

bash
open index.html
3. Add your TMDB API key
Replace the placeholder in the script section:

js
const apiKey = 'YOUR_TMDB_API_KEY';
You can obtain a free key from The Movie Database.

🧩 Folder Structure
text
cinesearch/
│
├── index.html          # Main application file
├── README.md           # Documentation
└── assets/             # (Optional) directory for local images if used
🧠 Core JavaScript Functions
fetchAndDisplay(view, query, page)
Dynamically fetches movie data based on the chosen list, filters, or search keywords.

applyCurrentFilters()
Gathers user-selected filters and triggers an updated movie fetch.

showMovieDetails(movieId)
Displays a rich modal with detailed information for a selected movie.

surpriseMe()
Fetches a random movie result from TMDB’s popular list.

setupPagination()
Handles navigation between pages of results.

🎨 UI Enhancements
Built with Tailwind CSS 3+ for rapid UI styling.

Utilizes CSS animations (fadeIn and popIn) for smooth modal and tag interactions.

Responsive grid design scales from mobile to large desktop screens.

🔒 API & Rate Limits
Please note that TMDB’s free API plan includes rate limitations. Avoid spamming API requests (especially with “Surprise Me!”) to stay within safe limits.

🌟 Future Improvements
Add user authentication for favorite lists

Allow saving filters persistently

Integrate infinite scrolling

Dark/light mode toggle

