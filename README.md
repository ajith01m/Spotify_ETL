# Spotify_ETL
This Project is basically extracting the track details of global top from Spotify daily and store the API response in S3 in AWS.
Post that the raw files are processed and transformed into clean and saved in processed folder in same s3 bucket .
These whole process is automated to trigger every day. 

For trigger used Amazon Event Bridge service .
