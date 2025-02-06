# Booking.com Web Scraper

A Python-based web scraping tool that automates hotel searches on Booking.com and extracts relevant information about available accommodations.

## Features

- Automated hotel search on Booking.com
- Currency selection
- Date range selection
- Number of adults specification
- Hotel filtering by star rating
- Price sorting (lowest first)
- Results displayed in a clean table format

## Prerequisites

- Python 3.6 or higher
- Chrome browser
- ChromeDriver (compatible with your Chrome version)

## Project Structure
booking-scraper/
├── booking/
│ ├── init.py
│ ├── booking.py # Main booking automation class
│ ├── booking_filtration.py # Filtering functionality
│ ├── booking_report.py # Results processing
│ └── constants.py # Configuration constants
├── run.py # Script entry point
└── README.md
