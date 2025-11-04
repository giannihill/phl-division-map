# Philadelphia Division Map

This project displays a precinct-level election map for Philadelphia using D3.js and TopoJSON.  
Division boundaries come from the City of Philadelphia’s **Political Ward Divisions** dataset, which notes that each division’s four-digit ID’s first two digits represent the ward.

## Setup

1. Generate `division_map.topo.json` using BigQuery and mapshaper (see notes in `index.html`).
2. Clone this repository and run a local web server:
   ```bash
   npm install -g http-server
   http-server .
   ```
3. Open `http://localhost:8080` in your browser.

Use the dropdown to switch between metrics (Q–Y) and hover over divisions to view details like reporting status and race results.
