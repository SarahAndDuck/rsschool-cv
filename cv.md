# _Ratkevich Irina_

---

## _Contacts:_

- **Location:** Tomsk, Russia
- **Phone:** +7-952-163-0774
- **Email:** ratkevirina@gmail.ru
- **GitHub:** [SarahAndDuck](https://github.com/SarahAndDuck)
- **Discord:** Irin (@SarahAndDuck)

---

## _About me:_

I am taking in **The Rolling Scopes** JavaScript/Front-end course
to gain the knowledge and experience to work as
a Junior JavaScript/Front-end Software Engineer.

---

## _Skils:_

- HTML
- CSS
- Preprocessor SCSS
- JavaScript
- React
- Version Control/Git
- Browser Developer tools
- Responsive and Mobile Design
- UX/Usability
- Figma

---

## _Code example:_

**Task**: Implement an intersection function that takes two arrays of numbers and returns an array of numbers present in the first and second arrays.

    const intersection = (...restParam) => {
      if (restParam.length < 2) {
        throw new Error('INVALID_ARGUMENTS_COUNT');
      }

      for (let argument of restParam) {
        if (!Array.isArray(argument)) {
          throw new Error('INVALID_ARGUMENT');
        }
        for (let item of argument) {
          if (!(typeof item === 'number')) {
            throw new Error('INVALID_ELEMENT_IN_ARRAY');
          }
        }
      }

      var resultFilter = restParam[0].filter((x) => restParam[1].includes(x));
      var result = resultFilter.filter((val, ind, arr) => arr.indexOf(val) === ind);
      return result;
    };

---

## _Education:_

[Tomsk State University of Control Systems and Radioelectronics](https://tusur.ru/en)

---

## _Curses:_

- youtube channels:
  - [FreelancerLifeStyle](https://www.youtube.com/c/FreelancerLifeStyle)
  - [GLO Academy](https://glo.academy)
- online courses:
  - [online javascript tutorial](https://learn.javascript.ru/)
  - [htmlacademy](https://htmlacademy.ru)
  - [Rubius academy](https://academy.rubius.com/)

---

## _Languages:_

- Russian - native speaker
- English - A2
