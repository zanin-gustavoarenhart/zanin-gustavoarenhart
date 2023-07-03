<div align="center">
  <a href="https://github.com/lopes-gustavodossantos">
  <img width="42%" src="https://github-readme-stats.vercel.app/api?username=lopes-gustavodossantos&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img width="50%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lopes-gustavodossantos&layout=compact&langs_count=7&theme=dark"/>
</div>

<div> 
  <a href="https://www.linkedin.com/in/gustavo-dos-santos-lopes/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href = "mailto:lopes.gustavodossantos@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"_blank"></a>
</div>

<div align="center">
button {
  font-family: inherit;
  font-size: 20px;
  background: royalblue;
  color: white;
  padding: 0.7em 1em;
  padding-left: 0.9em;
  display: flex;
  align-items: center;
  border: none;
  border-radius: 16px;
  overflow: hidden;
  transition: all 0.2s;
}

button span {
  display: block;
  margin-left: 0.3em;
  transition: all 0.3s ease-in-out;
}

button svg {
  display: block;
  transform-origin: center center;
  transition: transform 0.3s ease-in-out;
}

button:hover .svg-wrapper {
  animation: fly-1 0.6s ease-in-out infinite alternate;
}

button:hover svg {
  transform: translateX(1.2em) rotate(45deg) scale(1.1);
}

button:hover span {
  transform: translateX(5em);
}

button:active {
  transform: scale(0.95);
}

@keyframes fly-1 {
  from {
    transform: translateY(0.1em);
  }

  to {
    transform: translateY(-0.1em);
  }
}
</div>
