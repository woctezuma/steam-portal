# Steam Portal

This page lists my Github repositories which objective is to analyze [Steam](https://store.steampowered.com) data.

## I. Store descriptions

### 1. Similarity

-   [`steam-descriptions`](https://github.com/woctezuma/steam-descriptions): retrieve games with similar store descriptions,
-   [`woctezuma.github.io`](https://woctezuma.github.io/): visualize, as a graph, games with similar store descriptions.

### 2. Generative Language Model

-   [`sample-steam-descriptions`](https://github.com/woctezuma/sample-steam-descriptions): sample store descriptions, with the GPT-2 language model.

## II. Store banners

### 1. Similarity

-   [`download-steam-banners`](https://github.com/woctezuma/download-steam-banners): retrieve games with similar banners, using MobileNet (alpha 0.25, input 128x128x3).
-   [`match-steam-banners`](https://github.com/woctezuma/match-steam-banners): retrieve games with similar banners, using MobileNet v3 (alpha 1.00, input 256x256x3).
-   [`steam-CLIP`][banner-repository-CLIP]: retrieve games with similar store banners, using OpenAI's CLIP (input 224x224x3).
-   [`steam-DINO`](https://github.com/woctezuma/steam-DINO): retrieve games with similar store banners, using Facebook's DINO (input 224x224x3),
-   [`steam-DINOv2`](https://github.com/woctezuma/steam-DINOv2): retrieve games with similar store banners, using Meta AI's DINOv2,
-   [`steam-BiT`](https://github.com/woctezuma/steam-BiT): retrieve games with similar store banners, using Google's Big Transfer (BiT) (input 224x224x3),
-   [`steam-BEiT`](https://github.com/woctezuma/steam-BEiT): retrieve games with similar store banners, using Microsoft's Bidirectional Encoder representation from Image Transformers (BEiT) (input 224x224x3),

### 2. Generative Adversarial Networks

-   [`google-colab`](https://github.com/woctezuma/google-colab): train a [DCGAN](https://arxiv.org/abs/1511.06434) to generate 28x28 store banners,
-   [`steam-stylegan`](https://github.com/woctezuma/steam-stylegan): train a [StyleGAN](https://arxiv.org/abs/1812.04948) to generate 128x128 store banners,
-   [`steam-stylegan2`](https://github.com/woctezuma/steam-stylegan2): train a [StyleGAN2](http://arxiv.org/abs/1912.04958) to generate 256x256 store banners.
-   [`steam-stylegan2-ada`](https://github.com/woctezuma/steam-stylegan2-ada): train a [StyleGAN2-ADA][stylegan2-ada-paper] to generate 256x256 store banners.
-   [`steam-lightweight-gan`](https://github.com/woctezuma/steam-lightweight-gan): train a ["lightweight GAN"](https://github.com/lucidrains/lightweight-gan) to generate 256x256 store banners.
-   [`steam-stylegan2-ada-pytorch`](https://github.com/woctezuma/steam-stylegan2-ada-pytorch): train a [StyleGAN2-ADA][stylegan2-ada-paper] (PyTorch) to generate 256x256 store banners.

### 3. Face detection

-   [`steam-face-detection`](https://github.com/woctezuma/steam-face-detection): detect (and count) faces on Steam store/library banners, for filtering purposes.

### 4. Search engine

-   [`steam-image-search`](https://github.com/woctezuma/steam-image-search): search for images on Steam using natural language queries.
-   [`steam-template-matching`](https://github.com/woctezuma/steam-template-matching): perform template matching with Steam store images.

## III. Store screenshots

### 1. Similarity

-   [`download-steam-screenshots`](https://github.com/woctezuma/download-steam-screenshots): retrieve games with similar store screenshots, using MobileNet (alpha 0.25, input 128x128x3).

## IV. Store reviews

### 1. Generative Language Model

-   [`sample-steam-reviews`](https://github.com/woctezuma/sample-steam-reviews): sample reviews, with different methods (including GPT-2),
-   [`sample-steam-reviews-with-gpt-2`](https://github.com/woctezuma/sample-steam-reviews-with-gpt-2): sample reviews, with the GPT-2 language model. The code is shorter and simpler.

### 2. Stats

-   [`steam-reviews`](https://github.com/woctezuma/steam-reviews): stats and sentiment analysis of reviews,
-   [`steam-cut`](https://github.com/woctezuma/steam-cut): fetch the number of reviews for Steam and non-Steam purchases,
-   [`players-vs-reviews`](https://github.com/woctezuma/players-vs-reviews): discover games with an unusual ratio of number of players vs. number of reviews.
-   [`steam-reviews-to-sales`](https://github.com/woctezuma/steam-reviews-to-sales): study the relationship between review numbers and sales of games,

## V. Scores

### 1. Rankings

-   [`hidden-gems`](https://github.com/woctezuma/hidden-gems): rank games to discover "hidden gems". NB: This lead to my contribution to [Steam250](https://steam250.com/contributors),
-   [`Steam-Bayesian-Average`](https://github.com/woctezuma/Steam-Bayesian-Average): rank games, developers and publishers,
-   [`Steam-Labs-Recommender`](https://github.com/woctezuma/steam-labs-recommender): tweak the Interactive Recommender of Steam Labs,
-   [`hidden-demos`](https://github.com/woctezuma/hidden-demos): rank games which offer a demo.

### 2. Community

-   [`metacouncil-goty`](https://github.com/woctezuma/metacouncil-goty): ranked-choice voting for Games of the Year Awards on [MetaCouncil/Steam](https://metacouncil.com) in 2018-2020,
-   [`steam-era-goty`](https://github.com/woctezuma/steam-era-goty): ranked-choice voting for Games of the Year Awards on [ResetERA/Steam](https://resetera.com) in 2017,
-   [`steam-groups`](https://github.com/woctezuma/steam-groups): descriptive stats regarding the libraries of members of a Steam group.

## VI. Store tags

-   [`match-steam-tags`](https://github.com/woctezuma/match-steam-tags)@[PyPI](https://pypi.org/project/steamtags/): download and match Steam tags with appIDs,
-   [`steam-tag-mapping`](https://github.com/woctezuma/steam-tag-mapping): visualize an embedding of Steam tags.

## VII. Miscellaneous

-   [`humble-monthly`](https://github.com/woctezuma/humble-monthly): analyze the content of Humble Monthly Bundles,
-   [`recent-sales`](https://github.com/woctezuma/recent-sales): a crude attempt at estimating Steam sales and revenue,
-   [`steam-hype`](https://github.com/woctezuma/steam-hype): query a third-party API to find upcoming Steam games with many followers,
-   [`steam-trade-finder`](https://github.com/woctezuma/steam-trade-finder): find Steam trades for a given appID,
-   [`steam-market`](https://github.com/woctezuma/steam-market): find arbitrages on the Steam Market.
-   [`steam-points-shop`](https://github.com/woctezuma/steam-points-shop): find games which have been removed from the [Steam Points Shop](https://store.steampowered.com/points/shop/).
-   [`AmongUs-DAU`](https://github.com/woctezuma/AmongUs-DAU): compute "Daily Active Users" (DAU) of Among Us from "Concurrent Connected Users" (CCU),
-   [`bundle-split`](https://github.com/woctezuma/bundle-split): fetch bundle content, then price bundle split based on prices at keyshop resellers.
-   [`steampy-buy-orders`](https://github.com/woctezuma/steampy-buy-orders): automatically set buy orders on the Steam Market with steampy. 
-   [`steam-next-fest`](https://github.com/woctezuma/steam-next-fest): fetch new demos from the Steam Next Fest, then play them as fast as possible.
-   [`add-free-licenses`](https://github.com/woctezuma/add-free-licenses): automatically add free licenses on Steam with ASF IPC.
-   [`steam-player-level-percentiles`](https://github.com/woctezuma/steam-player-level-percentiles): query and analyze percentiles of player levels on Steam.

## VIII. Data scraping

### 1. GameDataCrunch API

-   [`gamedatacrunch`](https://github.com/woctezuma/gamedatacrunch)@[PyPI](https://pypi.org/project/gamedatacrunch/): an API to download data through [GameDataCrunch API](https://www.gamedatacrunch.com/).

### 2. SteamSpy API

-   [`steamspypi`](https://github.com/woctezuma/steamspypi)@[PyPI](https://pypi.org/project/steamspypi/): an API to download data through [SteamSpy API](https://steamspy.com/api.php).

### 3. Steam API

-   [`download-steam-reviews`](https://github.com/woctezuma/download-steam-reviews)@[PyPI](https://pypi.org/project/steamreviews/): download every review for the game of your choice,
-   [`steampi`](https://github.com/woctezuma/steampi)@[PyPI](https://pypi.org/project/steampi/): download app details (including release date) through Steam API, and match names with appIDs,
-   [`steam-api`](https://github.com/woctezuma/steam-api): download a list of all appIDs through Steam API, then download their app details, create an aggregate similar to SteamSpy's (but more exhaustive), finally analyze store attributes and map tags.

NB: With `steam-api`, store descriptions can also be aggregated for [later processing](https://github.com/woctezuma/steam-portal#i-store-descriptions).

### 4. My own API

#### i) Heroku endpoints

-   [`heroku-flask-api`][my-flask-API]: serve the [matching][banner-repository-CLIP] results through an API built with Flask on Heroku,
-   [`heroku-levenshtein-api`](https://github.com/woctezuma/heroku-levenshtein-api): match game names with Levenshtein distance through an API built with Flask on Heroku,
-   [`heroku-clip`](https://github.com/woctezuma/heroku-clip): classify images through an API built with Streamlit on Heroku,

#### i) API utils

-   [`steam-svelte-autocomplete`](https://github.com/woctezuma/steam-svelte-autocomplete): auto-complete game names with Svelte,
-   [`steam-popular-appids`](https://github.com/woctezuma/steam-popular-appids): create a **short** list of popular Steam appIDs,
-   [`steam-curator-release-dates`](https://github.com/woctezuma/steam-curator-release-dates): query Steam API to reveal **hidden** release dates,

## IX. Data snapshots

-   [`steam-store-snapshots`](https://github.com/woctezuma/steam-store-snapshots): app lists,
-   [`steam-api-data`](https://github.com/woctezuma/steam-api-data): app details,
-   [`download-steam-banners-data`](https://github.com/woctezuma/download-steam-banners-data): store banners,
-   [`download-steam-screenshots-data`](https://github.com/woctezuma/download-steam-screenshots-data): store screenshots,
-   [`steam-filtered-image-data`](https://github.com/woctezuma/steam-filtered-image-data): **filtered** library images (vertical banners, logos), and the Steam-OneFace dataset,
-   [`steam-reviews-data`](https://github.com/woctezuma/steam-reviews-data): reviews,
-   [`steamspy-data`](https://github.com/woctezuma/steamspy-data): SteamSpy data snapshot,
-   [`hidden-gems-data`](https://github.com/woctezuma/hidden-gems-data): language stats for regional rankings of "hidden gems",
-   [`recent-sales-data`](https://github.com/woctezuma/recent-sales-data): aggregate of SteamSpy data between July 17th, 2017 and February 6th, 2018.

## X. Data leaks

-   [`egs-15DaysofGames`](https://github.com/woctezuma/egs-15DaysofGames): datamining of 15 Days of (free) Games on the Epic Games Store (EGS),
-   [`egs-datamining`](https://github.com/woctezuma/egs-datamining): datamining of unreleased games on the Epic Games Store (EGS),
-   [`epic-games-ratings`](https://github.com/woctezuma/epic-games-ratings): Bayesian average ratings of games on the Epic Games Store,
-   [`epic-games-achievements`](https://github.com/woctezuma/epic-games-achievements): achievements on the Epic Games Store,
-   [`epic-games-tracker`](https://github.com/woctezuma/epic-games-tracker): track the numbers of players and ratings on the Epic Games Store,
-   [`epic-games-promotion-tracker`](https://github.com/woctezuma/epic-games-promotion-tracker): track upcoming promotional offers on the Epic Games store,
-   [`epic-games-gift-tracker`](https://github.com/woctezuma/epic-games-gift-tracker): track upcoming gift wrappings on the Epic Games store,
-   [`epic-games-player-estimates`](https://github.com/woctezuma/epic-games-player-estimates): correlate the numbers of players and ratings on the Epic Games Store,
-   [`geforce-leak`](https://github.com/woctezuma/geforce-leak): datamining of Nvidia's GeForce NOW (GFN),

<!-- Definitions -->

[my-flask-API]: <https://github.com/woctezuma/heroku-flask-api>
[banner-repository-CLIP]: <https://github.com/woctezuma/steam-CLIP>
[stylegan2-ada-paper]: <https://arxiv.org/abs/2006.06676>
