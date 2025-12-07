# Geolocation Surprise Page

This is a simple interactive webpage that asks for the user’s permission to access their device location and displays a playful “surprise” based on their coordinates. The page includes a consent modal, an animated overlay, and an option to copy the detected latitude and longitude.

## Features

* Browser-based geolocation request
* Consent modal before accessing location
* Animated overlay with a fun message
* Option to copy coordinates
* Error handling for denied permission, unavailable location, and timeouts
* Works on HTTPS or localhost (required by the geolocation API)

## How It Works

1. The user clicks the **Show me a surprise** button.
2. A consent modal appears.
3. On approval, the browser attempts to fetch geolocation coordinates.
4. If successful, an overlay displays:

   * Latitude
   * Longitude
   * A randomized “surprise” message
5. Users can copy the coordinates or close the overlay.

## Requirements

* A modern browser with geolocation support
* HTTPS or `http://localhost`
* No external libraries required

## File Structure

```
index.html   # Contains HTML, CSS, and JavaScript for the entire page
```

## Usage

Open the page in a browser, press the button, and follow the prompts to view your location-based surprise.

