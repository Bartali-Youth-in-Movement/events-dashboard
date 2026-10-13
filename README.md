# Bartali Events Dashboard

A lightweight, interactive dashboard for exploring Bartali cycling events across Israel. The site helps riders and organizers browse events by center, group, difficulty, season, distance, and climbing, while viewing each event on an interactive map and inspecting route details.

This project is built as a static web app and does not require a framework or build step.

## Overview

The Bartali Events Dashboard is designed to make event discovery easy and visual. It allows users to:

- browse all events in one place
- filter by region, center, audience, duration, and technical level
- search by event name, place, or activity center
- view route details on a map
- compare routes by distance and cumulative ascent
- see elevation profile and event metadata

It is especially useful for presenting Bartali cycling activities in an accessible and organized way.

## Features

- Interactive map with event routes
- Search and filtering tools
- Event sorting by date, distance, or climbing
- Difficulty indicators for route complexity
- Route statistics such as distance and total ascent
- Event detail panel with route information
- Responsive layout for desktop and mobile
- Light/dark theme toggle
- Hebrew-language interface

## Tech Stack

- HTML
- CSS
- JavaScript
- Leaflet for map rendering
- Google Apps Script / Google Sheets as data source

## Project Structure

```text
events-dashboard/
├── index.html        # Main app file, styles, and JavaScript
├── README.md         # Project documentation
└── .gitignore        # Optional repository settings
