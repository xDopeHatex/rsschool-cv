# dr. Gorokhov Ivan

## Frontend Developer

**Contact information:**

**Phone:** +374-430-46-428  
**Email:** xgorokhovx@gmail.com  
**Telegram:** https://t.me/xDopex  
[LinkedIn](https://www.linkedin.com/in/ivan-gorokhov-829668234)  
[CodeWars](https://www.codewars.com/users/xDopeHatex/)

---

**Briefly About Myself:**

I am a skilled and motivated front-end developer with over one year of experience building and maintaining interactive, user-friendly websites and web applications. Proficient in the latest web development technologies and able to develop cross-platform compatible websites that meet the latest web standards.

---

**Skills:**

- HTML/CSS/JavaScript
- TypeScript
- Tailwind, Sass, SCSS
- React JS
- Redux, ReduxToolkit
- Axios
- Git, GitHub, GitLab
- REST API
- JWT
- Figma
- Jira, Clickup
- Problem-Solving Mindset

---

**Code example:**

Here's an example of function that could track the Y position of the screen. And use it to display button as soon as user scrolls up.

```
  const [isArrowActive, setIsArrowActive] = useState(false);

  const [lastScrollTop, setlastScrollTop] = useState(false);
  const [howMuchIsItUp, setHowMuchIsItUp] = useState(0);
  const [isItFarEnoughUp, setIsItFarEnoughUp] = useState(false);

  const [scrollY, setScrollY] = useState(0);

  const listenScrollY = () => {
    setScrollY(window.pageYOffset * 0.005);

    if (window.pageYOffset < lastScrollTop) {
      if (howMuchIsItUp > window.pageYOffset + 170) {
        setIsItFarEnoughUp(true);
      }
    } else {
      setIsItFarEnoughUp(false);
      setHowMuchIsItUp(window.pageYOffset);
    }

    setIsScrolledEnoughUp(isItFarEnoughUp);

    setlastScrollTop(window.pageYOffset);

    if (window.pageYOffset > 1100) {
      setIsArrowActive(true);
    } else {
      setIsArrowActive(false);
    }

    setIsScrolledEnoughDown(isArrowActive);
  };

  useEffect(() => {
    function watchScroll() {
      window.addEventListener("scroll", listenScrollY);
    }
    watchScroll();
    return () => {
      window.removeEventListener("scroll", listenScrollY);
    };
  });

```

---

**Courses:**

- Udemy: JS, React, Tailwind
- Frontend Masters: Redux, TypeScript, HTML/CSS/JS
- RS Schools Course «JavaScript/Front-end.» (in progress)

---

**Languages:**

- English - Intermediate/Upper-intermediate (according to the online test at [EFset](www.efset.org) )
- Russian - native
- English -
- Ukrainian - Intermediate
- Polish - Basic
- Belarusian - Basic
