# Gather &mdash; Event Management Dashboard

**Day 22 of 30 Days of Code**

A clean, responsive, single-file event management dashboard built with vanilla HTML, CSS, and JavaScript &mdash; no frameworks, no build step.

## Features

### Dashboard Overview
- **Stats cards** &mdash; Total tickets sold, revenue, check-ins, and active events with month-over-month change indicators
- **Upcoming events list** &mdash; Card-based layout with progress bars, sales tracking, and quick action buttons (preview / log sales)
- **Attendee management** &mdash; Searchable, filterable table with check-in toggling and status tracking
- **Ticket sales overview** &mdash; Progress visualization for each event
- **Quick summary** &mdash; Check-in rate, upcoming events in next 30 days, registration count

### Create Event Wizard
A 4-step form flow:
1. **Event information** &mdash; name, type, and description
2. **Date and location** &mdash; date picker, start time, venue, and city
3. **Tickets** &mdash; ticket tier, price, and total capacity
4. **Cover photo** &mdash; optional image upload (JPG/PNG, up to 5 MB)

### Interactive Elements
- **Live filtering** &mdash; events by type, attendees by name, ticket tier, and status
- **Dark / light mode** &mdash; toggle with persisted preference
- **Event preview modal** &mdash; venue, sales, gross revenue, and copyable gate code
- **Attendee detail modal** &mdash; ticket info, status, and registration date
- **CSV export** &mdash; download the filtered attendee list
- **Toast notifications** &mdash; inline feedback for all actions
- **Loading skeleton** &mdash; animated placeholder while initial data loads

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS Custom Properties, CSS Grid, Flexbox |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Barlow (body), IBM Plex Mono (code/nav) |
| Hosting | Static &mdash; open `index.html` in any browser |

## Data

All sample data is embedded in `index.js` inline as JavaScript objects:

- **4 events** across Music, Technology, and Workshop categories
- **10 registered attendees** with varying ticket tiers and check-in statuses

## File Structure

```
day-22/
├── README.md
├── DAY 22 CHALLENGE.docx
└── index.html
```

## Getting Started

```bash
# Clone or navigate to this directory, then open in a browser:
open index.html
```

Alternatively, serve with any static server:

```bash
npx serve .
```

## License

Part of the **30 Days of Code** challenge. See individual challenge documentation for context.