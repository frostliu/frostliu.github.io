# **Codes&Dataset**  

---
## JAFFE Gabor Features  

JAFFE database contains 213 images of 7 facial expressions (6 basic facial expressions + 1 neutral) posed by 10 Japanese female models. Each image has been rated on 6 emotion adjectives by 60 Japanese subjects. The original dataset can be found here.  

In this processed dataset, the Gabor features are exptracted on the selected 122 facial points of which are normalized and cropped images of JAFFE of 120×96 with the eyes and nose of all images in the same horizontal lines respectively.  

Gabor datafile is a .mat file that can be easily loaded in MatLab, and it contains some variables including ‘ per’, ‘exp’, ‘pos’, ‘gab1′ and ‘gab2′. The definition of the variables is as follows. A vdisk mirror of the data file is here.  

* **per：** the label of each person(1-KA, 2-KL, 3-KM, 4-KR, 5-MK, 6-NA, 7-NM, 8-TM, 9-UY, 10-YM)  
* **exp：** the label of each expression (1-AN, 2-DI, 3-FE, 4-HA, 5-NE, 6-SA, 7-SU)  
* **pos：** the position of selected facial points.  
* **gab1：** The Gabor feature of the extracted points which each row presents the Gabor feature of one expression image.(Amplitude of Gabor feature is used here. five scales and eight orientations of Gabor nuclears are used)
* **gab2：** The Gabor feature of the extracted points after nomalizing each vector.(Amplitude of Gabor feature is used here)  


Please cite the following papers when using the processed data sets. We appreciate it very much.  

* Weifeng Liu, Caifeng Song, Yanjiang Wang, Facial Expression Recognition Based on Discriminative Dictionary Learning, ICPR2012, Tsukuba Science City, Japan, 2012, pp. 1839-1842.  
* Weifeng Liu, Caifeng Song, Yanjiang Wang, Lu Jia, Facial Expression Recognition Based on Gabor Features and Sparse Representation, ICARCV2012, Guangzhou, China, 2012, pp.1402-1406.  


Download: [Gabor_JAFFE.rar GoogleSites](https://sites.google.com/site/weifengliusite/code-dataset/Gabor_JAFFE.rar?attredirects=0&d=1)
