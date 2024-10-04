---
layout: home
author_profile: true
classes: wide smaller-font
---

{% capture custom_content %}
### About me
<div style="text-align: justify; font-size: 16px;">
I am a Ph.D. candidate and university fellow in Electrical Engineering at the University of Rhode Island, specializing in Reinforcement Learning, Computer Vision, and Signal Processing. I graduated from K. N. Toosi University of Technology, Iran, in 2020 with a degree in Electrical Engineering. During my bachelor studies, beyond advancing my programming skills and knowledge of working with various types of devices and sensors, I also explored the computer science field specifically artificial intelligence. Later, interested in advanced knowledge beyond traditional electrical engineering research, I decided to pursue a master's in Computer Engineering with a focus on AI at Sharif University of Technology. During my studies, I focused on learning the fundamentals of artificial intelligence across various fields, including computer vision, reinforcement learning, and data analysis. I also conducted research on advanced signal processing techniques in time-series data analysis, which allowed me to further build my expertise in the field. 

My multidisciplinary background in electrical engineering and artificial intelligence has prepared me well for my current doctoral studies. After winning a university fellowship, I began my PhD at the University of Rhode Island, where I am working on medical robotics and brain-computer interface (BCI) applications. My current research focuses on autonomous and shared autonomy systems, human-in-the-loop intelligent agents, and advanced signal processing techniques for electroencephalography (EEG) analysis and interpretation. I design multimodal AI frameworks that integrate biosignals with computer vision to enhance shared autonomy systems specifically for individuals with disabilities. By incorporating environmental perception data alongside limited user inputs, I train reinforcement learning agents to interpret human intentions and execute robotic tasks such as reach-to-grasp or object manipulation, utilizing 6D pose estimation. I am currently leading NSF/NIH-funded projects in human-centered AI for assistive and rehabilitation robotics.
</div>
{: .small}

### Research interest
- Robotics
- Human-robot interaction
- Reinforcement Learning
- Computer Vision
- Signal Processing
- Brain-Computer Interfaces (BCI)
{: .small}
{% endcapture %}

{{ custom_content | markdownify }}
 ---
<video width="600" height="400" controls>
    <source src="{{ '/assets/videos/sim2real.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag. You can <a href="{{ '/assets/videos/sim2real.mp4' | relative_url }}">download the video</a> instead.
</video>


![GIF]({{ '/assets/videos/amplification_demo.gif' | relative_url }})


<img src="{{ '/assets/videos/ClickMove_demo.gif' | relative_url }}" alt="Project 1 GIF" width="600" height="auto">


![Image]({{ '/assets/images/wavelet.png' | relative_url }})

![Image]({{ '/assets/images/bispectrum.png' | relative_url }})

![Image]({{ '/assets/images/labeling.png' | relative_url }})


