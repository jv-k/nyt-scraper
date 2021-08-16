# nyt-scraper

Since the [Incognito Mode](https://www.niemanlab.org/2019/02/your-favorite-way-to-get-around-the-new-york-times-paywall-might-be-about-to-go-away/) workaround doesn't seem to work any longer to bypass NYT's subscription paywall, this repository is one of many ways to programmatically bypass the client-side JavaScript system that they are using.

## Run the scraper

```
git clone https://github.com/jv-k/nyt-scraper.git
cd nyt-scraper
npm start
```
Then go to your browser and load:
```
localhost:5000/?url=<nyt paywalled article URL>
```

Et voíla.

**Disclaimer**: This repo is for educational purposes ONLY.
