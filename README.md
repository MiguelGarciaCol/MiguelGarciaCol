<p align="right">
  🌐 Selecciona idioma: 
  <select id="language-selector">
    <option value="es">Español</option>
    <option value="en">English</option>
  </select>
</p>

<!-- Contenido en español -->
<div id="es">
  <p align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=1000&color=00FFC0&background=00FFC000&center=true&vCenter=true&width=800&lines=Soy+Miguel+Garcia;Estudiante+de+Ingenier%C3%ADa+de+Software;Apasionado+por+Java+y+el+desarrollo+backend" alt="Typing SVG"/>
  </p>

  ### 👋 Hola, soy Miguel Garcia 🇨🇴

  🎓 Estudiante de Ingeniería de Software en la Iberoamericana  
  💻 Apasionado por Java y el desarrollo backend con Spring Boot  
  📍 Actualmente en **Colombia**  
  🔍 Aprendiendo **Java**, **Spring Boot** y profundizando en **bases de datos**  

  ### 🧰 Tecnologías y herramientas
  <!-- Tabla de tecnologías en español -->

  ### 🧰 Tecnologías y herramientas
<table align="center">
  <tr>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40" height="40" alt="Java"/>
      <br/>
      <span>Java</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="40" height="40" alt="Spring Boot"/>
      <br/>
      <span>Spring Boot</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" height="40" alt="MySQL"/>
      <br/>
      <span>MySQL</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL"/>
      <br/>
      <span>PostgreSQL</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" width="40" height="40" alt="Oracle DB"/>
      <br/>
      <span>Oracle DB</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="40" height="40" alt="IntelliJ"/>
      <br/>
      <span>IntelliJ</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40" alt="Git"/>
      <br/>
      <span>Git</span>
    </td>
  </tr>
</table>
</div>

<!-- Contenido en inglés -->
<div id="en" style="display: none;">
  <p align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=1000&color=00FFC0&background=00FFC000&center=true&vCenter=true&width=800&lines=I+am+Miguel+Garcia;Software+Engineering+Student;Passionate+about+Java+and+Backend+Development" alt="Typing SVG"/>
  </p>

  ### 👋 Hi, I'm Miguel Garcia 🇨🇴

  🎓 Software Engineering student at Iberoamericana  
  💻 Passionate about Java and backend development with Spring Boot  
  📍 Currently in **Colombia**  
  🔍 Learning **Java**, **Spring Boot**, and deepening knowledge in **databases**  

  ### 🧰 Technologies and Tools
  <!-- Tabla de tecnologías en inglés -->
  ### 🧰 Tecnologías y herramientas
<table align="center">
  <tr>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40" height="40" alt="Java"/>
      <br/>
      <span>Java</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="40" height="40" alt="Spring Boot"/>
      <br/>
      <span>Spring Boot</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" height="40" alt="MySQL"/>
      <br/>
      <span>MySQL</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL"/>
      <br/>
      <span>PostgreSQL</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" width="40" height="40" alt="Oracle DB"/>
      <br/>
      <span>Oracle DB</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="40" height="40" alt="IntelliJ"/>
      <br/>
      <span>IntelliJ</span>
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40" alt="Git"/>
      <br/>
      <span>Git</span>
    </td>
  </tr>
</table>
</div>

<script>
  // Script para cambiar entre idiomas
  const languageSelector = document.getElementById('language-selector');
  const sections = {
    es: document.getElementById('es'),
    en: document.getElementById('en')
  };

  languageSelector.addEventListener('change', (e) => {
    const selectedLanguage = e.target.value;
    Object.keys(sections).forEach(lang => {
      sections[lang].style.display = lang === selectedLanguage ? 'block' : 'none';
    });
  });
</script>


