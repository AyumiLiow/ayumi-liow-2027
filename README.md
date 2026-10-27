# why does a sound move us?

A one-page site showing Ayumi Liow's research interests in Kansei (感性), music and movement, prepared for prospective PhD supervisors at Waseda University (September 2027).

## Files

- `index.html`: the page (all styles and scripts are inside it)
- `fonts/`: Satoshi Medium and Bold (from Fontshare / Indian Type Foundry)
- `assets/dance-tonight.mp3`: "Dance Tonight" (instrumental) by Ayumi
- `assets/star-trails.jpg`: background photo, NASA/Anil Menon

## Run locally

Open `index.html` in a browser. For the music-reactive animation, serve the folder instead of opening the file directly:

```
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. The site appears at `https://<your-username>.github.io/<repository-name>/` after a minute or two.

## Credits

- Background image: [Star trails over the Banda Sea](https://www.nasa.gov/image-article/star-trails/), NASA/Anil Menon
- Font: [Satoshi](https://www.fontshare.com/fonts/satoshi) by Indian Type Foundry
- Japanese font: Noto Sans JP, loaded from Google Fonts
- Music: ["Dance Tonight"](https://youtu.be/Y14dAFeVZHw) (instrumental) by Ayumi. All rights reserved.
