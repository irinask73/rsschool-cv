# Irina Skidan		
## Contacts
**Email:** irinaskid@gmail.com \
**Telegram:** @IrinaSkidan \
**Phone:** +38093 495 62 58	
## Summary
My goal is to become a **front-end developer with React**. 

I am a purposeful person who can work both in a team and independently. My strengths are the ability to learn and apply new knowledge in practice. I have experience in website layout.
## Skills
* HTML;
* CSS;
* Sass (SCSS);
* BEM;
* Git;
* Gulp;
* Wordpress;
* Initial JS;
* Photoshop, Figma.
## Code examples

//implementation of an accordion menu with JS
```
const accordionItems = document.querySelector("[data-accordion='accordion__items']");
const accordionButtons = accordionItems.querySelectorAll('li > div');

for (let i = 0; i < accordionButtons.length; i++) {
accordionButtons[i].addEventListener('click', function () {
const isTabActive = accordionButtons[i].nextElementSibling.classList.contains('active');
for (let j = 0; j < accordionButtons.length; j++) {
if (isTabActive === false) {
accordionButtons[j].classList.remove('active')
}
}
accordionButtons[i].nextElementSibling.classList.toggle('active');
// if the same element has a class 'active' then on click remove the class 'active'
});
}
```
## Experience
As part of the training course responsive market place [here](https://github.com/irinask73/moderno.git) and travel site [here](https://github.com/irinask73/messinia.gitt) using HTML, CSS, JS, Jquery.
## Education
I have higher education in engineering and economics. A year ago I decided to change the type of activity. I’m self-studying in the IT-sphere.
* FreeCodeCamp. Responsive Web Design/ Javascript Algorithms and Data Structures;
* Markup Developer by Vadim Prokopchuk;
* Now I am studying learn.javscript.ru
## Languages
* Deutch: A2;
* Englisch: basic knowledge allowing to understand technical documentation. Now I am studying at intensive courses at the Churchill club [here](http://english-webinar.ru/).
