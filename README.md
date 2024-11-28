# Geolocation-Based Address Fetcher
A web-based application that enables users to fetch their current geographical coordinates and detailed address information using the Geolocation API and OpenCage Geocoder API. This app ensures user convenience by storing location data in cookies for quick access.

## 🌟 Features
### Geolocation Functionality
 - Fetches user's current location with a single click.
 - Handles browser permissions and errors gracefully.
### Address Details
<ins> Displays: </ins>
- Latitude and Longitude coordinates.
- City, State, Postcode, and Country.
- A fully formatted address for easy reference.
### Cookie Storage
- Automatically saves location data (City, State, Postcode, Country) in cookies for 7 days.
- Enables faster access to previously fetched data.
### Error Handling
- Notifies users if geolocation is disabled or unsupported in their browser.
- Displays appropriate messages when location fetching fails.
## 🛠️ Technical Stack
### Frontend
- HTML, CSS, and JavaScript.
### APIs
- Geolocation API: Fetches user coordinates.
- OpenCage Geocoder API: Translates coordinates into address details.
### Cookie Management
- Utilizes JavaScript-based cookies for storing location data locally.

