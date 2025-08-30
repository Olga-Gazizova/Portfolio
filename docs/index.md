---

hide:
  - navigation
  - toc
  - path
  - footer

glightbox: false

slug: "/post1"
metaTitle: "Обо мне"
sort: "1"

---

<!-- ===== Стили только для этой страницы ===== -->
<style>
 .md-typeset h1,
 .md-content__button {
   display: none;
 }

 /* Ссылки под приветствием */
 .hero-links {
   margin-top: 1rem;
   display: flex;
   gap: 1.5rem;
 }

 .hero-links a {
   color: var(--md-typeset-a-color); /* ✅ берём цвет темы */
   text-decoration: none;
   font-weight: 500;
   display: flex;
   align-items: center;
   gap: 0.5rem; /* расстояние между иконкой и текстом */
 }

 .hero-links a:hover {
   text-decoration: underline;
 }

 /* Заголовок перед карточками */
 .section-title {
   font-size: 2rem;
   font-weight: 600;
   margin: 3rem 0 1.5rem 0;
 }
</style>

<!-- ===== Блок "Приветствие" ===== -->
<div class="hero-block">

  <div class="hero-text">
    <span class="hero-title">
      Привет!<br>
      Я Ольга Газизова — продуктовый дизайнер
    </span>

  <p class="hero-subtext">
    Начала в IT как продуктовый менеджер, потом перешла в UX/UI-дизайн.  
      <br>С 2023 года изучаю системный анализ, формулирую требования и осваиваю UML и ООП, чтобы создавать понятные и качественные продукты вместе с командой.
  </p>

  <!-- ✅ Ссылки с иконками -->
  <div class="hero-links">
    <a href="https://t.me/OlgaGazizova" target="_blank">
        Телеграм
    </a>

  <a href="mailto:ongazizova@gmail.com">
        Почта
    </a>

  <a href="./images/Газизова Ольга Николаевна.pdf">
        Резюме
    </a>

  </div>
  </div>

  <!--<div class="hero-photo">
    ![Фото Ольги](assets/photo.png)
  </div>-->

</div>

<!-- ✅ Заголовок перед карточками -->
<h2 class="section-title">Мои работы</h2>

<div class="cards-block">
  <a href="01-case" class="card">
    <img src="images/index-card-01.png" alt="Карточка 1">
    <div class="card-content">
      <h3>Система управление доступом</h3>
      <p>Разработка интерфейса для системы управления устройствами и пользователями</p>
    </div>
  </a>

  <a href="02-case" class="card">
    <img src="images/index-card-02.png" alt="Карточка 2">
    <div class="card-content">
      <h3>Сервис по обзвону должников</h3>
      <p>Улучшение UI/UX интерфейса сервиса для информирования о задолженности</p>
    </div>
  </a>

  <a href="03-case" class="card">
    <img src="images/index-card-03.png" alt="Карточка 3">
    <div class="card-content">
      <h3>Приложение для подписи PDF-документов</h3>
      <p>Разработка интерфейса для электронной подписи документов</p>
    </div>
  </a>
</div>
