# evielm9awda's GitHub Profile

<div align="center">
  <img src="https://raw.githubusercontent.com/evielm9awda/evielm9awda/main/terminal.svg" alt="Terminal" width="800" height="400">
</div>

<script>
const terminal = `
Welcome to evielm9awda's GitHub Terminal!
-------------------------------------------

$ whoami
evielm9awda

$ ls projects
- project1
- project2
- project3

$ cat about_me.txt
Hi there! I'm evielm9awda, a passionate developer who loves to code and create.
My interests include:
- Web Development
- Machine Learning
- Open Source Contributions

$ git status
On branch main
Your repository is up to date with 'origin/main'

$ echo "Feel free to explore my repositories and contribute!"

$ exit
Logging off... Thanks for visiting!
`;

document.addEventListener('DOMContentLoaded', (event) => {
  const pre = document.querySelector('pre');
  let i = 0;
  const typeWriter = () => {
    if (i < terminal.length) {
      pre.innerHTML += terminal.charAt(i);
      i++;
      setTimeout(typeWriter, 10);
    }
  };
  typeWriter();
});
</script>

<pre style="background-color: #000; color: #0f0; padding: 20px; border-radius: 5px; font-family: monospace;">
</pre>

## Connect with me

- 📫 How to reach me: [Your preferred contact method]
- 🌐 Website: [Your website if you have one]
- 💼 LinkedIn: [Your LinkedIn profile]

## GitHub Stats

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=evielm9awda&show_icons=true&theme=radical)

## Top Languages

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=evielm9awda&layout=compact&theme=radical)

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=evielm9awda&color=brightgreen" alt="Profile views">
</div>
