### 👋 Olá, me chamo Leandro Moura!

<br>

<p align="left">
  Atualmente sou <strong>Engenheiro de Software / Dev. Fullstack</strong> na <strong>Trestto Tecnologia</strong>.
  <br><br>
  Com mais de 3 anos de experiência, sou apaixonado por inovação tecnológica e pela construção de soluções robustas e escaláveis, com foco principal em automações Python, no ecossistema .NET e desenvolvimento front-end moderno.
  <br><br>
  Sou formado em Análise e Desenvolvimento de Sistemas e tenho [Pós-graduação/Certificação] pela FIAP, buscando sempre aprimorar meus conhecimentos técnicos para contribuir com o progresso da equipe e do produto.
</p>

<br>

---

### 🚀 Minhas Estatísticas no GitHub

<p align="center">
  <a href="https://github.com/leandromoura124">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=leandromoura124&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=leandromoura124&layout=compact&langs_count=7&theme=dracula"/>
  </a>
</p>

<br>

---

### 🔧 Tecnologias e Ferramentas

<div align="left">
  
  **Backend & Banco de Dados:**
  <br>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET">
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">

  <br><br>
  **Frontend:**
  <br>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  
  <br><br>
  **Cloud & DevOps:**
  <br>
  <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/CI%2FCD-2088C1?style=for-the-badge&logo=github-actions&logoColor=white" alt="CI/CD">
  
</div>

<br>

---

### 📫 Onde me encontrar

<p align="left">
  <a href="https://www.linkedin.com/in/moura-leandro/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>





var fila = (current.getDisplayValue('queue') || '').toLowerCase();

if (
  fila.indexOf('service desk chat') > -1 ||
  fila.indexOf('agiliza chat') > -1
) {
  answer = 1; // Chat
} else if (
  fila.indexOf('ura') > -1 ||
  fila.indexOf('telefone') > -1
) {
  answer = 2; // URA
} else if (
  fila.indexOf('callback') > -1 ||
  fila.indexOf('retorno') > -1
) {
  answer = 3; // Callback
} else {
  answer = 4; // Outros
}
