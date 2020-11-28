# Official_Portfolio
## Description
In my portfolio you will find project 1 from the coding bootcamp, and 3 homework assignments. As I evolve as a full stack web developer, so will my portfolio!

### Tools/Technologies
- JavaScript
- HTML
- CSS
- Bootstrap

### Scroll to on Click
```JS
$('a.js-scroll-trigger[href*="#"]:not([href="#"])').click(function() {
      if (location.pathname.replace(/^\//, '') == this.pathname.replace(/^\//, '') && location.hostname == this.hostname) {
        var target = $(this.hash);
        target = target.length ? target : $('[name=' + this.hash.slice(1) + ']');
        if (target.length) {
          $('html, body').animate({
            scrollTop: (target.offset().top - 71)
          }, 1000, "easeInOutExpo");
          return false;
        }
      }
    });

```
## Live Link
- [Portfolio](https://aparnell0130.github.io/Official_Portfolio/)

![ALT Text](assets/img/profDemo.gif)
## Author Info
- Linkedin - [Aaron Parnell](https://www.linkedin.com/in/aaron-parnell-1ab4661b3/)
- Github - [aparnell0130](https://github.com/aparnell0130)

[Back to top](#Official_Portfolio)