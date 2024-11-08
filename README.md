# ADA-edu-data-processing

## Overview
This repository contains data and resources related to the ADA educational data processing project. The necessary files are hosted in a shared Google Drive folder, accessible at the following link:

[Google Drive: ADA-edu-data-processing](https://drive.google.com/drive/folders/17GTrGzVLX6rv7BiiCdOtJ75sq7MKwkrG)

## Contents
Within the `edu-data.zip` archive, the following key files are included:

- `education_data._raw_yt_metadata.jsonl.csv` - contains all videos with education category.
- `education_data._raw_yt_metadata.jsonl_no_description.csv` - contains all videos with education category, without description
- `education_channel_with_country.csv` - channel data with education category, obtained by `__mini___raw_df_channels_100k.tsv` and YouTube API
- `other_channel_with_country.csv` - channel data with categories other than education, obtained by `__mini___raw_df_channels_100k.tsv` and YouTube API
- `video_with_channelcountry.csv` - videos with country data, obtained by left-joining `education_data._raw_yt_metadata.jsonl_no_description.csv` and `education_channel_with_country.csv`


