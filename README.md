
<h1 align="center">Hi 👋, I'm Onsa Bezzine</h1>
<h3 align="center">Full Stack Java & Angular Developer | Passionate about Clean Code, and Real-World Solutions </h3>
<?xml version="1.0" encoding="utf-8"?>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 220" width="900" height="220" role="img" aria-labelledby="title desc">
  <title id="title">Our Nature Sparks Achievement — ONSA</title>
  <desc id="desc">Stylized header where initials O, N, S, A are highlighted to represent the name ONSA.</desc>

  <defs>
    <linearGradient id="gradInitial" x1="0" x2="1">
      <stop offset="0" stop-color="#FF6B6B"/>
      <stop offset="1" stop-color="#FFB86B"/>
    </linearGradient>

    <style><![CDATA[
      text { font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; }
      .word { fill:#E6EEF8; font-weight:500; font-size:48px; }
      .initial { fill: url(#gradInitial); font-weight:800; font-size:76px;
                 filter: drop-shadow(0 0 10px rgba(255,107,107,0.45));
                 animation: float 3.5s ease-in-out infinite, glow 2.8s ease-in-out infinite;
                 transform-origin: center;
      }
      @keyframes float { 0%{transform:translateY(0)}50%{transform:translateY(-6px)}100%{transform:translateY(0)} }
      @keyframes glow  { 0%{filter:drop-shadow(0 0 6px rgba(255,107,107,0.35))}50%{filter:drop-shadow(0 0 18px rgba(255,107,107,0.95))}100%{filter:drop-shadow(0 0 6px rgba(255,107,107,0.35))} }

      .caption { fill:#94A3B8; font-size:14px; font-weight:600; letter-spacing:1px; }
      .spark { fill:#FFD86B; opacity:0; animation:twinkle 3s linear infinite; }
      @keyframes twinkle { 0%{opacity:0;transform:scale(0.6)} 10%{opacity:1;transform:scale(1)} 30%{opacity:0.6} 100%{opacity:0} }
    ]]></style>
  </defs>

  <rect width="900" height="220" rx="16" fill="transparent"/>

  <!-- Sparks -->
  <circle class="spark" cx="690" cy="36" r="4" style="animation-delay:0s"/>
  <circle class="spark" cx="120" cy="28" r="3" style="animation-delay:0.6s"/>
  <circle class="spark" cx="520" cy="78" r="3.5" style="animation-delay:1.2s"/>

  <!-- Use separate <text> elements for predictable positioning -->
  <!-- baseline y = 120 for the line -->
  <g transform="translate(70,0)">
    <!-- Our -->
    <text x="0" y="120" class="initial">O</text>
    <text x="56" y="120" class="word">ur</text>

    <!-- Nature -->
    <text x="220" y="120" class="initial">N</text>
    <text x="276" y="120" class="word">ature</text>

    <!-- Sparks -->
    <text x="420" y="120" class="initial">S</text>
    <text x="476" y="120" class="word">parks</text>

    <!-- Achievement -->
    <text x="610" y="120" class="initial">A</text>
    <text x="666" y="120" class="word">chievement</text>
  </g>

  <text x="450" y="188" text-anchor="middle" class="caption">Initiales mises en valeur → O N S A = Onsa</text>
</svg>


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



