# Music Discovery
Previously, music recommenders were just like your friends that shared good music with you. Now, we turn them into hipster music snobs chasing fresh new songs with data science. You can read about this project on my [blog](http://dohyunshin.com/jekyll/pixyll/2016/09/24/music-discovery/).

## Files
`hdf5_getters.py` helper function to retrieve data from Million Song Dataset  
`X.ipynb` retrieve features from the Million Song Dataset  
`Y.ipynb` retrieve vector representation of songs via collaborative filtering on data from the Echo Nest API  
`data.ipynb` combine and preprocess the data  
`model.ipynb` train the convolutional neural network  
`model.h5` the trained model saved  
`predictions.ipynb` feed songs from test set to the convnet and get predictions  
`tsne.ipynb` map the 10-dimensional song vectors to 2-dimensional tsne vectors  
`recommendation.ipynb` recommend songs based on the convnet model  
`app` an app including a d3 interactive TSNE graph with the ability to input song names

## Citation
https://papers.nips.cc/paper/5004-deep-content-based-music-recommendation.pdf
