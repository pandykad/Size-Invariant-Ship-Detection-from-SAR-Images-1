# Size Invariant Ship Detection from SAR Images

### Overview

- Ship detection from remote sensing imagery is a crucial application for maritime security. When talking about maritime security, we have to consider many things like traffic surveillance, protection against illegal fisheries, oil discharge control, sea pollution monitoring, etc.
- Automated Identification System (AIS) are very effective at monitoring ships which are legally required to install a VHF transponder, but fail to detect those which are not, and those which disconnect their transponder.
- So how do you detect these uncooperative ships? The solution is using: Synthetic Aperture Radar (SAR)

[![Demo](http://www.youtube.com/watch?v=9pqrjH9NmlM "Demo")

(http://img.youtube.com/vi/9pqrjH9NmlM/0.jpg)

<iframe width="560" height="315" src="https://www.youtube.com/embed/9pqrjH9NmlM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[![Everything Is AWESOME](https://yt-embed.herokuapp.com/embed?v=[9pqrjH9NmlM])](http://www.youtube.com/watch?v=9pqrjH9NmlM "Everything Is AWESOME")

<iframe  title="YouTube video player" width="480" height="390" src="http://www.youtube.com/watch?v=9pqrjH9NmlM?autoplay=1" frameborder="0" allowfullscreen></iframe>


## A Deep Learning based approach to detect ships from satellite images. 

Implementation of this repository has been kept confidential for the time being due to confidentiality agreement but these are some of the outputs from the Experimentaion :

### Youtube: https://www.youtube.com/watch?v=9pqrjH9NmlM 

Sample 1 :  
Confidence: Large Ship = 99%, Small Ship Moving = 35%  
Total Execution Time: 40.50ms  
Computation Resources used: 65.33 BFLOPS  
<img src="Result%20Images/sample_1.png" width="400">  

Sample 2 :  
Confidence: Small Ship Moving = 97%, Small Ship Moving = 98%   
Total Execution Time: 40.62ms  
Computation Resources used: 65.33 BFLOPS  
<img src="Result%20Images/sample_2.png" width="400">  

Sample 3 :  
Confidence: Small Ship Moving = 40%, Small Ship Moving = 80%, Medium Ship Moving = 75%, Medium Ship Not Moving = 86%  
Total Execution Time: 40.66ms  
Computation Resources used: 65.33 BFLOPS  
<img src="Result%20Images/sample_3.png" width="400">  

Sample 4 :    
Confidence: Large Ship = 99%  
Total Execution Time: 40.67ms  
Computation Resources used: 65.33 BFLOPS  
<img src="Result%20Images/sample_4.png" width="400">  

Sample 5 :  
Confidence: 99.3%  
<img src="Result%20Images/sample_5.png" width="400">  

Sample 6 :  
Confidence: 94%  
<img src="Result%20Images/sample_6.png" width="400">  

Sample 7 :  
Multiple Ship Detection    
<img src="Result%20Images/sample_7.png" width="400">  
  
  
## Happy Experimentation !
