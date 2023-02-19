# Music Recommender ANNOY
Music Recommender using ANNOY and Google's AudioSet

## Highlights
1. Predicts song similarity based on Audio Embedding Information
2. Approximate Nearest Neighbors used for feature similarity
3. Embedded data generated for every second of audio was pre-transformed with "IBM MAX Audio Embedding Generator" (https://github.com/IBM/MAX-Audio-Embedding-Generator)

## How to run
1. Download Google Dataset (See references section below) and place in the `./data/audioset_v1_embeddings` directory
![image](https://user-images.githubusercontent.com/87340855/219968863-8604b42c-4c5d-4852-b3ad-2d28d20b8da7.png)
2. Run `main.ipynb`

## Dependencies
- Tensorflow 2.0 (installed via pip in anaconda)
- ANNOY (https://github.com/spotify/annoy)

## Demo Images
### Input Data gets 5 video Recommendations from YouTube
![image](https://user-images.githubusercontent.com/87340855/219968727-9b0e0a42-7233-4c01-95f8-cbd262884b80.png)

## References
1. Dataset: https://research.google.com/audioset/download.html
