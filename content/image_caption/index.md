+++
title = "Image Caption Generator" 
+++

The Image Captioning feature will prompt the user for an image to process, then will generate a caption to search for depending on the image given. No posters will be used but only screenshots for better accuracy. The MS-COCO dataset will be used for this feature and the IMDB reviews for the search once caption is generated. Read more here: https://github.com/cmeza432/movie_recommender

## Deployment
Make sure to have Python Flask installed, if not already installed simply run pip install flask. Once installed, then install the MS-COCO data set here: http://cocodataset.org/#download

## Reference: 
https://www.tensorflow.org/tutorials/text/image_captioning

## Contribution:
Converting the code to work on python anywhere and caching the the files for the training process.

## Biggest Challenge 
Trying to get it to download all files without running out of space on pythonanywhere. It was overcame by limiting the size of the dataset used to get something working.

# Algorithm