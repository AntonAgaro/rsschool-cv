# My CV
## My name and contacts
Anton Agaronov, 27 years old.  
Adress: 410053, Russian Federation, Saratov, 5th Saratov passage, 1.   
Phone: +7 906 317 35 17.  
E-mail: agaronov.anton@yandex.ru.   
## About me
I graduated from Saratov State Academy of Law in 2015.   
I worked lawyer 5 years. Last 3 years I was engaged private legal practice.   
In 2020 I decided to change profession to Frontend JavaScript developer, because I really interest how computers and Internet work, web-sites and application development. I want to develop web-sites and application myself.   
Besides, I very glad that profession developer gives me opportunity to use English language in my work and I can learn this language very well.    
I started self-study, had learned html and CSS. Then I took web-development courses on Udemy. Then I started to study JavaScript by Udemy’s courses and continue study to this day.   
When I worked lawyer, I had developed my own web-site for advertisement. I used WordPress for it. 
After completed web-development courses I had developed landing by layout with some interactive elements like a modal window, slider, page up button, nav-panel.  
It can be seen by link https://github.com/AntonAgaro/layout1. 
## My skills
I use Visual Studio Code for writing code. I can use html, CSS, JavaScript, Sass, Scss for develop web-sites. 
## My code example
For example, below is my code which allow modal window append when button clicked:  
``` 
const btn = document.querySelectorAll('[data-modal]'),
      modalWindow = document.querySelector('.overlay'),
      close = document.querySelector('.modal__close');
function openModal() {
    modalWindow.classList.add('active');
            } 
function closeModal() {
    modalWindow.classList.remove('active');
            }
 btn.forEach(btn => {
    btn.addEventListener('click', openModal);
            });
 close.addEventListener('click', closeModal);
 modalWindow.addEventListener('click', closeModal);
```  
## Work Experience
https://github.com/AntonAgaro/layout1  
## Education
Courses: Web-developer courses 2021 33.5 total hours by Udemy, certificate from 18 February 2021. 
## English level
My English level is A2 
