# ADA-edu-data-processing

## Overview
This repository contains data and resources related to the ADA educational data processing project. The necessary files are hosted in a shared Google Drive folder, accessible at the following link:

[Google Drive: ADA-edu-data-processing](https://drive.google.com/drive/folders/17GTrGzVLX6rv7BiiCdOtJ75sq7MKwkrG)

## Contents
Within the `edu-data.zip` archive, the following key files are included:

- `education_data._raw_yt_metadata.jsonl.csv`
- `education_data._raw_yt_metadata.jsonl_no_description.csv`
- `education_channel_with_country.csv`
- `other_channel_with_country.csv`
- `video_with_channelcountry.csv`

The `education_data._raw_yt_metadata.jsonl.csv` and `education_data._raw_yt_metadata.jsonl_no_description.csv`contains all videos with education category. The `education_channel_with_country.csv`, `other_channel_with_country.csv` are derived from `__mini___raw_df_channels_100k.tsv`, which is the sample of the raw channel dataset. `video_with_channelcountry.csv` is the obtained by left-joining the `education_data._raw_yt_metadata.jsonl.csv` and `education_channel_with_country.csv`
