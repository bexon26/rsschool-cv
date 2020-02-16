### Yauheni Tsydrankou ###

#### Contact Info: ####
* **Telephone number:** 
 +375333718187
* **Telegram:** evgeniy tsydrenkov
* **E-mail:** bexonn80@gmail.com
* **Github:** https://github.com/bexon26
* **English:** Pre-intermediate (А2).


I am a beginner web-developer. My goal is to change jobs and do what I love, helping other people solve their problems.


#### Skills: #### 
JavaScript, HTML, CSS, ModX, Bootstrap, Git
#### Tools: #### 
GIT, VS Code, Photoshop, Adobe Illustrator

**Code Exaples:**
```javascript
var photos = cardElement.querySelector('.popup__photos');

  if (card.offer.photos.length) {
    for (var i = 0; i < card.offer.photos.length; i++) {
      if (!i) {
        photos.children[0].src = card.offer.photos[0];
      } else {
        var photo = photos.children[0].cloneNode(true);
        photo.src = card.offer.photos[i];
        photos.appendChild(photo);
      }
    }
  } else {
    photos.classList.add('visually-hidden');
  }

  var avatar = cardElement.querySelector('.popup__avatar');
  if (card.author.avatar) {
    avatar.textContent = card.author.avatar;
  } else {
    avatar.classList.add('visually-hidden');
  }

  return cardElement;
};
```
Experience
I have experience creating an online store on CMS ModX Revolution

Education
Faculty of Physics, specialty - Automated Systems of Information Processing, Univerversity of Name of Francisca Scorina 2014-2019.

HTML basics course
CSS course 
HTML Academy: JavaScript level 1, Mimo: basis html, css, js