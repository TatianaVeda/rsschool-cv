## Junior Frontend Developer 

# Tatiana Vedishcheva     # CV 
*************************************
## Contacts 
Location: 02680 Espoo, Finland  
tvvedishcheva@gmail.com  
https://github.com/TatianaVeda  
https://www.linkedin.com/in/tatiana-vedishcheva/  
https://tvvedishcheva.wixsite.com/portfolio  
***********************************************************

## SUMMARY
I am inspired in creating or improving useful and convenient web services in Finland. I am passionate about solving complex tasks that help people to make the activity and cognition of life savvier, clearer, and more productive.  
My interest in mathematics, deep focus, analytical and critical thinking, and the ability to communicate easily with people and to understand their needs put me in a meeting position between computers and the human world.  
Testing and user-oriented software are the areas that are of particular interest and importance to me. I am good at structuring information, constantly striving to improve my work, and paying attention to detail.   
I have 10 years of working with texts and people to better understand each other, as well as work experience in a large bank in Russia (Sberbank), the Finnish Central Association of Russian Speakers and Omnia's Communications and Marketing Department in Finland.


## TECH SKILLS 
VS Code, HTML, CSS  
Basics of JavaScript, Python  
Git, GitHub  
WordPress, Wix,   
Figma, Canva  
Notes, Miro, Slack  
Adobe Photoshop, Gimp, CorelDraw, SpeedTree (3D), Filmora  

## STRENGTHS
Analytical mindset and a results-oriented approach  
Empathy, humor, imagination, questioning  
Visual eye, conscientious, detail-oriented  

## Code example:
[Sidebar](https://codepen.io/tatianaveda/pen/QWrmJRR)
```
const upBtn = document.querySelector('.up-button')
const downBtn = document.querySelector('.down-button')
const sidebar = document.querySelector('.sidebar')

const container = document.querySelector('.container')

const mainSlide = document.querySelector('.main-slide')
const slidesCount  = mainSlide.querySelectorAll('div').length

let activeSlideIndex  = 0

sidebar.style.top = `-${(slidesCount - 1)*100}vh`
upBtn.addEventListener('click', () => {
changeSlide('up')
})

downBtn.addEventListener('click', () => {
changeSlide('down')  
})

function changeSlide(direction) {
  if (direction === 'up') 
  {
    activeSlideIndex++
    if (activeSlideIndex === slidesCount)
    {
      activeSlideIndex = 0
    }
  } else if (direction === 'down') {
    activeSlideIndex--
      if (activeSlideIndex < 0) {
        activeSlideIndex = slidesCount - 1
     }
  }
  
 const height = container.clientHeight
 mainSlide.style.transform = `translateY(-${activeSlideIndex * height}px)`
 
 sidebar.style.transform = `translateY(${activeSlideIndex * height}px)`
}
```

## Experience

### 2021  The Interactive Interface concept for the Smart Greenhouse, The SocialBlock project   
[FIGMA](https://www.figma.com/proto/HzVbcaRZsmH4UO7X494OpK/Display?kind=&node-id=300-2859&page-id=0%3A1&scaling=scale-down)  
### 2020   
Assistant project manager, ZOAN Oy
- defining project objectives, requirements, Asana
- preparing the tasks&resources for the product team, Slack  

Internship in Communication and marketing service, Omnia
- mockup designing, updating concept  for the lesson teacher's site: questionnaire, interview, analysis and preparation of new concept  
### 2018   
Content manager in Enray project (Autodesk Revit Rendering App)
- logo creation, the app’s UI improving
- 3D modeling in Speedtree  
### 2014 - 2015, 1999 - 2003   
Senior PR-specialist, Sberbank, Russia

## Education, courses:
### Education
2004 -       Marketing, RIMA-A, Hogeschool Inholland/University of Applied Sciences, Russia  
1999 -       Master's degree in Journalism, Ural State University, Russia

### Courses:
* Human-Centered Product Development, Tampere University of Applied Science (completed 2021) 
<img width="562" alt="image" src="https://github.com/TatianaVeda/rsschool-cv/assets/33755571/dd4c0215-10e3-4bfb-a703-6df075348204">
 
* IT support basics, Coursera (completed 2023)   
* JavaScript,  Udemy (in progress)  
* JavaScript/Front-end, Udemy (in progress)  

## Languages
- English - Intermediate (B1.2)  
- Finnish - Intermediate (YKI-testi keskitaso 3)  
- Russian - Native  
- German - Basic  


