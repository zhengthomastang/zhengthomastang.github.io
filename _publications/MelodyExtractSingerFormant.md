---
title: "Melody Extraction from Polyphonic Audio of Western Opera: A Method Based on Detection of the Singer’s Formant"
collection: publications
permalink: /publication/MelodyExtractSingerFormant
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2014-06-27
venue: "2014 International Society for Music Information Retrieval Conference"
paperurl: "http://www.terasoft.com.tw/conf/ismir2014/proceedings/T029_329_Paper.pdf"
citation: '<b>Zheng Tang</b> and Dawn AA Black. "Melody Extraction from Polyphonic Audio of Western Opera: A Method Based on Detection of the Singer’s Formant". <i>2014 International Society for Music Information Retrieval Conference (ISMIR 2014)</i>. pp. 161-166. 2014.'
---
## Abstract
Current melody extraction approaches perform poorly on the genre of opera. The singer’s formant is defined as a prominent spectral-envelope peak around 3 kHz found in the singing of professional Western opera singers. In this project we introduce a novel melody extraction algorithm based on this feature for opera signals. At the front end, it automatically detects the singer’s formant according to the Long-Term Average Spectrum (LTAS). This detection function is also applied to the short-term spectrum in each frame to determine the melody. The Fan Chirp Transform (FChT) [4] is used to compute pitch salience as its high time-frequency resolution overcomes the difficulties introduced by vibrato. Subharmonic attenuation is adopted to handle octave errors which are common in opera vocals. We improve the FChT algorithm so that it is capable of correcting outliers in pitch detection. The performance of our method is compared to 5 state-of-the-art melody extraction algorithms on a newly created dataset and parts of the ADC2004 dataset. Our algorithm achieves an accuracy of 87.5% in singer’s formant detection. In the evaluation of melody extraction, it has the best performance in voicing detection (91.6%), voicing false alarm (5.3%) and overall accuracy (82.3%). 


## Honor
* ISMIR 2014 Student Travel Grant


## Citation
@inproceedings{Tang14MelodyExtractSingerFormant,  
author = {Zheng Tang and Dawn A. A. Black},  
title = {Melody extraction from polyphonic audio of western opera: {A} method based on detection of the singer's formant},  
booktitle = {Proc. ISMIR},  
pages = {161--166},  
address = {Taipei, Taiwan},  
year = {2014}  
}