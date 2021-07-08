# SerenityOS User Map

A map showing where in the world the SerenityOS developers and users are :^)

**[Visit the map!](https://usermap.serenityos.org)**

## Contribution

If you want to add yourself to the repo, make a PR that adds a file to the folder [`people`](people/). This file has to have the following format and should have `${your-nick}.json` as name:

```json
{
  "nick": "denvercoder9",
  "coordinates": [
    48.77844,
    9.18014
  ],
  "links": {
    "Website": "https://example.com",
    "GitHub": "https://github.com/denvercoder9"
  }
}
```

Some tips:
- You can find your location with either [OpenStreet Maps](https://www.openstreetmap.org/), [Google Maps](https://www.google.com/maps) or your mobile phone if GPS is enabled
- `links` is an object where each key will be displayed as a link with the string content as `href`.
- You decide how precise you want it to be. On your room, just the right street, the center of the city, center of the country. You decide!

NOTE: The website files are in `docs/`, because GitHub Pages still only deploys either from there or the repo root.
