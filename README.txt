CINEMORA — HTML + CSS MOVIE REVIEW WEBSITE
==========================================

WHAT IS INCLUDED
- 14 linked HTML pages
- One shared responsive stylesheet: css/style.css
- An images folder with a guide for your own posters, banners and profile pictures
- No JavaScript, React, Bootstrap or Tailwind

HOW TO RUN
1. Extract CINEMORA.zip.
2. Open the CINEMORA folder in VS Code.
3. Open index.html.
4. Right-click index.html and choose "Open with Live Server" (if you have the Live Server extension).
   Or double-click index.html to open it in your browser.

HOW TO ADD YOUR OWN IMAGES
1. Put your image files inside the images folder.
2. Use the exact filenames listed in images/IMAGE_GUIDE.txt.
3. To use a different filename, open the relevant HTML page and change the src value.
4. Recommended:
   - Movie posters: portrait 2:3 JPG or WebP
   - Hero/banner images: landscape 16:9 JPG or WebP
   - Profile images: square JPG or WebP
5. You can add unlimited cards: copy a <article class="movie-card">...</article> block in discover.html and change its title, year, genre, rating and image filename.

IMAGE FILES TO ADD
See images/IMAGE_GUIDE.txt. The project intentionally leaves image slots ready for your own pictures.

PAGES
index.html          Home
discover.html       Discover movies
movie.html          Movie detail and multi-part rating
review-hub.html     Community review feed
write-review.html   Review form
critics.html        Critics profiles
rankings.html       Film rankings
collections.html    Curated collections
watchlist.html      Watchlist sample
diary.html          Watched-film diary
compare.html        Compare two films
profile.html        User profile
login.html          Login screen
register.html       Registration screen

IMPORTANT LIMITATION
Because this project uses only HTML and CSS:
- Navigation, responsive layout, hover effects and forms are present.
- Forms do not save data.
- Login/register do not create accounts.
- Reviews, ratings, watchlists and diary entries are sample/static content.
To make those features actually work later, you will need a backend/database and JavaScript or another server-side solution.
