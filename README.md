# Hydrus-Downloaders

These are downloaders which you can import to Hydrus. There's one at the moment cuz it's really all I wanted to do.

nitter w/ artist - adds a creator tag for nitter.eu URLS (u probably should download the nitter parser from here first tho: https://github.com/CuddleBear92/Hydrus-Presets-and-Scripts/tree/master/Downloaders/Nitter)

Another thing. Save this as a bookmark and it'll turn the current Twitter URL to a Nitter.eu URL:
`javascript(function()%7Bvar%20url%20%3D%20window.location.href%3Burl%20%3D%20url.replace('twitter.com'%2C%20'nitter.eu')%3Bwindow.prompt(%22Copy%20to%20clipboard%3A%20Ctrl%2BC%2C%20Enter%22%2C%20url)%7D)()`
