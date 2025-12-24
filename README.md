
<h1 align="center">Hi 👋, I'm Onsa Bezzine</h1>
<h3 align="center">Full Stack Java & Angular Developer | Passionate about Clean Code, and Real-World Solutions </h3>


<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" width="100%" height="160" viewBox="0 0 1000 160" role="img" aria-label="Our Nature Sparks Achievement - creative">
    <defs>
      <linearGradient id="gradShift" x1="0" x2="1">
        <stop offset="0%" stop-color="#7C3AED">
          <animate attributeName="stop-color" dur="6s" repeatCount="indefinite"
                   values="#7C3AED;#06B6D4;#60A5FA;#7C3AED"/>
        </stop>
        <stop offset="100%" stop-color="#06B6D4">
          <animate attributeName="stop-color" dur="6s" repeatCount="indefinite"
                   values="#06B6D4;#60A5FA;#7C3AED;#06B6D4"/>
        </stop>
      </linearGradient>

      <!-- filtre glow pour initiales -->
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <!-- petite ligne décorative animée -->
      <linearGradient id="lineGrad" x1="0" x2="1">
        <stop offset="0%" stop-color="#60A5FA" stop-opacity="0.9"/>
        <stop offset="100%" stop-color="#06B6D4" stop-opacity="0.9"/>
      </linearGradient>
    </defs>

    <!-- fond transparent pour GitHub, texte centré -->
    <g transform="translate(500,75)">
      <!-- texte principal composé de blocs pour pouvoir animer chaque initiale -->
      <text text-anchor="middle" font-family="Fira Code, 'Segoe UI', Roboto, system-ui, monospace" font-size="34" letter-spacing="0.6">
        <!-- "Our" -->
        <tspan x="-280" dy="-6" fill="#94A3B8">Our </tspan>

        <!-- O initiale : glow + pulse -->
        <tspan x="-240" dy="0" fill="url(#gradShift)" font-weight="900" font-size="44" filter="url(#glow)">
          O
          <animate attributeName="font-size" values="44;50;44" dur="3s" repeatCount="indefinite"/>
        </tspan>

        <!-- "Nature" -->
        <tspan x="-200" dy="0" fill="#94A3B8">ature </tspan>

        <!-- N initiale -->
        <tspan x="-80" dy="0" fill="url(#gradShift)" font-weight="900" font-size="44" filter="url(#glow)">
          N
          <animate attributeName="font-size" values="44;50;44" begin="0.5s" dur="3s" repeatCount="indefinite"/>
        </tspan>

        <tspan x="-40" dy="0" fill="#94A3B8">ature </tspan> <!-- small spacing correction if needed -->

        <!-- S initiale -->
        <tspan x="70" dy="0" fill="url(#gradShift)" font-weight="900" font-size="44" filter="url(#glow)">
          S
          <animate attributeName="font-size" values="44;50;44" begin="1s" dur="3s" repeatCount="indefinite"/>
        </tspan>
        <tspan x="110" dy="0" fill="#94A3B8">parks </tspan>

        <!-- A initiale -->
        <tspan x="260" dy="0" fill="url(#gradShift)" font-weight="900" font-size="44" filter="url(#glow)">
          A
          <animate attributeName="font-size" values="44;50;44" begin="1.5s" dur="3s" repeatCount="indefinite"/>
        </tspan>
        <tspan x="300" dy="0" fill="#94A3B8">chievement</tspan>
      </text>

      <!-- ligne décorative animée en dessous -->
      <line x1="-360" x2="360" y1="28" y2="28" stroke="url(#lineGrad)" stroke-width="2" stroke-linecap="round">
        <animate attributeName="stroke-dasharray" from="0,720" to="720,0" dur="6s" repeatCount="indefinite"/>
      </line>

      <!-- petites étincelles animées pour le côté créatif -->
      <g>
        <circle cx="-140" cy="-30" r="2.6" fill="#FFF" opacity="0.9">
          <animate attributeName="cy" values="-30;-50;-30" dur="2.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.9;0.2;0.9" dur="2.5s" repeatCount="indefinite"/>
        </circle>
        <circle cx="80" cy="-22" r="2.2" fill="#FFF" opacity="0.8">
          <animate attributeName="cy" values="-22;-40;-22" begin="0.8s" dur="2.6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.8;0.15;0.8" begin="0.8s" dur="2.6s" repeatCount="indefinite"/>
        </circle>
      </g>
    </g>
  </svg>
</p>

---

### About Me

- Engineer with strong academic background in **Software Engineering**
- Specialized in **Full Stack Java & Angular development**
- Passionate about **clean architecture**, **real-world applications**, and **DevOps best practices**
- Building and contributing to open-source projects while preparing for professional opportunities

---

### Technical Skills

- **Backend**: Java, Spring Boot, Spring Security, RESTful APIs, JWT Authentication, JPA, Hibernate
- **Frontend**: Angular, ReactJS, TypeScript, JavaScript, RxJS, Angular Material, Bootstrap, HTML, CSS
- **DevOps & CI/CD**: Docker, Git, GitHub Actions, Maven
- **Databases**: MySQL, MongoDB
- **Networking & Security**: Solid foundations in computer networking and network security (CCNA 2 certified), firewalls, VPNs, TCP/IP, OSI model, basic ethical hacking
- **Tools & IDEs**: VS Code, IntelliJ IDEA, Spring Tool Suite (STS), Postman, Figma 4
- **Testing & Debugging**: Unit testing (JUnit), Debugging, Logging,
- **Methodologies**: Agile (Scrum), version control workflows (Git/GitHub)
  
### Certifications
- Cisco CCNA 2: Switching, Routing, and Wireless Essentials
  
---

### 🚀 Projects

#### 1. **Mailbox Automation**
Asynchronous email receiver and processor using Spring Integration & JavaMail.

- **Backend**: Spring Boot 3.2.1, Spring Integration, JavaMail
- **Features**:
  - Receive and process emails via IMAP
  - Extract content, download attachments
  - Logs & moves processed mails to folders
- **Configuration**: YAML-based with thread pool tuning and secure IMAP setup


  
#### 2. **Employee Management System**
A full-stack CRUD application for managing employee data.

- **Backend**: Spring Boot, Spring Data JPA, MySQL
- **Frontend**: React, Axios, Bootstrap  
- **Features**:
  - View, add, update, and delete employees
  - RESTful API integration
- **Endpoints**:
  - `GET /api/v1/employees`
  - `POST /api/v1/employees`
  - `GET /api/v1/employees/{id}`
  - `PUT /api/v1/employees/{id}`
  - `DELETE /api/v1/employees/{id}`



#### 3. **Academic Projects (Private Repos)**
Created and developed as part of my final year project studies.

- Topics: Olympic committee digitalization
- Tech Stack: Spring Boot, Angular, MySQL
- *Note*: Repositories are private due to academic restrictions but reflect strong architectural design and teamwork experience


---

> “Code is not just about syntax — it's about solving problems, creating impact, and learning every day.”



