---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Good Game English"
date: 2023
published: true
labels:
  - Robotics
  - Arduino
  - C++
summary: "My team developed a robotic mouse that won first place in the 2015 UH Micromouse competition."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

During my internship at Gen. G Esports, I led the development of an educational curriculum titled Good Game English, a unique program designed to blend language learning with gaming. This project was specifically created for middle school students attending summer sessions, and it sought to enhance their English language skills by incorporating elements from the popular game League of Legends.

The challenge was to develop a curriculum that not only met educational standards but also actively engaged students through their passion for gaming. Over the course of the internship, I worked alongside a team to create three weeks' worth of lesson plans. These lessons balanced gaming mechanics with language learning exercises, utilizing in-game terminology, character dialogue, and strategic thinking as ways to improve vocabulary, reading comprehension, and communication skills.

Each week’s lesson was designed to hit specific engagement and learning quotas, which required us to constantly revise and test new approaches to ensure maximum student participation. We implemented quizzes, team-based activities, and discussions that leveraged the social and collaborative aspects of gaming to foster teamwork and critical thinking in the classroom.

Beyond creating the curriculum, I had the opportunity to present our work during several large-scale presentations in Hawaii. These presentations were aimed at showcasing the potential of combining esports with education, and they provided a platform to highlight the positive impact of gaming in a structured, academic setting. I also addressed feedback from educators and peers to refine the curriculum further.


```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
