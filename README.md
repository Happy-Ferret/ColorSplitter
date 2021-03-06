# ColorSplitter

Website: http://comfreek.github.io/ColorSplitter/<br>
Demo: http://comfreek.github.io/ColorSplitter/release/index.html<br>
Idea from SoftwareRecommendations.SE: [Web app to extract all colours of an image](http://softwarerecs.stackexchange.com/a/14864/583)

## Screenshot
![Screenshot of ColorSplitter fed with the Google logo](https://raw.githubusercontent.com/ComFreek/ColorSplitter/screenshots/google-logo-screenshot.PNG)


## Description
ColorSplitter is a web app to show each and every color an image uses.

The user simply selects a file, which then gets analyzed on the client-side. No data is sent to a server.

## Supported browsers

These browsers are known to work with ColorSplliter:

- Google Chrome 39.0.2171.93 (on Android)
- Google Chrome 41.0.2258.2 canary (on Windows)
- Opera 26.0.1656.60
- Firefox Nightly 37.0a1 (2014-12-25)<br>
  (Note that the number of pages and the current page number are erroneously not shown, however, the rest of the web app is still usable.)

## How to install (for end users)
1. Download the latest release: https://github.com/ComFreek/ColorSplitter/releases.
2. Extract the contents of the ZIP folder to your favorite location.
3. Open `index.html` in a supported browser.

## How to install (for developers)

1. Download this repository, either via Git or via the [ZIP download GitHub offers](https://github.com/ComFreek/ColorSplitter/archive/master.zip).

2. Install NodeJS.

3. Execute `npm install && gulp` inside the project's directory.

4. Open `release/index.html` in a supported browser.

## Author, License
[ComFreek](https://github.com/ComFreek), [@ComFreek](http://twitter.com/ComFreek)
MIT License (c) 2014 ComFreek
