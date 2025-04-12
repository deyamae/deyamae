<p align="center">
  <img src="https://github.com/deyamae/deyamae/raw/main/jims-computer.jpg" alt="Jims Computer" width="1000" height="400" />
</p>


```js
import { StudentWebDeveloper } from '@deyamae'; 

class Bio extends StudentWebDeveloper { 
  name     = 'Andrea Quintana'; 
  title    = 'Aspiring Full-Stack Developer'; 
  location = 'Philippines'; 
  uptime   = '21 years'; 
}

class Skills extends StudentWebDeveloper { 
  languages = ['JavaScript', 'Python', 'PHP', 'C++']; 
  frontend  = ['HTML5', 'CSS3', 'Bootstrap']; 
  backend   = ['JavaScript']; 
  databases = ['MySQL']; 
  design    = ['Canva', 'Figma'];  
}

class Tools extends StudentWebDeveloper {
  tools = ['Git', 'VS Code', 'Docker'];
}

class Interests extends StudentWebDeveloper {
  interests = ['Valorant', 'Roblox', 'Mukbang Videos'];
}
