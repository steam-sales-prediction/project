## About Dataset

This dataset comprises information for various apps/videogames published on Steam. The dataset includes for each app info about its supported platforms, whether it supports steam achievements, trading cards or a workshop, and many more info. Some apps may be Demos or DLCs of others. For some of the apps, the steam analytics client "Gamalytic" was used to gather information about the app sales and user reviews.

## Dataset Information

1. **Base Game Information**
   - **AppID**: unique steam ID for the app.
   - **Name**: App's name.
   - **Supported Platforms**: a list of the supported platforms that may contain Windows, Linux or Mac support.
   - **Metacritic Score**: a score that represents the critical consensus for games.
   - **Steam Achievements Support**: whether or not the app has achievements.
   - **Steam Trading Cards Support**: whether or not the app has trading cards.
   - **Steam Workshop Support**: whether or not the app has a workshop.
   - **Genres**: a list of the app genres.
   - **Total Number of Available Achievements**
   - **Release Date**
2. **DLCs**: a file that maps app IDs with their additional downloadable content apps.
3. **Demos**: a file that maps app IDs with their available demos.
4. **Gamalytic Steam Games**
   - **steamID**
   - **Price**
   - **copiesSold (target variable)**
   - **publisherClass**
   - **reviewScore**
   - **aiContent**