```js
import { StudentWebDeveloper } from '@deyamae'; 

class Bio extends StudentWebDeveloper { 
  name     = 'Andy'; 
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
