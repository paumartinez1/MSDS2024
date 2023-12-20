# Harmony in Diversity: Redefining the Spotify Journey Through Musical Archetypes
## Authors
Paula Martinez, Anish Pati, Richard Rian, Jeremiah Soliman, James Zabala

## Project Description
In the realm of music recommendation, current methods typically study the listening activity of a user to generate song suggestions. However, these approaches lack a nuanced understanding of the music style that the user prefers. Our objective is to delve into these nuances and innovate music recommendations by introducing a more intricate understanding of individual musical preferences. This project culminates in the creation of distinctive musical archetypes for Spotify users, which could serve as the foundation for the generation of personalized song playlists based on these archetypes.

## Solution Abstract
Our solution involves leveraging the Spotify API as a foundation. The first step is to create a pool of songs and extract the audio features of each song—such as danceability, energy, and tempo. Using dimensionality reduction techniques, particularly through Principal Component Analysis, we constructed 16 unique musical archetypes that encapsulate the prevailing characteristics of this song collection. 

As a prototype, we gathered data on the top 50 tracks from at least 10 students in the MSDS Full-Time Cohort. For each student’s track, we determined the dominant archetype based on PCA. The existing song database, each tagged with a specific archetype, enabled us to assign a principal archetype to each user, which is the most frequently occurring archetype within their top tracks.

## What's Next?
Playlists tailored to each archetype could be generated using an information retrieval approach. This aims to enhance the music discovery journey for the user. Archetype compatibility is also an interesting exploration to introduce a novel dynamics within the Spotify and music landscape, enriching the user's listening experience with interconnected musical preferences.
