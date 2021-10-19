# Affective image dataset / image emotion dataset

- **IAPS**

- **Artphoto**

- **Abstract**

- **FI**

- **Twitter**

- **Emotion6 / EmotionROI**

- **GAPED**

  ****

## IAPS

The subset A of IAPS (**IAPSa**) [1] is collected from IAPS to characterize the images by a descriptive discrete emotion category. Specifically, **203 negative images and 187 positive images** are selected, and then labeled by twenty undergraduate participants. To the best of our knowledge, it is the first affective image dataset which is labeled using a discrete emotion category.



## Artphoto

**ArtPhoto** contains **806** art photos from photo-sharing sites, in which emotions are determined by the artist who uploaded the photo.

The Artphoto dataset [2] contains 806 artistic photos collected from an art sharing site. The photos are obtained by searching the site with the emotion categories as keywords. The ground truth of each image is determined by the user who uploads it.



## Abstract

**Abstract** [2] contains **228** peer-reviewed abstract paintings, including colors and textures. The  original Abstract dataset [2] consists of 280 paintings which are combinations only of color and texture. They are annotated by about 230 people, and each image is voted 14 times. For each image, the category obtaining the most number of votes is regarded as the ground truth. After filtering the images whose votes are inconclusive, 228 images are retained.



## FI

**FI** [3] is currently the largest well-labeled dataset. The original FI data set contains 90,000 noisy images collected from Flicker and Instagram by searching eight types of affective keywords. Weakly labeled images were further labeled by 225 Amazon Mechanical Turk (AMT) workers selected through qualification tests. **23,308** images with at least three votes obtained from 5 designated AMT staff will be retained.



##  Twitter I 

 **Twitter I** [4] is collected by Amazon Mechanical Turk[[1\]](#_ftn1) (AMT) staff from social networking sites and labeled as **two categories** (i.e., positive and negative), and contains **1,269 images**. We tested our method on all three subsets of Twitter I, including "five consents," "at least four consents," and "at least three consents,". "Five Agrees" means that all five AMT workers have given the same emotional label to a given image.

------

[[1\]](#_ftnref1) https://www.mturk.com/

## Emotion6

**Emotion6** [5] was created as an emotion prediction benchmark and collected from Flickr to generate **1,980 images** with six emotion categories. They assumed that the influence of each pixel on the emotion-inducing area is proportional to the number of rectangles that cover that pixel and adopt AMT to collect 15 responses to the emotion-inducing site and represent the actual situation.



## GAPED 

The Geneva affective picture database (GAPED) [6] contains **730 pictures** which are collected to make full use of visual emotion stimuli. Several specific types of negative or positive content are presented in these images. The **520 negative images, 121 positive images, and 89 neutral images** are labeled by 60 people ranging from 19 to 43 years (mean=24, STD=5.9). In addition, the continuous VA scales are rated from 0 to 100 points.

1. Negative

       - Snakes
       - Spiders
       - Human concerns
       - Animal mistreatments

2. Positive 

3. Neutral


| Categories | **Number of pictures** |
| ---------- | ---------------------- |
| Negative   | 520                    |
| Positive   | 121                    |
| Neutral    | 89                     |
| **Total**  | 730                    |

> **下载地址：**https://www.unige.ch/cisa/research/materials-and-online-research/research-material/



### GAPED 

```
[1] Mikels J A, Fredrickson B L, Larkin G R, et al. Emotional category data on images from the International Affective Picture System[J]. Behavior research methods, 2005, 37(4): 626-630.
[2] Machajdik J, Hanbury A. Affective image classification using features inspired by psychology and art theory[C]//Proceedings of the 18th ACM international conference on Multimedia. 2010: 83-92.
[3] You Q, Luo J, Jin H, et al. Building a large scale dataset for image emotion recognition: The fine print and the benchmark[C]//Proceedings of the AAAI conference on artificial intelligence. 2016, 30(1).
[4] You Q, Luo J, Jin H, et al. Robust image sentiment analysis using progressively trained and domain transferred deep networks[C]//Twenty-ninth AAAI conference on artificial intelligence. 2015.
[5] Peng K C, Chen T, Sadovnik A, et al. A mixed bag of emotions: Model, predict, and transfer emotion distributions[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2015: 860-868.
[6] Dan-Glauser E S, Scherer K R. The Geneva affective picture database (GAPED): a new 730-picture database focusing on valence and normative significance[J]. Behavior research methods, 2011, 43(2): 468-477.
```



All datasets can be obtained from Nankai CV lab:

[Nankai University](http://www.nankai.edu.cn/)  | [CV lab](https://cv.nankai.edu.cn/) | [visual sentiment analysis](http://47.111.31.20:8081/sentiment/index.html)

