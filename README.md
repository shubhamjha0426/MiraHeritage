# MIRA HERITAGE — Cultural Discovery Website

A polished, responsive cultural and local tourism website for Mira-Bhayandar.

## Run locally
1. Extract the ZIP file.
2. Open the `MiraHeritage_Pro` folder in VS Code.
3. Open `index.html` in a browser, or install the VS Code **Live Server** extension and click **Go Live**.

## Working features
- Responsive navigation and layouts
- Search across place names, areas and descriptions
- Category filters and curated mood shortcuts
- Place detail modals with Google Maps directions
- Save/favourite places (browser localStorage)
- Build, clear, share and open a multi-stop itinerary in Google Maps
- Visitor reviews with selectable star rating (stored locally)
- Place suggestions form (stored locally)
- Click/tap ripple wave effect
- Scroll progress indicator and back-to-top button

## Important production notes
This is a complete working front-end. It does not pretend to have a server: saved places, reviews and suggestions are stored in the visitor's own browser and are not shared with other visitors. For a public production launch, connect a backend/database and secure form service for cross-device accounts, public reviews and business submissions. Do not publish private email addresses or collect sensitive personal information without a privacy notice and appropriate safeguards.

Place descriptions are concise visitor-guide summaries. Check local access, timings, entry rules and safety before travel. Images are loaded from Unsplash URLs and need an internet connection.

## Place research
The place list was assembled using Mira-Bhayandar Municipal Corporation / myMBMC tourism and garden listings, with additional map listing information for some destinations. Review source details and confirm access before publishing changes.


## Destination photography
The previous generic Unsplash landscape placeholders have been replaced with real photographs of Mira-Bhayandar/Uttan-area locations and local scenes. Photo sources include Wikimedia Commons (Ghodbunder Fort, Uttan/Velankanni coast, creek and local garden/coast views), the official Keshav Srushti gallery, and identified local photo pages for Uttan Beach, Janjire Dharavi Fort and ISKCON Mira Road.

Some smaller municipal parks and St. Jerome Church do not have a confidently verified public photograph in the sources checked. For those cards, a real nearby Mira-Bhayandar-area scene is used rather than claiming an unrelated stock image is the exact site. Please retain photo-source credits and verify each image's licence/attribution requirements before commercial use. Images are loaded from their source websites, so an internet connection is required.


### Image loading fix
Destination photo links from Wikimedia Commons now use the Commons FilePath redirect instead of manually guessed upload hashes. Destination-card and itinerary images also have an automatic Uttan shoreline fallback if an external image host fails. An internet connection is required for these externally hosted photographs.
