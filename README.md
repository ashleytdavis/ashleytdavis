## 👋 Hi there! 

```SQL
CREATE TABLE me (
  id INT AUTO_INCREMENT PRIMARY KEY,
  firstName VARCHAR(30),
  lastName VARCHAR(30),
  school VARCHAR(100),
  degree VARCHAR(200),
  email NOT NULL VARCHAR(100)
);

CREATE TABLE hobbies (
    hobby_id INT AUTO_INCREMENT PRIMARY KEY,
    id INT NOT NULL,            
    hobby VARCHAR(255) NOT NULL,
    FOREIGN KEY (id)
      REFERENCES me(id)
);

INSERT INTO me
VALUES ('Ashley', 'Davis', 'Northeastern University',
        'B.S. in Computer Science', 'ashley921davis@gmail.com');

INSERT INTO hobbies (id, hobby)
VALUES (1, 'Fencing 🤺'), (1, 'Lifting 💪'), (1, 'Gaming 🎮'), (1, 'Crosswords 🏁');
```

Hi there! My name is Ashley Davis, a 21 year old programmer from Riverdale, NJ (nothing like the [tv show](https://en.wikipedia.org/wiki/Riverdale_(American_TV_series))). Welcome to my github porfolio!

### Stats
[![Ashley's GitHub stats](https://github-readme-stats.vercel.app/api?username=ashleytdavis)](https://github.com/anuraghazra/github-readme-stats)



### Tech Stack
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)&nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)&nbsp;
![Typescript](https://img.shields.io/badge/-Typescript-05122A?style=flat&logo=Typescript)&nbsp;
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react)&nbsp;
![Node.js](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=node.js)&nbsp;
![Java](https://img.shields.io/badge/-Java-05122A?style=flat&logo=Java&logoColor=FFA518)&nbsp;
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Markdown](https://img.shields.io/badge/-Markdown-05122A?style=flat&logo=markdown)\
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;
![Eclipse](https://img.shields.io/badge/-Eclipse-05122A?style=flat&logo=eclipse-ide&logoColor=2C2255)&nbsp;
![Photoshop](https://img.shields.io/badge/-Photoshop-05122A?style=flat&logo=adobe-photoshop)&nbsp;

### Connect with Me
<a href="https://linkedin.com/in/ashleytdavis"><img src="https://img.shields.io/badge/-Ashley%20Davis%20-0077B5?style=flat&logo=Linkedin&logoColor=white"/></a>
<a href="mailto:ashley921davis@gmail.com"><img src="https://img.shields.io/badge/-ashley921davis@gmail.com-D14836?style=flat&logo=Gmail&logoColor=white"/></a>
