# eseo-sptotify-project
Ce dépôt Github contient tous le code source produit lors de la réalisation de ce projet. 

Il est organisé en partie logique représentant les différentes étapes de l'etl. L'arborescence ci-jointe illustre la structure du projet : 

Projet Spotify
├── ER_model
├── spotify_warehouse - public - streams_daily.png 
├── etl_jobs
│   ├── artists
│   └── final_data
│       ├── artist_dimension.csv
│       └── raw_data
│           ├── artist_dim_starter.csv
│           └── artists.csv
├── country
│   ├── final_data
│       ├── country_dim.csv
│       └── intermediate_data.csv
│   └── raw_data
│       ├── internet_usage.csv
│       └── WDI_data.csv
│   └── country_dim_job.ipynb
├── date
│   ├── final_data
│       ├── date_dim.csv
│   └── raw_data
│       └── date_dim_job.ipynb
├── stream
│   ├── final_data
│       ├── spotify_stream_fact.csv
│   └── raw_data
│       ├── non_correspondances.csv
│       └── spotify_streams_data_raw.csv
│       └── fact_data_cleaning_job.ipynb
├── table_creation_data_insertion
│   └── etl_job.ipynb
├── tracks
│   ├── final_data
│       ├── tracks_dim.csv
│   └── raw_data
│       ├── spotify_songs.csv
│       ├── Top_Songs_US.csv
│       ├── tracks_dim_starter.csv
│       └── tracks_features.csv
│       └── tracks_cleaning_job.ipynb
├── Power BI
│   └── power_bi_project.pbix
├── Specifications
└── Sujet

Par ailleurs, il respecte le workflow data suivant : 
![workflow_data](https://github.com/user-attachments/assets/cabbfaab-b542-445a-a2ca-5ac1c2104969)

