<svg xmlns="http://www.w3.org/2000/svg" width="100%">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        .br-container {
          background-color: #0a0608;
          background-image: 
            linear-gradient(rgba(0, 255, 136, 0.04) 1px, transparent 1px),
            linear-gradient(90deg, rgba(0, 255, 136, 0.04) 1px, transparent 1px),
            radial-gradient(circle at 20% 30%, rgba(255, 166, 0, 0.15) 0%, transparent 40%),
            radial-gradient(circle at 80% 70%, rgba(212, 7, 0, 0.1) 0%, transparent 40%);
          background-size: 40px 40px, 40px 40px, 100% 100%, 100% 100%;
          color: #e8ddd0;
          padding: 40px 24px;
          font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
          position: relative;
          overflow: hidden;
          min-height: 100vh;
        }
        .br-container::before {
          content: '';
          position: absolute;
          inset: 0;
          background: repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0,0,0,0.15) 2px, rgba(0,0,0,0.15) 4px);
          pointer-events: none;
          z-index: 1;
          animation: scan 8s linear infinite;
        }
        @keyframes scan {
          0% { transform: translateY(0); }
          100% { transform: translateY(10px); }
        }
        .br-content { position: relative; z-index: 2; }
        .br-lang-indicator {
          display: inline-block;
          padding: 6px 14px;
          background: rgba(0, 255, 136, 0.08);
          border: 1px solid rgba(0, 255, 136, 0.3);
          border-radius: 4px;
          font-family: 'JetBrains Mono', monospace;
          font-size: 0.75rem;
          color: #00FF88;
          letter-spacing: 0.15em;
          margin-bottom: 24px;
          animation: pulse-glow 3s ease-in-out infinite;
        }
        @keyframes pulse-glow {
          0%, 100% { box-shadow: 0 0 10px rgba(0, 255, 136, 0.2); }
          50% { box-shadow: 0 0 20px rgba(0, 255, 136, 0.5); }
        }
        .br-title-ru {
          font-size: 1.3rem;
          font-weight: 700;
          color: #e8ddd0;
          margin: 8px 0 4px 0;
          font-family: 'JetBrains Mono', monospace;
        }
        .br-title-en {
          font-size: 0.85rem;
          color: #8a7e72;
          font-style: italic;
          margin-bottom: 12px;
          font-family: 'JetBrains Mono', monospace;
        }
        .br-text-ru {
          font-size: 0.95rem;
          color: #e8ddd0;
          line-height: 1.6;
          margin-bottom: 4px;
        }
        .br-text-en {
          font-size: 0.8rem;
          color: #8a7e72;
          font-style: italic;
          line-height: 1.5;
          margin-bottom: 16px;
        }
        .br-hr {
          border: 0;
          height: 1px;
          background: linear-gradient(90deg, transparent, rgba(0, 255, 136, 0.3), transparent);
          margin: 32px 0;
        }
        .br-h2-ru {
          color: #00FF88;
          font-size: 1.4rem;
          font-weight: 700;
          margin-bottom: 4px;
          text-shadow: 0 0 10px rgba(0, 255, 136, 0.3);
        }
        .br-h2-en {
          color: #ffa600;
          font-size: 0.85rem;
          font-family: 'JetBrains Mono', monospace;
          letter-spacing: 0.1em;
          margin-bottom: 20px;
          text-transform: uppercase;
        }
        .br-pre {
          background: rgba(0,0,0,0.5);
          border-left: 3px solid #00FF88;
          padding: 16px;
          border-radius: 4px;
          color: #e8ddd0;
          font-family: 'JetBrains Mono', monospace;
          font-size: 0.85rem;
          margin-bottom: 24px;
          box-shadow: inset 0 0 20px rgba(0, 255, 136, 0.05);
        }
        .br-list { list-style: none; padding: 0; margin: 0 0 24px 0; }
        .br-list li { margin-bottom: 10px; padding: 8px 12px; background: rgba(255,255,255,0.02); border-radius: 4px; border-left: 2px solid #ffa600; }
        .br-table { width: 100%; border-collapse: collapse; font-size: 0.85rem; margin-bottom: 24px; background: rgba(0,0,0,0.3); border-radius: 8px; overflow: hidden; }
        .br-table th { background: rgba(0, 255, 136, 0.1); color: #00FF88; text-align: left; padding: 12px 8px; font-family: 'JetBrains Mono', monospace; font-size: 0.75rem; letter-spacing: 0.1em; }
        .br-table td { padding: 12px 8px; border-top: 1px solid rgba(255,255,255,0.05); }
        .br-table a { color: #00FF88; text-decoration: none; font-weight: 600; }
        .br-table .br-sub { color: #8a7e72; font-size: 0.75rem; font-style: italic; display: block; }
        .br-quote { border-left: 3px solid #ffa600; padding: 12px 16px; background: rgba(255, 166, 0, 0.05); margin: 16px 0; }
        .br-quote .ru { color: #e8ddd0; font-style: italic; font-size: 0.9rem; }
        .br-quote .en { color: #8a7e72; font-style: italic; font-size: 0.75rem; margin-top: 4px; }
        .br-gif { width: 100%; border-radius: 8px; margin: 16px 0; border: 1px solid rgba(0, 255, 136, 0.2); }
      </style>

  <div class="br-container">
        <div class="br-content">
          
  <div align="center">
            <span class="br-lang-indicator">[ LANGUAGE • RU / EN ]</span>
          </div>

  <h1 align="center" style="margin: 20px 0;">
            <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=00FF88&center=true&vCenter=true&width=600&lines=FULLSTACK+DEVELOPER;Java+%7C+Spring+%7C+React+%7C+Vue;4%2B+Years+Experience;Microservices+%7C+Event-Driven;Clean+Code+%7C+Pixel-Perfect+UI" alt="Typing SVG" />
          </h1>

  <p align="center">
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

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="br-gif" alt="Blade Runner Rain" />
          <hr class="br-hr" />

  <div class="br-h2-ru">⚡ Обо мне</div>
          <div class="br-h2-en">// ABOUT ME</div>

  <pre class="br-pre">$ whoami
&gt; Daniil Rybiyakov | Fullstack Developer

$ cat focus.txt  
&gt; Microservices, Event-Driven Architecture, Clean Code, Pixel-Perfect UI

$ uptime
&gt; 4+ years of commercial development</pre>

  <ul class="br-list">
            <li>🔥 <strong>Backend:</strong> Java 17/21, Spring Boot, Spring Cloud, Spring Security, Kotlin</li>
            <li>🗄️ <strong>Data &amp; Messaging:</strong> PostgreSQL, Redis, Apache Kafka, RabbitMQ, Hibernate/JPA</li>
            <li>🏗️ <strong>Architecture:</strong> Microservices, DDD, CQRS, Event-Driven, REST/gRPC</li>
            <li>🎨 <strong>Frontend:</strong> React 18, Vue 3, TypeScript, Next.js, Tailwind CSS</li>
            <li>🐳 <strong>DevOps &amp; Tools:</strong> Docker, Kubernetes, GitLab CI, Grafana, JUnit 5/Mockito</li>
          </ul>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="br-gif" alt="Blade Runner Rain" />
          <hr class="br-hr" />

  <div class="br-h2-ru">🌐 Портфолио</div>
          <div class="br-h2-en">// PORTFOLIO</div>

  <p align="center">
            <a href="https://daniil2022ri.github.io/Portfolio_FullStack/" target="_blank">
              <img src="https://img.shields.io/badge/🌐_PORTFOLIO-00FF88?style=for-the-badge&logo=google-chrome&logoColor=0a0608&labelColor=00FF88&color=0a0608" />
            </a>
            <a href="https://daniil2022ri.github.io/Portfolio_FullStack/" target="_blank">
              <img src="https://img.shields.io/static/v1?label=&message=BLADE+RUNNER+STYLE&color=0a0608&style=for-the-badge&logo=react&logoColor=00FF88" />
            </a>
          </p>

  <div class="br-quote">
            <div class="ru">🎬 Сайт-портфолио: React, glitch-эффекты, интерактивные карточки и живые демо-проекты.</div>
            <div class="en">Portfolio website: React, glitch effects, interactive cards and live demo projects.</div>
          </div>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="br-gif" alt="Blade Runner Rain" />
          <hr class="br-hr" />

  <div class="br-h2-ru">🚀 Проекты</div>
          <div class="br-h2-en">// PROJECTS</div>

  <div class="br-title-ru">Backend</div>
          <div class="br-title-en">Server-side development</div>

  <table class="br-table">
            <thead>
              <tr>
                <th>PROJECT</th>
                <th>STACK</th>
                <th>DESCRIPTION</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td><a href="https://github.com/Daniil2022Ri/PaymentService">PaymentService</a></td>
                <td>Java 21, Spring Boot, Kafka, Redis</td>
                <td>Высоконагруженный микросервис платежей. Идемпотентность, retry-механизмы.<span class="br-sub">High-load payment microservice. Idempotency, retry mechanisms.</span></td>
              </tr>
              <tr>
                <td><a href="https://github.com/Daniil2022Ri/AIAssistantBackend">AIAssistantBackend</a></td>
                <td>Java 21, WebFlux, OpenAI, Redis</td>
                <td>Реактивный API-шлюз. Интеграция с LLM через SSE.<span class="br-sub">Reactive API gateway. LLM integration via SSE.</span></td>
              </tr>
              <tr>
                <td><a href="https://github.com/Daniil2022Ri/Bank_DDD_Antifraund">Bank_DDD_Antifraud</a></td>
                <td>Java 17, Spring Cloud, DDD, CQRS</td>
                <td>Прототип антифрод-системы с асинхронной коммуникацией.<span class="br-sub">Antifraud system prototype with async communication.</span></td>
              </tr>
              <tr>
                <td><a href="https://github.com/Daniil2022Ri/SpringSercutiry_V2">SpringSecurity_V2</a></td>
                <td>Java 17, Spring Security, JWT</td>
                <td>Централизованный сервис аутентификации (RBAC, OAuth2).<span class="br-sub">Centralized auth service (RBAC, OAuth2).</span></td>
              </tr>
              <tr>
                <td><a href="https://github.com/Daniil2022Ri/MVC_Hibernate">MVC_Hibernate</a></td>
                <td>Java 11, Hibernate, PostgreSQL</td>
                <td>Оптимизированный DAL. Решение N+1, L2-кэш, сложные HQL.<span class="br-sub">Optimized DAL. N+1 solution, L2 cache, complex HQL.</span></td>
              </tr>
            </tbody>
          </table>

  <div class="br-title-ru">Frontend &amp; API</div>
          <div class="br-title-en">Client-side &amp; integrations</div>

  <table class="br-table">
            <thead>
              <tr>
                <th>PROJECT</th>
                <th>STACK</th>
                <th>LINK</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>TechStore</td>
                <td>Vue 3, Pinia, CSS Grid</td>
                <td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_Gadjet_Store/index.html">Открыть / Open ↗</a></td>
              </tr>
              <tr>
                <td>Sneaker Store</td>
                <td>React 18, CSS Animations</td>
                <td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_shooth_Store/index.html">Открыть / Open ↗</a></td>
              </tr>
              <tr>
                <td>Travel Portal</td>
                <td>React 18, Lazy Loading</td>
                <td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Normal_verstka_Web/Site_Travel_Store/index.html">Открыть / Open ↗</a></td>
              </tr>
              <tr>
                <td>WeatherApp 🟢</td>
                <td>React, Open-Meteo API</td>
                <td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Web_API_sites/Weather_monitoring_site/index.html">Открыть / Open ↗</a></td>
              </tr>
              <tr>
                <td>CurrencyHub 🟢</td>
                <td>React, ExchangeRate API</td>
                <td><a href="https://daniil2022ri.github.io/Portfolio_FullStack/Web_API_sites/CurrencyHub/index.html">Открыть / Open ↗</a></td>
              </tr>
            </tbody>
          </table>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="br-gif" alt="Blade Runner Rain" />
          <hr class="br-hr" />

  <div class="br-h2-ru">📊 Статистика</div>
          <div class="br-h2-en">// STATISTICS</div>

  <p align="center">
            <img src="https://github-readme-stats.vercel.app/api?username=Daniil2022Ri&show_icons=true&theme=dark&title_color=00ff88&icon_color=00ff88&text_color=e8ddd0&bg_color=0a0608&border_color=1e1e2e" height="180" />
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Daniil2022Ri&layout=compact&theme=dark&title_color=00ff88&text_color=e8ddd0&bg_color=0a0608&border_color=1e1e2e" height="180" />
          </p>
          <p align="center">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=Daniil2022Ri&theme=dark&background=0a0608&border=1e1e2e&stroke=00ff88&ring=00ff88&fire=ff6b6b&currStreakNum=00ff88&sideNums=00ff88&currStreakLabel=e8ddd0&sideLabels=e8ddd0&dates=8b8b8b" height="180" />
          </p>

  <img src="https://raw.githubusercontent.com/Daniil2022Ri/Daniil2022Ri/main/PlasmaBladeRunner_1.gif" class="br-gif" alt="Blade Runner Rain" />
          <hr class="br-hr" />

  <div class="br-h2-ru">📫 Контакты</div>
          <div class="br-h2-en">// CONTACTS</div>

  <p align="center">
            <a href="mailto:hhffcgubv@gmail.com">
              <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&color=0a0608&labelColor=00FF88" />
            </a>
            <a href="https://t.me/danilRyDeveloperFullStack">
              <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&color=0a0608&labelColor=00FF88" />
            </a>
          </p>

  <hr class="br-hr" />

  <p align="center">
            <img src="https://komarev.com/ghpvc/?username=Daniil2022Ri&color=00FF88&style=for-the-badge" />
          </p>

  <p align="center" style="margin-top: 24px;">
            <i style="color: #00FF88; font-family: 'JetBrains Mono', monospace; font-size: 0.85em;">
              // Building resilient, scalable systems. Clean code, pixel-perfect execution.
            </i>
          </p>

  </div>
      </div>
    </div>
  </foreignObject>
</svg>
