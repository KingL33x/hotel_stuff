# Study Rooms

Study Rooms is a self-contained, browser-based prototype for finding and booking study rooms. It uses a GOV.UK-style interface and JavaScript to provide an interactive booking journey.

All rooms, availability and bookings are fictional. The prototype is intended for student demonstration and usability testing only.

## Features

- Search by date, start time, end time and group size
- Filter rooms by building and facilities
- View room details and availability
- Check booking details before confirmation
- Receive an in-page booking reference
- View confirmed bookings
- Reset the prototype to restore its initial state
- Responsive layout and keyboard-friendly navigation

## Included screens

1. **Find a room** - enter booking requirements
2. **Search results** - filter and compare rooms
3. **Room details** - view the building, floor, capacity and facilities
4. **Check your booking** - review and confirm the booking
5. **Booking confirmed** - view the reference and room instructions
6. **My bookings** - view active and completed bookings

## Run locally

The project has no build step or package dependencies.

From the project directory, start a local static server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

You can also open `index.html` directly, although a local server is recommended.

## Prototype behaviour

- Rooms and availability are stored in memory while the page is open.
- Refreshing or closing the page clears newly created bookings.
- The **Reset prototype** link returns the prototype to its initial state.
- Help, accessibility statement, contact and cancellation actions are intentionally marked as not yet implemented.
- The fake booking flow does not send emails or connect to an API.

## Files

- `index.html` - the complete prototype, including markup, styles and JavaScript
- `README.md` - project documentation

## Example rooms

The prototype includes rooms at:

- Brindley Library
- Ashworth Science Hub
- Kemp Hall