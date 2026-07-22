<svg xmlns="http://www.w3.org/2000/svg" width="100%">
  <foreignObject width="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        .br-wrap {
          background-color: #050508;
          background-image: 
            repeating-linear-gradient(0deg, rgba(0,0,0,0.25) 0px, rgba(0,0,0,0.25) 2px, transparent 2px, transparent 4px),
            linear-gradient(rgba(0, 240, 255, 0.04) 1px, transparent 1px),
            linear-gradient(90deg, rgba(0, 240, 255, 0.04) 1px, transparent 1px),
            radial-gradient(circle at 50% 0%, rgba(255, 157, 0, 0.25), transparent 60%),
            radial-gradient(circle at 80% 100%, rgba(0, 240, 255, 0.15), transparent 50%);
          background-size: 100% 4px, 50px 50px, 50px 50px, 100% 100%, 100% 100%;
          color: #e0e0e6;
          padding: 30px;
          border-radius: 12px;
          font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
          position: relative;
          border: 1px solid rgba(0, 240, 255, 0.3);
          box-shadow: 0 0 50px rgba(0, 240, 255, 0.15), inset 0 0 80px rgba(0,0,0,0.8);
          line-height: 1.6;
        }
        h1, h2, h3 { font-family: 'JetBrains Mono', monospace; }
        h2 { 
          color: #ff9d00; font-size: 1.5rem; margin-top: 24px; margin-bottom: 16px; 
          text-transform: uppercase; letter-spacing: 0.1em;
          border-bottom: 1px solid rgba(255, 157, 0, 0.3); padding-bottom: 8px;
          text-shadow: 0 0 15px rgba(255, 157, 0, 0.4);
        }
        h3 { color: #00f0ff; font-size: 1.2rem; margin-bottom: 12px; text-shadow: 0 0 10px rgba(0, 240, 255, 0.4); }
        a { color: #00f0ff; text-decoration: none; border-bottom: 1px dotted #00f0ff; transition: all 0.2s; }
        a:hover { color: #ff9d00; border-bottom: 1px solid #ff9d00; text-shadow: 0 0 8px #ff9d00; }
        
  details {
          margin-bottom: 24px; border: 1px solid rgba(0, 240, 255, 0.3); border-radius: 8px;
          background: rgba(5, 5, 8, 0.85); overflow: hidden; position: relative;
          box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
        }
        summary {
          padding: 16px 24px; cursor: pointer; font-weight: 800; font-size: 1.1rem;
          color: #ff9d00; background: rgba(255, 157, 0, 0.05);
          border-bottom: 1px solid rgba(0, 240, 255, 0.2); list-style: none;
          display: flex; align-items: center; gap: 12px;
          text-transform: uppercase; letter-spacing: 0.15em; font-family: 'JetBrains Mono', monospace;
        }
        summary::-webkit-details-marker { display: none; }
        summary::before { content: "▶"; font-size: 0.8rem; transition: transform 0.3s ease; color: #00f0ff; }
        details[open] summary::before { transform: rotate(90deg); }
        summary:hover { background: rgba(255, 157, 0, 0.15); box-shadow: inset 0 0 20px rgba(255, 157, 0, 0.1); }
        details[open] summary { 
          background: rgba(0, 240, 255, 0.1); color: #00f0ff; 
          text-shadow: 0 0 10px rgba(0, 240, 255, 0.8); border-bottom: 1px solid #00f0ff;
        }
        .content { padding: 24px; position: relative; z-index: 1; }

  table { width: 100%; border-collapse: collapse; margin: 16px 0; font-size: 0.9rem; }
        th { 
          background: rgba(0, 240, 255, 0.1); color: #00f0ff; text-align: left; padding: 12px; 
          border-bottom: 2px solid #00f0ff; text-transform: uppercase; letter-spacing: 0.05em; font-family: 'JetBrains Mono', monospace;
        }
        td { padding: 12px; border-bottom: 1px solid rgba(0, 240, 255, 0.15); color: #e0e0e6; }
        tr:hover { background: rgba(255, 157, 0, 0.05); }
        td a { color: #ff9d00; font-weight: 600; border-bottom: none; }
        td a:hover { color: #fff; text-shadow: 0 0 8px #ff9d00; }

  pre { 
          background: rgba(0, 0, 0, 0.6); padding: 20px; border-radius: 8px; 
          border-left: 4px solid #ff9d00; overflow-x: auto; 
          font-family: 'JetBrains Mono', monospace; font-size: 0.85rem; line-height: 1.6;
          box-shadow: inset 0 0 20px rgba(0,0,0,0.5);
        }
        code { color: #00f0ff; }
        
  ul { list-style: none; padding: 0; margin: 16px 0; }
        li { 
          padding: 10px 15px; margin-bottom: 8px; background: rgba(255, 255, 255, 0.02); 
          border-left: 3px solid #00f0ff; border-radius: 0 6px 6px 0; transition: all 0.2s;
        }
        li:hover { background: rgba(0, 240, 255, 0.05); border-left-color: #ff9d00; transform: translateX(5px); }
        li strong { color: #ff9d00; }

  blockquote { 
          border-left: 4px solid #ff9d00; padding: 12px 15px; margin: 16px 0; 
          color: #8a8a9a; font-style: italic; background: rgba(255, 157, 0, 0.03); border-radius: 0 8px 8px 0; 
        }

  .neon-btn {
          display: inline-block; padding: 10px 20px; border: 1px solid #00f0ff; color: #00f0ff;
          border-radius: 4px; text-transform: uppercase; letter-spacing: 0.1em; font-size: 0.8rem;
          box-shadow: 0 0 10px rgba(0, 240, 255, 0.2), inset 0 0 10px rgba(0, 240, 255, 0.1);
          margin: 5px; font-family: 'JetBrains Mono', monospace; font-weight: bold;
        }
        .neon-btn:hover { background: rgba(0, 240, 255, 0.15); box-shadow: 0 0 25px rgba(0, 240, 255, 0.6); color: #fff; border-bottom: none; }
        .neon-btn.amber { border-color: #ff9d00; color: #ff9d00; box-shadow: 0 0 10px rgba(255, 157, 0, 0.2), inset 0 0 10px rgba(255, 157, 0, 0.1); }
        .neon-btn.amber:hover { background: rgba(255, 157, 0, 0.15); box-shadow: 0 0 25px rgba(255, 157, 0, 0.6); }

  .gif-br {
          width: 100%; border-radius: 8px; border: 1px solid rgba(255, 157, 0, 0.3);
          box-shadow: 0 0 30px rgba(255, 157, 0, 0.2); margin: 24px 0;
        }
        hr { border: 0; height: 1px; background: linear-gradient(90deg, transparent, #00f0ff, #ff9d00, transparent); margin: 30px 0; opacity: 0.5; }
      </style>

  <div class="br-wrap">
        <h1 align="center" style="margin-top: 0; border: none; text-shadow: none; color: #e0e0e6;">
          <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=00FF88&center=true&vCenter=true&width=600&lines=FULLSTACK+DEVELOPER;Java+%7C+Spring+%7C+React+%7C+Vue;4%2B+Years+Experience;Microservices+%7C+Event-Driven;Clean+Code+%7C+Pixel-Perfect+UI" alt="Typing SVG" />
        </h1>

  <p align="center" style="margin-bottom: 24px;">
          <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
          <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
          <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
          <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />
          <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
          <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
          <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white" />
          <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
          <img src="https://img.shields.io/badge/Kubernetes-326DE6?style=for-the-badge&logo=kubernetes&logoColor=white" />
        </p>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="gif-br" alt="Blade Runner Rain" />

  <details open>
          <summary>🇷🇺 Русский</summary>
          <div class="content">
            <h2>⚡ Обо мне</h2>
            <pre><code>$ whoami
&gt; Daniil Rybiyakov | Fullstack Developer

$ cat focus.txt
&gt; Microservices, Event-Driven Architecture, Clean Code, Pixel-Perfect UI

$ uptime
&gt; 4+ years of commercial development</code></pre>
            <ul>
              <li>🔥 <strong>Backend:</strong> Java 17/21, Spring Boot, Spring Cloud, Spring Security, Kotlin</li>
              <li>🗄️ <strong>Data & Messaging:</strong> PostgreSQL, Redis, Apache Kafka, RabbitMQ, Hibernate/JPA</li>
              <li>🏗️ <strong>Architecture:</strong> Microservices, DDD, CQRS, Event-Driven, REST/gRPC</li>
              <li>🎨 <strong>Frontend:</strong> React 18, Vue 3, TypeScript, Next.js, Tailwind CSS</li>
              <li>🐳 <strong>DevOps & Tools:</strong> Docker, Kubernetes, GitLab CI, Grafana, JUnit 5/Mockito</li>
            </ul>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="gif-br" alt="Blade Runner Rain" />

  <h2>🌐 Портфолио</h2>
            <p align="center">
              <a href="https://daniil2022ri.github.io/Portfolio_FullStack/" target="_blank" class="neon-btn">🌐 Открыть Портфолио</a>
              <a href="https://daniil2022ri.github.io/Portfolio_FullStack/" target="_blank" class="neon-btn amber">Blade Runner Style</a>
            </p>
            <blockquote>🎬 Сайт-портфолио: React, glitch-эффекты, интерактивные карточки и живые демо-проекты.</blockquote>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="gif-br" alt="Blade Runner Rain" />

  <h2>🚀 Проекты</h2>
            <h3>Backend</h3>
            <table>
              <thead><tr><th>Проект</th><th>Стек</th><th>Описание</th></tr></thead>
              <tbody>
                <tr><td><a href="https://github.com/Daniil2022Ri/PaymentService" target="_blank">PaymentService</a></td><td>Java 21, Spring Boot, Kafka, Redis</td><td>Высоконагруженный микросервис платежей. Идемпотентность, retry-механизмы.</td></tr>
                <tr><td><a href="https://github.com/Daniil2022Ri/AIAssistantBackend" target="_blank">AIAssistantBackend</a></td><td>Java 21, WebFlux, OpenAI, Redis</td><td>Реактивный API-шлюз. Интеграция с LLM через SSE, управление сессиями.</td></tr>
                <tr><td><a href="https://github.com/Daniil2022Ri/Bank_DDD_Antifraund" target="_blank">Bank_DDD_Antifraud</a></td><td>Java 17, Spring Cloud, DDD, CQRS</td><td>Архитектурный прототип антифрод-системы банка с асинхронной коммуникацией.</td></tr>
                <tr><td><a href="https://github.com/Daniil2022Ri/SpringSercutiry_V2" target="_blank">SpringSecurity_V2</a></td><td>Java 17, Spring Security, JWT</td><td>Централизованный сервис аутентификации (RBAC, OAuth2, Rate Limiting).</td></tr>
                <tr><td><a href="https://github.com/Daniil2022Ri/MVC_Hibernate" target="_blank">MVC_Hibernate</a></td><td>Java 11, Hibernate, PostgreSQL</td><td>Оптимизированный Data Access Layer. Решение N+1, L2-кэш, сложные HQL.</td></tr>
              </tbody>
            </table>

  <h3>Frontend & API</h3>
            <table>
              <thead><tr><th>Проект</th><th>Стек</th><th>Ссылка</th></tr></thead>
              <tbody>
                <tr><td>TechStore</td><td>Vue 3, Pinia, CSS Grid</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_Gadjet_Store/index.html" target="_blank">Открыть ↗</a></td></tr>
                <tr><td>Sneaker Store</td><td>React 18, CSS Animations</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_shooth_Store/index.html" target="_blank">Открыть ↗</a></td></tr>
                <tr><td>Travel Portal</td><td>React 18, Lazy Loading</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_Travel_Store/index.html" target="_blank">Открыть ↗</a></td></tr>
                <tr><td>WeatherApp 🟢</td><td>React, Open-Meteo API</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Web_API_sites/Weather_monitoring_site/index.html" target="_blank">Открыть ↗</a></td></tr>
                <tr><td>CurrencyHub 🟢</td><td>React, ExchangeRate API</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Web_API_sites/CurrencyHub/index.html" target="_blank">Открыть ↗</a></td></tr>
              </tbody>
            </table>
          </div>
        </details>

  <details>
          <summary>🇬🇧 English</summary>
          <div class="content">
            <h2>⚡ About Me</h2>
            <pre><code>$ whoami
&gt; Daniil Rybiyakov | Fullstack Developer

$ cat focus.txt
&gt; Microservices, Event-Driven Architecture, Clean Code, Pixel-Perfect UI

$ uptime
&gt; 4+ years of commercial development</code></pre>
            <ul>
              <li>🔥 <strong>Backend:</strong> Java 17/21, Spring Boot, Spring Cloud, Spring Security, Kotlin</li>
              <li>🗄️ <strong>Data & Messaging:</strong> PostgreSQL, Redis, Apache Kafka, RabbitMQ, Hibernate/JPA</li>
              <li>🏗️ <strong>Architecture:</strong> Microservices, DDD, CQRS, Event-Driven, REST/gRPC</li>
              <li>🎨 <strong>Frontend:</strong> React 18, Vue 3, TypeScript, Next.js, Tailwind CSS</li>
              <li>🐳 <strong>DevOps & Tools:</strong> Docker, Kubernetes, GitLab CI, Grafana, JUnit 5/Mockito</li>
            </ul>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="gif-br" alt="Blade Runner Rain" />

  <h2>🌐 Portfolio</h2>
            <p align="center">
              <a href="https://daniil2022ri.github.io/Portfolio_FullStack/" target="_blank" class="neon-btn">🌐 Open Portfolio</a>
              <a href="https://daniil2022ri.github.io/Portfolio_FullStack/" target="_blank" class="neon-btn amber">Blade Runner Style</a>
            </p>
            <blockquote>🎬 Portfolio website: React, glitch-effects, interactive cards, and live demo projects.</blockquote>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="gif-br" alt="Blade Runner Rain" />

  <h2>🚀 Projects</h2>
            <h3>Backend</h3>
            <table>
              <thead><tr><th>Project</th><th>Stack</th><th>Description</th></tr></thead>
              <tbody>
                <tr><td><a href="https://github.com/Daniil2022Ri/PaymentService" target="_blank">PaymentService</a></td><td>Java 21, Spring Boot, Kafka, Redis</td><td>High-load payment microservice. Idempotency, retry mechanisms.</td></tr>
                <tr><td><a href="https://github.com/Daniil2022Ri/AIAssistantBackend" target="_blank">AIAssistantBackend</a></td><td>Java 21, WebFlux, OpenAI, Redis</td><td>Reactive API gateway. LLM integration via SSE, session management.</td></tr>
                <tr><td><a href="https://github.com/Daniil2022Ri/Bank_DDD_Antifraund" target="_blank">Bank_DDD_Antifraud</a></td><td>Java 17, Spring Cloud, DDD, CQRS</td><td>Architectural prototype of bank antifraud system with async communication.</td></tr>
                <tr><td><a href="https://github.com/Daniil2022Ri/SpringSercutiry_V2" target="_blank">SpringSecurity_V2</a></td><td>Java 17, Spring Security, JWT</td><td>Centralized auth service (RBAC, OAuth2, Rate Limiting).</td></tr>
                <tr><td><a href="https://github.com/Daniil2022Ri/MVC_Hibernate" target="_blank">MVC_Hibernate</a></td><td>Java 11, Hibernate, PostgreSQL</td><td>Optimized Data Access Layer. N+1 solution, L2-cache, complex HQL.</td></tr>
              </tbody>
            </table>

  <h3>Frontend & API</h3>
            <table>
              <thead><tr><th>Project</th><th>Stack</th><th>Link</th></tr></thead>
              <tbody>
                <tr><td>TechStore</td><td>Vue 3, Pinia, CSS Grid</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_Gadjet_Store/index.html" target="_blank">Open ↗</a></td></tr>
                <tr><td>Sneaker Store</td><td>React 18, CSS Animations</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_shooth_Store/index.html" target="_blank">Open ↗</a></td></tr>
                <tr><td>Travel Portal</td><td>React 18, Lazy Loading</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_Travel_Store/index.html" target="_blank">Open ↗</a></td></tr>
                <tr><td>WeatherApp 🟢</td><td>React, Open-Meteo API</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Web_API_sites/Weather_monitoring_site/index.html" target="_blank">Open ↗</a></td></tr>
                <tr><td>CurrencyHub 🟢</td><td>React, ExchangeRate API</td><td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Web_API_sites/CurrencyHub/index.html" target="_blank">Open ↗</a></td></tr>
              </tbody>
            </table>
          </div>
        </details>

<img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="gif-br" alt="Blade Runner Rain" />

  <h2>📊 GitHub Stats</h2>
        <p align="center" style="margin-bottom: 16px;">
          <img src="https://github-readme-stats.vercel.app/api?username=Daniil2022Ri&show_icons=true&theme=dark&title_color=00ff88&icon_color=00ff88&text_color=e8ddd0&bg_color=0a0608&border_color=1e1e2e" height="180" />
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Daniil2022Ri&layout=compact&theme=dark&title_color=00ff88&text_color=e8ddd0&bg_color=0a0608&border_color=1e1e2e" height="180" />
        </p>
        <p align="center" style="margin-bottom: 16px;">
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=Daniil2022Ri&theme=dark&background=0a0608&border=1e1e2e&stroke=00ff88&ring=00ff88&fire=ff6b6b&currStreakNum=00ff88&sideNums=00ff88&currStreakLabel=e8ddd0&sideLabels=e8ddd0&dates=8b8b8b" height="180" />
        </p>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="gif-br" alt="Blade Runner Rain" />

  <h2>📫 Contacts</h2>
        <p align="center" style="margin-bottom: 24px;">
          <a href="mailto:hhffcgubv@gmail.com" class="neon-btn amber">✉️ Email Me</a>
          <!-- ⚠️ ЗАМЕНИ 'daniil_rybakov_dev' НА СВОЙ РЕАЛЬНЫЙ ЮЗЕРНЕЙМ БЕЗ ОШИБОК -->
          <a href="https://t.me/daniil_rybakov_dev" target="_blank" class="neon-btn">💬 Telegram</a>
        </p>

  <hr />

  <p align="center" style="margin-bottom: 16px;">
          <img src="https://komarev.com/ghpvc/?username=Daniil2022Ri&color=00FF88&style=for-the-badge" />
        </p>

  <p align="center" style="margin-top: 24px;">
          <i style="color: #ff9d00; font-family: 'JetBrains Mono', monospace; font-size: 0.9em; text-shadow: 0 0 10px rgba(255, 157, 0, 0.5);">
            // Building resilient, scalable systems. Clean code, pixel-perfect execution.
          </i>
        </p>
      </div>
  </div>
  </foreignObject>
</svg>
