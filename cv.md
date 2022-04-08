# Stefan Stojkovic

## Contact Information

- Phone: +381 61 225 36 84;
- Email: stefan.chipsy@gmail.com;
- LinkedIn: https://www.linkedin.com/in/stefan-stojkovic-75004a135/;
- Facebook: https://www.facebook.com/profile.php?id=1008714495;
- Git Profile: https://github.com/chipsy1992;

### Summary

I work as a personal and condicional trainer, but that is not the job I want to do. So I finished IT Academy in Belgrade, and I realized that programming is something where I can find myself.
I have already learned some of **HTML** and **CSS** and **JavaScript** on my own, but I am hoping I can go into more depth within this course.

### Skills

As I already mentioned I do not have much experience in programing however, I know basics of:

- HTML;
- CSS;
- JavaScript;
- PHP;
- MySql;
- VScode;
- GitHub.

```js
const resetButton = document.querySelector("#reset");
const winningScoreSelect = document.querySelector("#playto");

let winningScore = 3;
let isGameOver = false;

function updateScores(player, opponent) {
  if (!isGameOver) {
    player.score += 1;
    if (player.score === winningScore) {
      isGameOver = true;
      player.display.classList.add("has-text-success");
      opponent.display.classList.add("has-text-danger");
      player.button.disabled = true;
      opponent.button.disabled = true;
    }
    player.display.textContent = player.score;
  }
}
```

### Experience

I don't have any experience. I finished IT Academy, some courses on Udemy, and working on some projects on my own.

### Education

Engineer of Technology - Faculty of Technology (http://www.tf.ni.ac.rs/);
Certified PHP Web Developer - ITAcademy (https://www.it-akademija.com/);

### Foreign Languages

**English**
LISTENING **C1** READING **C1**
WRITING **B2** SPOKEN PRODUCTION **B2** SPOKEN INTERACTION **B2**
