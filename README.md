<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f2027,50:203a43,100:2c5364&text=Dmitry%20Miroshnikov&fontColor=ffffff&fontSize=48&fontAlignY=34&desc=Backend-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%87%D0%B8%D0%BA%20%C2%B7%20Kotlin%20%2F%20Java&descAlignY=54&descSize=18&animation=fadeIn" alt="banner" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=4FC3F7&center=true&vCenter=true&width=760&lines=6%2B+%D0%BB%D0%B5%D1%82+%D0%B2+backend-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B5;Highload%3A+15+%D0%BC%D0%BB%D0%BD+%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%D0%BE%D0%B2+%D0%B2+%D0%B4%D0%B5%D0%BD%D1%8C;OCR+%2B+LLM+%D0%B2+%D0%B1%D0%B0%D0%BD%D0%BA%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D1%85+%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%B0%D1%85;BPMN%2C+Kafka%2C+Spring%2C+PostgreSQL" alt="typing" />

<br/>

<a href="https://t.me/miroshnikooov">
  <img src="https://img.shields.io/badge/Telegram-%40miroshnikooov-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="telegram" />
</a>
<img src="https://img.shields.io/badge/%D0%9C%D0%BE%D1%81%D0%BA%D0%B2%D0%B0-203a43?style=for-the-badge&logo=googlemaps&logoColor=white" alt="location" />
<img src="https://img.shields.io/badge/%D0%9E%D0%BF%D1%8B%D1%82-6%20%D0%BB%D0%B5%D1%82-2c5364?style=for-the-badge" alt="experience" />
<img src="https://komarev.com/ghpvc/?username=MirFlames&style=for-the-badge&color=0f2027&label=%D0%9F%D0%A0%D0%9E%D0%A1%D0%9C%D0%9E%D0%A2%D0%A0%D0%9E%D0%92" alt="views" />

</div>

---

## 👋 Обо мне

- 🏦 Backend-разработчик в **Лиге Цифровой Экономики**, пишу на **Kotlin/Java** для проектов Сбербанка
- ⚙️ Специализация — интеграционные слои и бизнес-логика там, где нагрузка измеряется миллионами запросов в сутки
- 🤖 Втаскиваю **OCR и LLM** в банковские бизнес-процессы: от FSM-фреймворка до дедупликации потока документов
- 🔀 Проектирую связку **BPMN ↔ Java**: где логика живёт в процессе, а где в прикладном сервисе
- 🧪 В пет-проектах — мультиагентные AI-схемы, TDD-контроль над AI-сгенерированным кодом и CI/CD от идеи до релиза
- 🎓 СФУ, Институт космических и информационных технологий — «Информатика и вычислительная техника»
- 🌍 Русский — родной, английский — B2

---

## 🛠 Стек

<div align="center">

<img src="https://skillicons.dev/icons?i=kotlin,java,spring,kafka,postgres,hibernate,docker,kubernetes&theme=dark" alt="stack-1" />
<br/>
<img src="https://skillicons.dev/icons?i=jenkins,gradle,maven,git,go,vue,react,idea&theme=dark" alt="stack-2" />

<br/><br/>

<img src="https://img.shields.io/badge/Java-8%20%2F%2011%20%2F%2017-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="java" />
<img src="https://img.shields.io/badge/Spring%20Cloud-Gateway%20%C2%B7%20Eureka%20%C2%B7%20LB-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="spring-cloud" />
<img src="https://img.shields.io/badge/Oracle-SQL-F80000?style=flat-square&logo=oracle&logoColor=white" alt="oracle" />
<img src="https://img.shields.io/badge/Activiti-BPM-1F8ACB?style=flat-square" alt="activiti" />
<img src="https://img.shields.io/badge/Platform%20V-Flow-21A038?style=flat-square" alt="platformv" />
<img src="https://img.shields.io/badge/LLM-OCR-8E44AD?style=flat-square" alt="llm-ocr" />

</div>

---

## 💼 Опыт — 6 лет 1 месяц

<details open>
<summary><b>🏦 Лига Цифровой Экономики</b> — Kotlin/Java-разработчик · май 2023 — н.в.</summary>

<br/>

**«Интеллектуальное распознавание документов»** — интеграционный слой между ML-инструментами (OCR, LLM) и бизнес-процессами банка

- Внедрил дедупликацию входящих документов по хэшу **до этапа OCR**: повторы (~0,5% потока) перестали проходить пайплайн OCR+LLM — экономия порядка **десятков млн ₽ в год** на инференсе
- Локализовал и устранил дефект интеграционного слоя, из-за которого терялись транзакции: снял с ручного восстановления **~100 тыс. документов** и прекратил дальнейшие потери
- Разрабатывал и поддерживал прослойку на самописном **FSM-фреймворке** для снижения издержек внедрения ИИ-инструментов: **15 млн запросов/день**, **90+ бизнес-процессов**, еженедельное дежурство на тестовом контуре

**«Безбумажный офис»** — слой бизнес-логики системы электронного документооборота банка

- Спроектировал и в срок вывел отдельный микросервис под новый контракт смежной крипто-АС со слоем обратной совместимости — миграция без поломки существующих потребителей
- Самостоятельно поднял дефицитную экспертизу по **legacy-BPM** и в срок выпустил пилот миграции бизнес-процессов с зарубежного BPM
- Принимал архитектурные решения о распределении логики между **BPMN** и прикладными сервисами, реализовал точки соединения BPMN ↔ Java через REST
- Закладывал производительность: индексы, пакетная обработка, параллельное выполнение, таймауты, rate-limiter
- Онбординг разработчиков, code review, покрытие модульными и интеграционными тестами

`Java 8/11/17` `Kotlin` `Spring Boot` `Hibernate/JPA` `Kafka` `PostgreSQL` `Oracle SQL` `Platform V Flow (Activiti BPM)` `LLM` `OCR`

</details>

<details>
<summary><b>📊 Intabia</b> — Java-разработчик · июнь 2020 — май 2023</summary>

<br/>

**«Risk Engine»** — гибкая система скоринга заёмщиков для кредитной организации

- Оптимизировал производительность сервисов по результатам нагрузочного тестирования
- В продуктовой Scrum-команде (9 разработчиков) участвовал в оценке задач, code review и покрытии кода тестами для быстрой доставки фич

**«ERP»** — модульная система планирования предприятия

- Разрабатывал и поддерживал модули системы, проводил рефакторинг, покрывал код модульными и интеграционными тестами

`Java 8/11` `Spring Boot` `Spring Data/Hibernate` `Spring Cloud` `Kafka` `PostgreSQL` `Docker` `Jenkins` `Gradle/Maven`

</details>

---

## 📈 Что за этим стоит в цифрах

| Что сделал | Что это дало |
| --- | --- |
| Дедупликация документов по хэшу до OCR | ~0,5% потока мимо пайплайна → десятки млн ₽/год на инференсе |
| Починил дефект интеграционного слоя | ~100 тыс. документов сняты с ручного восстановления |
| Прослойка на самописном FSM-фреймворке | 90+ бизнес-процессов под нагрузкой 15 млн запросов/день |
| Микросервис под новый контракт крипто-АС | Миграция без поломки существующих потребителей |
| Пилот миграции с зарубежного BPM | Дефицитная экспертиза поднята с нуля, релиз в срок |

---

## 🚀 Проекты

<div align="center">

<a href="https://github.com/MirFlames/launcher">
  <img src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=MirFlames&repo=launcher&theme=tokyonight&hide_border=true&bg_color=00000000" alt="launcher" />
</a>
<a href="https://github.com/MirFlames/branch-skill">
  <img src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=MirFlames&repo=branch-skill&theme=tokyonight&hide_border=true&bg_color=00000000" alt="branch-skill" />
</a>
<br/>
<a href="https://github.com/MirFlames/discord-admin-bot">
  <img src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=MirFlames&repo=discord-admin-bot&theme=tokyonight&hide_border=true&bg_color=00000000" alt="discord-admin-bot" />
</a>
<a href="https://github.com/MirFlames/mirflames.github.io">
  <img src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=MirFlames&repo=mirflames.github.io&theme=tokyonight&hide_border=true&bg_color=00000000" alt="personal-page" />
</a>

</div>

> **Пет-проекты:** full-cycle MVP на новом для себя стеке — `Go` + `Wails` + `Vue.js` + `React`. Заодно обкатываю мультиагентные AI-схемы и TDD-контроль над AI-сгенерированным кодом.

---

## 📊 Статистика

<div align="center">

<img src="https://github-readme-stats-salesp07.vercel.app/api?username=MirFlames&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&include_all_commits=true&count_private=true&locale=ru" alt="stats" height="170" />
<img src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=MirFlames&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000&langs_count=8&locale=ru" alt="top-langs" height="170" />

<br/>

<img src="https://streak-stats.demolab.com?user=MirFlames&theme=tokyonight&hide_border=true&background=00000000&locale=ru" alt="streak" />

<br/>

<img src="https://github-trophies.vercel.app/?username=MirFlames&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8&rank=SSS,SS,S,AAA,AA,A,B,C" alt="trophies" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MirFlames&theme=tokyo-night&hide_border=true&bg_color=00000000&area=true" alt="activity" width="100%" />

<br/>

<img src="https://raw.githubusercontent.com/MirFlames/mirflames/refs/heads/output/snake.svg" alt="snake" width="100%" />

</div>

---

<div align="center">

### 📬 Открыт к предложениям

<a href="https://t.me/miroshnikooov">
  <img src="https://img.shields.io/badge/%D0%9D%D0%B0%D0%BF%D0%B8%D1%81%D0%B0%D1%82%D1%8C%20%D0%B2%20Telegram-%40miroshnikooov-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="telegram-footer" />
</a>

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:2c5364,50:203a43,100:0f2027" alt="footer" width="100%" />

</div>
