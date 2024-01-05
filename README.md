# README
AWS free Tier link: https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all   

Spotify Dataset link: https://www.kaggle.com/datasets/tonygordonjr/spotify-dataset-

Services used from AWS: S3, Athena, Glue, Crawler, Athena and Quicksight


Initially, the data will reside in our staging layer. We utilized AWS Glue to construct an ETL pipeline, facilitating the transfer of data from the staging layer to our data warehouse. Once the data warehouse is established, a Glue crawler is executed to generate a database and populate a table within it. Subsequently, AWS Athena is used to query the data within the table. Once the setup is complete, AWS QuickSight is used for data visualization and obtaining business insights. The dataset for this project is the Spotify 2023 dataset, comprising five CSV files: albums, artists, Spotify data, Spotify features, and Spotify tracks. The albums file contains details about albums, tracks, artists, and album release dates. The artists file includes information such as artist names, number of followers, and their genres. The Spotify data file encompasses album ID, album name, album popularity, and artist details. Additionally, the Spotify features file provides details on danceability, energy, loudness, mode, speech, liveliness, and valence of the music. Lastly, the tracks file contains track ID, track popularity, and explicit indicators.


