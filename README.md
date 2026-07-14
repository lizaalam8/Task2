# FlyHigh Airways - Airplane Management System

A responsive airline operations dashboard built with HTML, Tailwind CSS and a custom stylesheet. Built for Task 2.

## Pages

- `welcome.html` - Intro/landing page with a link into the dashboard
- `index.html` - Home Dashboard with key stats, recent bookings and a live board snapshot
- `tickets.html` - Ticket Management with search, filters and a full tickets table
- `departures.html` - Departures board with filter tabs and quick stats
- `arrivals.html` - Arrivals board with filter tabs and quick stats

## Structure

```
task2/
  welcome.html
  index.html
  tickets.html
  departures.html
  arrivals.html
  css/
    tailwind.css
    style.css
  README.md
```

## Tech Used

- Tailwind CSS, compiled locally to `css/tailwind.css` (no CDN, loads instantly and works offline)
- Custom external stylesheet (css/style.css) for the sidebar, flight board and footer
- Font Awesome icons
- Google Fonts: Space Grotesk, Inter, IBM Plex Mono

## Running It

No build step required. Open `index.html` directly in a browser, or serve the folder with any static server:

```
npx serve .
```

## Notes

The sidebar collapses into a slide-in menu below 1024px width. All tables scroll horizontally on small screens so nothing breaks on mobile.