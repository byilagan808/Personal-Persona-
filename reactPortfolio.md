---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "React Portfolio"
date: Feb 2024
published: true
labels:
  - JavaSript
  - HTML
  - CSS
  - React
  - Bootstrap
  - Github
  - Netlify
summary: "Utilized React to implement reusable React components, Used bootstrap for clean and modern styling, Holds all of my professional information & demonstrates experience.
"
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

For my portfolio website project in February 2024, I created a comprehensive platform to highlight my professional background, skills, and achievements. I structured and styled the site using  technologies such as JavaScript, HTML, and CSS. Using React, I developed reusable components that made the website easier to maintain and scale. I used Bootstrap to create a clean, modern, and responsive design that looks great on all devices and screen sizes. I also used GitHub for version control to keep the project organized, and I hosted the website on Netlify for easy access. This project demonstrates my ability to create professional web applications with modern development practices.

Here is some code that illustrates how we read values from the line sensors:

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
