```markdown
<div align="center">
  
![Header](./github-header-banner.png)

<br/>

<h1>🐍 Gabrieli Santana</h1>
<h3>Estudante de ADS | Python & Flask | Backend Developer</h3>

<!-- GitHub Snake -->
![GitHub Snake](https://raw.githubusercontent.com/Gabrieli-Santana/Gabrieli-Santana/output/github-contribution-grid-snake.svg)

<!-- Badges -->
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

<br/>

📧 **Email:** gabrielisantanademlo@gmail.com  
💼 **LinkedIn:** [Gabrieli Santana](https://www.linkedin.com/in/gabrieli-santana-4a95512b1/)  
📚 **Curso:** Análise e Desenvolvimento de Sistemas - Unicesumar  
📍 **Localização:** Florianópolis/SC

</div>

<br/>

## 👋 Sobre Mim

Olá! Sou **Gabrieli Santana**, estudante de **Análise e Desenvolvimento de Sistemas** na Unicesumar Florianópolis. 

Atualmente estou focada em desenvolver minhas habilidades em **backend com Python**, criando APIs RESTful, integrando com bancos de dados e consumindo APIs externas. Este portfólio reúne meus projetos práticos onde aplico os meus conhecimentos.

### 🎯 Tiro Rápido:

**💼 Atualmente estou trabalhando em:**
- 💻 Desenvolvimento de uma nova plataforma de e-commerce utilizando React e Node.js
- 🖥️ Sistema de monitoramento de servidores em tempo real

**🌱 Atualmente estou aprendendo:**
- 📚 Explorando o Zustand para gerenciamento de estado
- 🐍 Python avançado para backend e automação
- 🗄️ Banco de dados PostgreSQL e MongoDB

**💬 Pergunte-me sobre:**
- Python, SQL, Markdown, JavaScript, React
- Desenvolvimento Backend e APIs REST
- Versionamento com Git e GitHub

**⚡ Curiosidade:**
- 🎢 Certa vez, resolvi um problema enquanto estava em uma montanha-russa!

<br/>

## 🛠️ Habilidades Técnicas

### **💻 Linguagens de Programação:**
![JavaScript](https://img.shields.io/badge/JavaScript-Expert-yellow?style=flat-square)
![Python](https://img.shields.io/badge/Python-Advanced-blue?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-Intermediate-blue?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-Advanced-orange?style=flat-square)

### **⚡ Frontend:**
![React](https://img.shields.io/badge/React-Expert-61DAFB?style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-Advanced-38B2AC?style=flat-square)
![GSAP](https://img.shields.io/badge/GSAP-Intermediate-88CE02?style=flat-square)

### **🔧 Backend:**
![Node.js](https://img.shields.io/badge/Node.js-Advanced-339933?style=flat-square)
![Express](https://img.shields.io/badge/Express-Intermediate-000000?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-Intermediate-000000?style=flat-square)

### **🗄️ Banco de Dados:**
![MongoDB](https://img.shields.io/badge/MongoDB-Intermediate-47A248?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Intermediate-336791?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-Intermediate-4479A1?style=flat-square)
![Prisma](https://img.shields.io/badge/Prisma-Intermediate-2D3748?style=flat-square)

<br/>

## 🚀 Projetos em Destaque

### 🤖 **[Dashboard de Monitoramento de Servidores](https://github.com/Gabrieli-Santana/Portfolio)**
**Sistema em tempo real para monitoramento de infraestrutura**

```python
# Tecnologias: Python, FastAPI, WebSockets, psutil
from fastapi import FastAPI, WebSocket
import psutil
import asyncio

app = FastAPI()

@app.websocket("/ws")
async def websocket_endpoint(websocket: WebSocket):
    await websocket.accept()
    while True:
        metrics = {
            "cpu": psutil.cpu_percent(),
            "memory": psutil.virtual_memory().percent,
            "disk": psutil.disk_usage('/').percent
        }
        await websocket.send_json(metrics)
        await asyncio.sleep(2)
```

**✅ Funcionalidades:**
- 📊 **Métricas em tempo real** (CPU, Memória, Disco)
- 🔔 **Sistema de alertas** automático
- 🌐 **WebSockets** para atualização contínua
- 📱 **Interface responsiva** com gráficos
- 🐳 **Docker** para containerização

### 💰 **[Gerenciador de Gastos Pessoais](https://github.com/Gabrieli-Santana/Portfolio)**
**Sistema para controle financeiro pessoal com análise de gastos**

**✅ Funcionalidades:**
- 💳 **CRUD completo** de transações
- 📈 **Relatórios** por categoria e período
- 💾 **Persistência** em SQLite
- 🎯 **Interface CLI** interativa
- 📊 **Análises** visuais dos gastos

### 📝 **[Gerenciador de Tarefas Inteligente](https://github.com/Gabrieli-Santana/Portfolio)**
**Sistema de organização com priorização automática**

**✅ Funcionalidades:**
- ⚡ **Prioridades inteligentes** (alta, média, baixa)
- 🔔 **Lembretes** automáticos
- 📅 **Agendamento** flexível
- 📁 **Categorização** por projetos
- 🔍 **Busca** e filtros avançados

<br/>

## 📈 Estatísticas do GitHub

<div align="center">

<!-- GitHub Stats -->
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Gabrieli-Santana&show_icons=true&theme=radical&hide_border=true)

<!-- Streak Stats -->
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Gabrieli-Santana&theme=radical&hide_border=true)

<!-- Top Languages -->
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Gabrieli-Santana&layout=compact&theme=radical&hide_border=true)

</div>

<br/>

## 🎯 Evolução do Aprendizado

### **🏆 Competências Desenvolvidas:**
- ✅ **Lógica de Programação** com Python e JavaScript
- ✅ **Programação Orientada a Objetos** (POO)
- ✅ **APIs RESTful** com Flask e Express
- ✅ **Banco de Dados** SQL e NoSQL
- ✅ **Versionamento** com Git e GitHub
- ✅ **Documentação** técnica de projetos

### **🚀 Próximos Objetivos:**
- 🔄 **Zustand** para gerenciamento de estado
- 🌐 **Desenvolvimento Web** com Django
- ☁️ **Deploy** de aplicações em nuvem (AWS/Azure)
- 🐳 **Docker** e containerização avançada
- 🔧 **CI/CD** pipelines
- 🧪 **Testes automatizados** (Jest, Pytest)

<br/>

## 📫 Vamos Conectar!

<div align="center">

💌 **Email:** [gabrielisantanademlo@gmail.com](mailto:gabrielisantanademlo@gmail.com)  
💼 **LinkedIn:** [Gabrieli Santana](https://www.linkedin.com/in/gabrieli-santana-4a95512b1/)  
🐙 **GitHub:** [Gabrieli-Santana](https://github.com/Gabrieli-Santana)  
📚 **Instituição:** Unicesumar - Florianópolis/SC

<br/>

![Visitor Count](https://komarev.com/ghpvc/?username=Gabrieli-Santana&color=blueviolet&style=flat-square)

</div>

---

<div align="center">

⭐ **Sinta-se à vontade para explorar meus repositórios e contribuir!**

*"O sucesso é a soma de pequenos esforços repetidos dia após dia."* - Robert Collier

<br/>

**Obrigada pela visita! 😊**

</div>
```
