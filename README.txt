Vadodara Bus Finder v0.1
========================

This is a browser/PWA prototype built from the seven user-supplied Vadodara bus PDFs.

Files:
- index.html        Mobile-first bus search UI
- data.json         Extracted timetable + master route data
- manifest.webmanifest  PWA metadata
- service-worker.js Offline cache

How to test locally:
1. Put these files in one folder.
2. Run a local web server (for example: python -m http.server 8000).
3. Open http://localhost:8000
4. Search an origin and destination that occur in the same timetable direction.

Important:
- Direct trips only; transfers are not implemented.
- Google Maps is opened through a directions URL; no Maps API key is embedded.
- The supplied source data contains flagged anomalies and route/timetable mapping questions.
- This is not an official VMC/VITCOS application.
