+++ 
abstract = "Average daily gain is an indicator of the growth rate, feed efficiency, and current health status of livestock species including pigs. Continuous monitoring of daily gain in pigs aids producers to optimize their growth performance while ensuring animal welfare and sustainability, such as reducing stress reactions and feed waste. Computer vision has been used to predict live body weight from video images without direct handling of the pig. In most studies, videos were taken while pigs were immobilized at a weighing station or feeding area to facilitate data collection. An alternative approach is to capture videos while pigs are allowed to move freely within their own housing environment, which can be easily applied to production system as no special imaging station needs to be established. The objective of this study was to establish a computer vision system by collecting RGB-D videos to capture top-view RGB and depth images of non-restrained, growing pigs to predict their body weight over time. Over a period of 38 days, eight growers were video recorded for approximately 3 min per day, at the rate of six frames per second, and manually weighed using an electronic scale. An image-processing pipeline in Python using OpenCV was developed to process the images. Specifically, each pig within the RGB frame was segmented by a thresholding algorithm, and the contour of the pig was identified to extract its length and width. The height of a pig was estimated from the depth images captured by the infrared depth sensor. Quality control included removing pigs that were touching the fence and sitting, as well as those showing extremely distorted shape or motion blur owing to their frequent movement. Fitting all of the morphological image descriptors simultaneously in linear mixed models yielded prediction coefficients of determination of 0.72–0.98, 0.65–0.95, 0.51–0.94, and 0.49–0.93 for one-, two-, three-, and four-day ahead forecasting, respectively, of body weight in time series cross-validation. Based on the results, we conclude that our RGB-D sensor-based imaging system coupled with the Python image-processing pipeline could potentially provide an effective approach to predict the live body weight of non-restrained pigs from images."
abstract_short = ""
authors = ["__Haipeng Yu__", "Kiho Lee","and Gota Morota"]
date = "2021-01-17"
# image = ""
# image_preview = ""
math = true
publication = "Translational Animal Science"
publication_short = "Translational Animal Science"
publication_types = ["2"]
selected = false
title = "Forecasting dynamic body weight of non-restrained pigs from images using an RGB-D sensor camera"
url_code = ""
url_dataset = ""
# url_pdf = "papers/BCFA_BN.pdf"
url_project = ""
url_slides = ""
url_video = ""

[[url_custom]]
name = "DOI"
url = "https://academic.oup.com/tas/advance-article/doi/10.1093/tas/txab006/6102880"

# [[url_custom]]
# name = "PubMed"
# url = "https://www.ncbi.nlm.nih.gov/pubmed/30992319"
# 
# [[url_custom]]
# name = "EuropePMC"
# url = "http://europepmc.org/article/MED/30992319"

# [[url_custom]]
# name = "bioRxiv"
# url = "https://www.biorxiv.org/content/10.1101/2020.09.03.282335v2"
+++
