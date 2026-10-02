# Kalkaska RV Park — Booking Assistant (POC)

A clickable proof of concept for a natural-language booking assistant for Kalkaska RV Park & Campground, scoped to pull-through sites F1–F10.

**Live demo:** see repo Settings → Pages once enabled, or the link shared alongside this repo.

## What it demonstrates
- A camper describes their rig and dates in plain language ("40' trailer, 50 amp, full hookup, July 3 through the 10") and the assistant checks it against F1–F10's specs, the park's season dates, and existing bookings.
- Every match only creates a **pending** request — nothing books automatically. Joe (the owner) reviews and approves or declines each one from the owner view (toggle in the top bar).
- Data is stored in the browser's local storage for this demo only — it is not a shared backend, and "Reset demo data" at the bottom restores the original sample bookings.

## Status
Proof of concept. Not connected to a real reservation system, payment processing, or live site inventory beyond F1–F10.
