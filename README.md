
A single-page weather lookup built with plain HTML, CSS, and JavaScript. Type any city name into the input, hit search, and it fetches live data from the OpenWeatherMap API—no build tools or frameworks required. The design is simple but clear: you see city, temperature, humidity, and a weather icon.

What You Can Do

Search for any city worldwide

View current temperature, humidity, and conditions

See a matching icon (sunny, cloudy, rain, etc.)

Smooth CSS transitions when results update

Tech Stack
HTML · CSS ·  JavaScript · Fetch API · OpenWeatherMap API ·  JavaScriptDOM 

How to Run
Clone the repo, open index.html in your browser, type a city, and view the live weather.

├── .env
├── README.md
└── server
    ├── .gitignore
    ├── app.js
    ├── build
        ├── images
        │   ├── clear.png
        │   ├── clouds.png
        │   ├── drizzle.png
        │   ├── humidity.png
        │   ├── mist.png
        │   ├── rain.png
        │   ├── search.png
        │   ├── snow.png
        │   └── wind.png
        └── index.html
    ├── package-lock.json
    └── package.json
