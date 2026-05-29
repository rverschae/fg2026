---
title: "Tutorial: Face and gesture recognition using event-based cameras"
author_profile: false
---

# Tutorial: Face and gesture recognition using event-based cameras

# [FG2026](https://fg2026.ieee-biometrics.org/) Tutorial, Kyoto, Japan

## Tutorial description
Event-based cameras are a recently introduced technology that asynchronously senses light intensity changes at the individual pixel level. They are increasingly being applied to various recognition problems of interest to the computer vision community, primarily because they continuously encode sparse appearance and motion information at very high speeds, with low latency, and across a high dynamic range. Over the last few years, interest in these devices has surged, particularly regarding their application to face and gesture analysis. Event-based cameras are uniquely suited for these tasks due to their high temporal resolution and high dynamic range, which eliminate motion blur and accommodate challenging illumination conditions. Moreover, they enable the analysis of subtle facial changes within a continuous data stream.
In this context, this tutorial provides an introductory yet comprehensive overview of event-based cameras and discusses their application to face and gesture recognition. The tutorial is organized into three parts. First, we provide an overview of event cameras, existing sensors, and the problems to which they have been applied, ranging from low-level vision (e.g., optical flow, tracking, and feature detection) to high-level vision (e.g., reconstruction, segmentation, and recognition). Second, we discuss existing techniques for processing event streams, including learning-based approaches. Finally, we present an overview of recent work on face and gesture recognition using event-based cameras, including a discussion of available datasets, current methodologies, and open research directions.
This tutorial is intended both for researchers with no prior experience with event-based cameras and for those who have worked with them in the past but wish to review recent advances in the field.


## Schedule:
### 13:30-15:00  Opening and Basics of Event-based cameras
- 13:30 — Opening & Introduction 
- 13:50 — Fundamentals of event-based cameras 
- 14:10 — Application examples 
- 14:30 - 14:40 Break
- 14:40 — Event data representations and visualization 

### 15:00-16:10 Event-based cameras for Face and Gesture Recognition
- 15:00 — Intro Event-based cameras for Face and Gesture 
- 15:10 — Event-based FG datasets and data generation 
- 15:20 — Data processing and classification 
- 15:30-15:40 Break
- 15:40 — Recent results on Event-based Face & Gesture recognition 

### 16:10-16:20 Future Perspectives and Closing Remarks 

## Tutorial Slides:

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vThK8uV0AtfjIDKUbmOEcUcGRKuyaoeqa1TU51oqBnbymL7CM_9XKVakJBnUdPXXNbano65Tg1L7_d9/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


## Requirements  (e.g., facilities, Internet access, etc.) and Additional Information:
- No special requirements.
- Primary target audience: The tutorial is intended for researchers with no prior experience with event-based cameras, as well as researchers that have worked with event-based cameras in the past but who want to review recent advances in this area.
- Background: we assume knowledge in image processing, computer vision, basics of Deep Learning, and basics of signal processing.
- Slides and prepared material will be made available.

## Organizers / Lecturers: 
### Rodrigo Verschae
- Email: rodrigo@verschae.org
- Web: [http://rodrigo.verschae.org](http://rodrigo.verschae.org)
- [https://scholar.google.com/citations?user=Fv1lZNkAAAAJ&hl=en](https://scholar.google.com/citations?user=Fv1lZNkAAAAJ&hl=en)
- Affiliation: Universitad Tecnica Universidad Técnica Federico Santa María, Chile
- Short bio: Rodrigo Verschae is currently with the Department of Informatics, Universitad Tecnica Universidad Técnica Federico Santa María, Chile. Doctor in Electrical Engineering and Master in Applied Maths, he is interested in Computer Vision, Machine Learning, and Robotics with experience in various application areas. Rodrigo has been Director and Associate Professor at the Institute of Engineering Sciences, Universidad de O’Higgins, assistant professor at Kyoto University, Japan (2015-2018), a postdoctoral fellow at the Advanced Mining Technology Center AMTC (2011-2013), a research fellow at the Kyushu Institute of Technology, Japan (2009-2011), and an associated researcher at Fraunhofer IPK-Institute, Germany (2004-2005), among others.

### Daniel Acevedo
- Email: dacevedo@dc.uba.ar
- Web: [https://scholar.google.com/citations?user=1Yv2P6oAAAAJ&hl=en](https://scholar.google.com/citations?user=1Yv2P6oAAAAJ&hl=en)
- Affiliation: Universidad de Buenos Aires. Facultad de Ciencias Exactas y Naturales. Departamento de Computación. Buenos Aires, Argentina.
- Short bio: Daniel Acevedo is currently an assistant researcher at the ICC (Instituto de Ciencias de la Computación) part of UBA (University of Buenos Aires) and CONICET (Consejo Nacional de Investigaciones Científicas y Técnicas). Daniel also works at the Department of Computer Sciences (FCEyN - UBA) as a professor. His research mainly focuses on digital image processing topics: facial expression recognition, texture analysis and retrieval. As well, he has worked on satellite data compression.

### Nicolas Mastropasqua:
- Email: nmastropasqua@dc.uba.ar
- Web: [https://scholar.google.com/citations?user=m-mTz2kAAAAJ&hl=en](https://scholar.google.com/citations?user=m-mTz2kAAAAJ&hl=en)
- Affiliation: Universidad de Buenos Aires. Facultad de Ciencias Exactas y Naturales. Departamento de Computación. Buenos Aires, Argentina.
- Short bio: Nicolas Mastropasqua is a Ph.D. student in Computer Science at Universidad de Buenos Aires. He received the degree in Computer Science from the Facultad de Ciencias Exactas y Naturales, Universidad de Buenos Aires in 2023. His research interests include computer vision, neuromorphic vision, facial expression analysis, and driver monitoring systems.

### Ignacio Bugueno-Cordova:
- Email: i.bugueno@ieee.org
- Web: [https://ibugueno.github.io/](https://ibugueno.github.io/)
- Affiliation: Universidad de O’Higgins
- Short bio: Ignacio Bugueno-Cordova obtained his Electrical Engineering degree in 2018 and his Master of Science degree in 2025, both from Universidad de Chile, Santiago, Chile. He has been a research assistant at the Robotics and Intelligent Systems Laboratory at Universidad de O’Higgins since 2020. In 2025, he was awarded an IEEE CIS Graduate Student Research Grant to conduct a research stay at the L3S Research Center, Hanover, Germany. His research interests include artificial intelligence, computer/event vision, deep learning, IoT, telecommunications, and robotics.

### Experience
The instructors possess extensive experience in face and gesture detection and recognition problems using event-based cameras [1–5] (see the list of related publications at the end of this document). They also have a strong background in facial recognition, detection, and analysis using standard RGB cameras. Furthermore, the instructors have previously delivered tutorials and talks on this topic, including a tutorial titled “Introduction to Face and Gesture Recognition Using Event-Based Cameras” at the 15th IEEE International Conference on Automatic Face and Gesture Recognition (FG 2020). This updated tutorial builds upon the 2020 edition, incorporating the substantial body of work that has been published over the last few years.

## The main instructors have presented tutorials/talks in related computer vision topics in the following international events: 
- IEEE RAS ICRA 2025 LA@Chile HANDS-ON: “Gentle introduction to Event-based Robot Vision” given at the satellite event of the ICRA 2025 conference sponsored by IEEE RAS.
- LACORO 2024 HANDS-ON: “Computer/Event vision and deep learning for dynamic environments” given at the 3rd Latin American Summer School on Robotics.
- Invited spotlight speaker at the KHIPU AI conference, Santiago, Chile, March 2025. 
- Tutorial on “Introduction to face and gesture recognition using event-based cameras" given at the 15th IEEE International Conference on Automatic Face and Gesture Recognition, November, 2020 (online).
- Tutorial presentation on “Deep Photovoltaic Prediction” at the IEEE RAS Summer School on Deep Learning for Robot Vision, Santiago, Chile, December 2019.
- Tutorial presentation on "Efficient object detection" at the IEEE RAS Summer School on Robot Vision, Santiago, Chile, December 2012 Tutorial presentation on "Multiclass object detection" at the IEEE LA-RAS Summer School, Santiago, Chile, December 2010
- Tutorial presentation on "Face detection” at the IEEE LA-RAS Summer School, Santiago, Chile December 2006.

## FG + Event-based Related Publications authored by the lectures
- [1] R Verschae, I Bugueno-Cordova, "[evTransFER: A Transfer Learning Framework for Event-based Facial Expression Recognition](https://www.sciencedirect.com/science/article/abs/pii/S092523122600038X)", Neurocomputing, 2026, 132641. 
- [2] N Mastropasqua, I Bugueno-Cordova, R Verschae, D Acevedo, Pablo Negri, Maria Elena Buemi, "Event-based facial microexpression analysis using Spiking Neural Networks", ICPRS, 2025
- [3] N Mastropasqua, D Acevedo, I Bugueno-Cordova, R Verschae, "[Exploring spatial-temporal dynamics in event-based facial microexpression analysis](https://arxiv.org/abs/2508.11988)", 2nd Workshop on Neuromorphic Vision ICCV, 2025
- [4] R Verschae, I Bugueno-Cordova, "[Event-based Gesture and Facial Expression Recognition: A Comparative Analysis](https://ieeexplore.ieee.org/document/10298106/)", in IEEE Access, vol. 11, pp. 121269-121283, 2023, doi: 10.1109/ACCESS.2023.3328220. 
- [5] I Bugueno-Cordova, R Verschae “Event-based Facial Expression Recognition", in LatinX in CV Workshop, 2023 International Conference on Computer Vision
