<a href="https://github.com/holopollock/watchlist-picker">
  <img width="230" alt="Watchlist Picker Development" src="dev-logo.png">
</a>

<br><br><br>

# Command-line Watchlist Picker

[[Installation](#installation)] [[Usage](#usage)]

A simple website that gives you a random film off your watchlist (or any list). The site is built with Vue, and deployed at [watchlistpicker.com](https://watchlistpicer.com) via Vercel. See also, the [Watchlist Picker backend](https://github.com/GoodbyteCo/Watchlist-Picker-Backend) and [CLI verion](https://github.com/HoloPollock/watchlist-picker).

A command-line tool to pick a random movie off your Letterboxd watchlist. The tool is also available as a more feature-rich web app, at [watchlistpicker.com](https://watchlistpicker.com). The source-code for the web app can be found in the [Goodbyte Watchlist Picker repository](https://github.com/GoodbyteCo/Letterboxd-Watchlist-Picker), and the backend in the [backend repository](https://github.com/GoodbyteCo/Watchlist-Picker-Backend).

## Installation

To install with Go, run: 

```
go get github.com/holopollock/watchlist-picker`
```

If you do not have Go intalled, clone this repository and run the included `build.sh` script.

## Usage

To use run:

```
watchlist-picker <USERNAME>
```

Where `<USERNAME>` is your Letterboxd username. For example, `watchlist-picker holopollock` will return a film off of Holopollock's watchlist.
