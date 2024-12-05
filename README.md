## 👋 Hi there! 

```SQL
CREATE TABLE me {
  id INT AUTO_INCREMENT PRIMARY KEY,
  firstName VARCHAR(30),
  lastName VARCHAR(30),
  school VARCHAR(100),
  degree VARCHAR(200),
  email NOT NULL VARCHAR(100)
}

CREATE TABLE hobbies (
    hobby_id INT AUTO_INCREMENT PRIMARY KEY,
    id INT NOT NULL,            
    hobby VARCHAR(255) NOT NULL,
    FOREIGN KEY (id)
      REFERENCES me(id)
);

INSERT INTO ashleytdavis
VALUES ('Ashley', 'Davis', 'Northeastern University',
        'B.S. in Computer Science', 'ashley921davis@gmail.com');

INSERT INTO hobbies (id, hobby)
VALUES (1, 'Fencing 🤺'), (1, 'Lifting 💪'), (1, 'Gaming 🎮');
```


### Tech Stack
❤️ Typescript
🧡 Java
💛 Python
💚 Node.js
🩵 React
💙 SQL/MySQL
💜 HTML
🖤 CSS
🩶 Visual Studio Code
🤍 Github & Git
🤎 Photoshop

### Connect with Me
- Linkedin
- Email
- Twitter
