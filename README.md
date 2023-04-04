# Investigating Guest Stars in The Office
Project Description
Trong dự án này, chúng ta khám phá xem:
Những ngôi sao khách mời nào sẽ xuất hiện trong tập nổi tiếng nhất của "The Office", bằng cách sử dụng mọi thứ từ list và vòng lặp cho đến pandas và matplotlib.

![image](https://user-images.githubusercontent.com/124687836/229759265-1513003a-9bcc-4dd5-a1e5-93c06c27a90a.png)

The Office! What started as a British mockumentary series about office culture in 2001 has since spawned ten other variants across the world, including an Israeli version (2010-13), a Hindi version (2019-), and even a French Canadian variant (2006-2007). Of all these iterations (including the original), the American series has been the longest-running, spanning 201 episodes over nine seasons.

In this notebook, we will take a look at a dataset of The Office episodes, and try to understand how the popularity and quality of the series varied over time. To do so, we will use the following dataset: datasets/office_episodes.csv, which was downloaded from Kaggle here.

This dataset contains information on a variety of characteristics of each episode. In detail, these are:

datasets/office_episodes.csv
episode_number: Canonical episode number.
season: Season in which the episode appeared.
episode_title: Title of the episode.
description: Description of the episode.
ratings: Average IMDB rating.
votes: Number of votes.
viewership_mil: Number of US viewers in millions.
duration: Duration in number of minutes.
release_date: Airdate.
guest_stars: Guest stars in the episode (if any).
director: Director of the episode.
writers: Writers of the episode.
has_guests: True/False column for whether the episode contained guest stars.
scaled_ratings: The ratings scaled from 0 (worst-reviewed) to 1 (best-reviewed).
