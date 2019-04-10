# Steam Portal

This page lists my Github repositories which objective is to analyze [Steam](https://store.steampowered.com) data.

## I. Store descriptions

### Similarity

-   [`steam-descriptions`](https://github.com/woctezuma/steam-descriptions): retrieve games with similar store descriptions.

## II. Store banners

### 1. Similarity

-   [`download-steam-banners`](https://github.com/woctezuma/download-steam-banners): retrieve games with similar store banners,
-   [`download-steam-screenshots`](https://github.com/woctezuma/download-steam-screenshots): retrieve games with similar store screenshots.

### 2. Generative Adversarial Networks

-   [`google-colab`](https://github.com/woctezuma/google-colab): train a [DCGAN](https://arxiv.org/abs/1511.06434) to generate 28x28 store banners,
-   [`steam-stylegan`](https://github.com/woctezuma/steam-stylegan): train a [StyleGAN](https://arxiv.org/abs/1812.04948) to generate 128x128 store banners.

## III. Scores

### 1. Rankings

-   [`hidden-gems`](https://github.com/woctezuma/hidden-gems): rank games to discover "hidden gems". NB: This lead to my contribution to [Steam250](https://steam250.com/contributors),
-   [`Steam-Bayesian-Average`](https://github.com/woctezuma/Steam-Bayesian-Average): rank games, developers and publishers,
-   [`hidden-demos`](https://github.com/woctezuma/hidden-demos): rank games which offer a demo.

### 2. Community

-   [`metacouncil-goty`](https://github.com/woctezuma/metacouncil-goty): ranked-choice voting for Games of the Year Awards on [MetaCouncil/Steam](https://metacouncil.com) in 2018,
-   [`steam-era-goty`](https://github.com/woctezuma/steam-era-goty): ranked-choice voting for Games of the Year Awards on [ResetERA/Steam](https://resetera.com) in 2017,
-   [`steam-groups`](https://github.com/woctezuma/steam-groups): descriptive stats regarding the libraries of members of a Steam group.

## IV. Store tags

-   [`match-steam-tags`](https://github.com/woctezuma/match-steam-tags)@[PyPI](https://pypi.org/project/steamtags/): download and match Steam tags with appIDs,
-   [`steam-tag-mapping`](https://github.com/woctezuma/steam-tag-mapping): visualize an embedding of Steam tags.

## V. Store reviews

-   [`steam-reviews`](https://github.com/woctezuma/steam-reviews): stats and sentiment analysis of reviews,
-   [`sample-steam-reviews`](https://github.com/woctezuma/sample-steam-reviews): sample reviews for the game called « Artifact »,
-   [`steam-cut`](https://github.com/woctezuma/steam-cut): fetch the number of reviews for Steam and non-Steam purchases,
-   [`players-vs-reviews`](https://github.com/woctezuma/players-vs-reviews): discover games with an unusual ratio of number of players vs. number of reviews.

## VI. Miscellaneous

-   [`humble-monthly`](https://github.com/woctezuma/humble-monthly): analyze of the content of Humble Monthly Bundles,
-   [`recent-sales`](https://github.com/woctezuma/recent-sales): a crude attempt at estimating Steam sales and revenue.

## VII. Data scraping

### 1. SteamSpy API

-   [`steamspypi`](https://github.com/woctezuma/steamspypi)@[PyPI](https://pypi.org/project/steamspypi/): an API to download data through [SteamSpy API](https://steamspy.com/api.php).

### 2. Steam API

-   [`download-steam-reviews`](https://github.com/woctezuma/download-steam-reviews)@[PyPI](https://pypi.org/project/steamreviews/): download every review for the game of your choice,
-   [`steampi`](https://github.com/woctezuma/steampi)@[PyPI](https://pypi.org/project/steampi/): download app details (including release date) through Steam API, and match names with appIDs,
-   [`steam-api`](https://github.com/woctezuma/steam-api): download a list of all appIDs through Steam API, then download their app details, create an aggregate similar to SteamSpy's (but more exhaustive), finally analyze store attributes and map tags.

NB: With `steam-api`, store descriptions can also be aggregated for [later processing](https://github.com/woctezuma/steam-portal#i-store-descriptions).

## VIII. Data snapshots

-   [`steam-api-data`](https://github.com/woctezuma/steam-api-data): app details,
-   [`download-steam-banners-data`](https://github.com/woctezuma/download-steam-banners-data): store banners,
-   [`download-steam-screenshots-data`](https://github.com/woctezuma/download-steam-screenshots-data): store screenshots,
-   [`steam-reviews-data`](https://github.com/woctezuma/steam-reviews-data): reviews,
-   [`hidden-gems-data`](https://github.com/woctezuma/hidden-gems-data): language stats for regional rankings of "hidden gems",
-   [`recent-sales-data`](https://github.com/woctezuma/recent-sales-data): aggregate of SteamSpy data between July 17th, 2017 and February 6th, 2018.
