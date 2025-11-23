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
      Я Ольга Газизова 👋
    </span>

  <p class="hero-subtext">
    Начала свою карьеру в IT в роли UX/UI-дизайнера.  
      <br> С 2023 года активно развиваюсь в направлении системного анализа, формулирую функциональные требования и фокусируюсь на создании понятных и качественных продуктов вместе с командой.
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
      <p>Разработка требований и интерфейса приложения для подписи документов</p>
    </div>
  </a>
</div>

<!-- Вставка кода Яндекс.Метрики -->
<!-- ===== Счетчик Яндекс.Метрики ===== -->
<script type="text/javascript">
    (function(m,e,t,r,i,k,a){
        m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
        m[i].l=1*new Date();
        for (var j = 0; j < document.scripts.length; j++) {
            if (document.scripts[j].src === r) { return; }
        }
        k=e.createElement(t), a=e.getElementsByTagName(t)[0], k.async=1, k.src=r, a.parentNode.insertBefore(k,a);
    })(window, document, 'script', 'https://mc.yandex.ru/metrika/tag.js?id=104134099', 'ym');

    ym(104134099, 'init', {ssr:true, clickmap:true, accurateTrackBounce:true, trackLinks:true});
</script>
<noscript><div><img src="https://mc.yandex.ru/watch/104134099" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
<!-- /Счетчик Яндекс.Метрики -->