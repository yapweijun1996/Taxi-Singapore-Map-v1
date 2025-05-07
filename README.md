# Taxi Availability Map Singapore

A responsive, interactive web map showing real-time taxi availability in Singapore. Users can locate nearby taxis within a specified radius by adjusting a slider, and the map updates dynamically. The app adapts well to both desktop and mobile devices.

---

## Features

- Displays your current location on the map.
- Shows only taxis within a user-selected radius.
- Auto-fly to your location when data is fetched.
- Responsive design with controls fixed at top or bottom depending on screen size.
- Refresh button to manually update taxi data.
- Cool pulse animation for your location marker.
- Instant filtering of taxis inside the selected radius.
- Updated automatically every 3 minutes.

---

## How to Use

1. **Open the webpage** in your browser (host it locally or via your server).
2. **Allow location access** to enable your current position.
3. Use the **radius slider** to set your search radius in kilometers.
4. The map will display your location and nearby taxis within that radius.
5. Click **"Refresh Data"** to fetch the latest taxi positions.
6. Adjust the radius slider anytime to see more or fewer taxis.

---

## How it Works

- The app loads the latest taxi data from [Singapore government API](https://data.gov.sg).
- All taxi positions are fetched once and stored.
- When you change the radius, only taxis inside that range are shown.
- The map intelligently zooms and recently centers on your location for better usability.

---

## Technologies Used

- **HTML5**, **CSS3**
- **JavaScript (ES6+)**
- **Leaflet.js** — Interactive map library

---

## Usage & Deployment

- Save the full code as `index.html`.
- Open in your browser for testing.
- To deploy, upload the file to your web server or host on GitHub Pages.

---

## License

This is a simple demo project. Feel free to reuse and adapt.

---

## Note

This code is a simple example for educational purposes. For production, consider adding:

- Error handling with user notifications
- Improved styling and UX
- Data caching or real-time updates with WebSocket
- Clustering for many taxis
- Custom icons or info popups

## Demo 
https://yapweijun1996.github.io/Taxi-Singapore-Map-v1/

## Preview
![image](https://github.com/user-attachments/assets/d7d43931-3189-4b71-9614-69d99472c0e8)
