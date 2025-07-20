# UntrackMe (fork)

<img src="app/src/main/ic_launcher-playstore.png" alt="Logo" width="70">

## What does UntrackMe do?

Basically it handles URLs. It can do these:

### Redirect
- Transform YouTube, Twitter, Instagram and Google Maps URLs into URLs of front-ends and services that respect your privacy.

### Unshorten
- See the real link behind short URLs of some URL shortening services without loading the web page

### Cleanup
- Remove known UTM parameters from URLs

## Two variants

There are two variants of UntrackMe. Both are free:

- **UntrackMe Full**  
  Has all the features mentioned above
- **UntrackMe Lite**  
  Only has 'Redirect' and 'Unshorten' features

## Features

### Redirect
UntrackMe can redirect you to privacy-friendly services:

- YouTube → [Invidious](https://www.invidio.us/)
- Twitter → [Nitter](https://nitter.net/)
- ~~Instagram → Bibliogram~~ [Deprecated](https://cadence.moe/blog/2022-09-01-discontinuing-bibliogram)
- Google Maps → [OpenStreetMap](https://www.openstreetmap.org/)  
  *Optionally, you can use geo URIs instead of OSM*

### Unshorten
View the real address behind short links from these services:

- t.co
- nyti.ms
- bit.ly
- tinyurl.com
- goo.gl
- ow.ly
- bl.ink
- buff.ly

### Cleanup
Remove known tracking parameters (like UTM) from URLs

## How-to

If you have a URL somewhere in your phone:
1. Open it with UntrackMe or share the URL to the app
2. UntrackMe will transform the URL
3. It will display a popup letting you select an app to open the new URL

## Customize Invidious Parameters

Invidious allows customization via URL parameters. To configure:

1. Open UntrackMe
2. Press the settings icon in Invidious section (not the one on top)
3. Touch any parameter you want to customize and choose an option:
   - **Ignore**: No action for the parameter
   - **Remove**: Remove the parameter if it exists
   - **[Available values]**: Add or modify the parameter with your chosen value

## To make it easier to Untrack :)

Set UntrackMe as the default app to handle URLs by selecting "Always" in Android's "Open with" dialog.

**For Lite version only:**
1. Click 'CONFIGURE' button in the app
2. Go to "Open by default" → "Open supported links in this app" → select "Always allow"
3. Check the apps page - all items should have tick marks

## Links

- **Source code**: [untrackme-fork](https://github.com/nubesurrealista/Untrackme-fork)
