## **Злата Косаревич**

### Junior Frontend Developer

---

### **Контактная информация**:

##### **Phone**: +7 903 131 1216

##### **E-mail**: <z.kosarevitch@yandex.ru>

##### **Telegram**: @zlavvitch

##### **Github**: [zlavvitch](https://github.com/zlavvitch)

---

### **About myself**:

Решила изменить сферу своей деятельности. На данный момент активно изучаю все необходимое. 

---

### **Навыки**:

- HTML
- CSS (Framework Bootstrap, Preprocessor SCSS, BEM methodology).
- JavaScript (Fundamentals,Functional Programming).
- Version control: Git (remote service GitHub).
- Module Bundlers: Webpack.
- MacOS
- Editor: VSCode.

---

### **Пример кода**:

```javascript
const getDaysBetweenDates = (date1, date2) => {
  if (!date2) throw new TypeError('TypeError');

  let result = Math.trunc(
    (new Date(date2).getTime() - new Date(date1).getTime()) / 86400000
  );

  if (result === -0) return (result = 0);
  return result;
};

getDaysBetweenDates('1-1-2020', '1-2-2020'); // -> 1
getDaysBetweenDates(new Date(2011, 6, 2, 6, 0), new Date(2012, 6, 2, 18, 0)); // -> 366
getDaysBetweenDates(1409796000000, 1409925600000); // -> 1
getDaysBetweenDates('1-1-2020', 'дата'); // -> NaN
getDaysBetweenDates(null); // -> TypeError
```

---

### **Опыт работы**:

Учебные проекты:

- [KataAcademy](https://github.com/zlavvitch/ProjectKata.git)
- [Professional](https://github.com/zlavvitch/Project-Fest.git)

---

### **Образование (курсы)**:

- Innopolis University «Course Introduction to Front-End Development» at the (completed)
- «Professional» Course «Full Stack Development» (in progress)
- KataAcademy Course «Front-End Development» (in progress)
- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

---

### **Языки**:

- English - Intermediate
- French - Basic