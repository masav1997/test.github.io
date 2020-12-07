<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="utf-8" />
    <title>Лайкмебель</title>
    <link rel="stylesheet" href="./css/style.css" />
  </head>
  <body>
    <header class="header">
      <img
        class="header__logo"
        src="img/Logo.svg"
        alt="Лайкмебель.рф. Вам точно понравится!"
      />
      <h3 class="header__title">
        Изготавливаем и устанавливаем <br />
        кухни в Москве и области с 2004 года
      </h3>
      <div class="header__status">
        <a class="header__status-tel" href="tel:+79955085117"
          >+7 (995) 508-51-17</a
        >
        <p class="header__status-title">сейчас работаем</p>
      </div>
    </header>

    <section class="main">
      <h1 class="main__header">
        Современные Комфортные Кухни
        <span class="main__header-orange">с пожизненной гарантией</span>
      </h1>
      <div class="main-block">
        <div class="description">
          <h2 class="description__title">Тренды дизайна кухни 2020 г.</h2>
          <div class="description__info">
            <div class="description__info-photo">
              <img src="./img/icon1.png" alt="Удобно 100%" />
            </div>
            <div class="description__info-arrow">
            </div>
            <div class="description__info-about">
              <p>Максимальное использование пространства и простота в уходе</p>
              <ul class="advantages">
                <li><a href="">Гладкие, ровные поверхности без ручек</a></li>
                <li>
                  <a href=""
                    >«Умные»‎ материалы фасадов — нет отпечатков и царапин</a
                  >
                </li>
              </ul>
            </div>
          </div>
          <p class="description__stock">
            <span class="description__stock-bold">Акция!</span> В честь 16-летия
            фабрики Скидки до 30% до 5 октября
          </p>
          <p class="description__stock-info">
            Рассчитайте стоимость вашей кухни в 3-х комплектациях:
            «Эксклюзивная»‎, «Богатая»‎ и «Хорошая»‎ — <br />
            и зафиксируйте <span>цену по акции</span>
          </p>
          <button class="description__btn" type="submit">
            Рассчитайте стоимость
            <p>за 2 минуты</p>
          </button>
          <div class="main-block__arrow" />
          <div class="main-block__container">
            <img
              class="main-block__icon"
              src="img/icon2.svg"
              alt="Лайкмебель.рф. Вам точно понравится!"
            />
          </div>
        </div>
      </div>
    </section>

    <section class="form">
      <p class="form__title">
        Рассчитайте стоимость вашей кухни в 3-х комплектациях: <br />
        <span class="form__title-bold"
          >«Эксклюзивная»‎, «Богатая»‎ и «Хорошая»</span
        >‎
      </p>
      <div class="progress-bar">
        <div class="progress-bar__scale">1 из 6</div>
      </div>
      <h2 class="form__title1">
        Мы уже приступили к расчёту стоимости кухни!‎
      </h2>
      <div class="form__section">
        <div class="quiz__img"></div>
        <form class="quiz">
          <p class="quiz__title">Как вам удобнее получить результат?</p>
          <ul class="quiz__form">
            <li>
              <input class="quiz__form-input" type="checkbox" name="whatsApp" id="whatsApp" />
              <label for="whatsApp"
                >Пришлите расчет в
                <span class="quiz__form-bold"> WhatsApp</span></label
              >
            </li>
            <li>
              <input class="quiz__form-input" type="checkbox" name="sms" id="sms" />
              <label for="sms"
                >Пришлите расчет ссылкой в
                <span class="quiz__form-bold">SMS</span></label
              >
            </li>
            <li>
              <input class="quiz__form-input" type="checkbox" name="call-back" id="call-back" checked/>
              <label for="call-back"
                >Перезвоните, у меня остались вопросы</label
              >
            </li>
          </ul>
          <p class="quiz__description">
            Введите номер телефона и получите <br> расчет кухни в 3-х комплектациях
          </p>
          <input class="quiz__tel" type="tel" name="tel" id="tel" placeholder="_(___)___-__-__" required>
          <button class="quiz__btn" type="submit" href="mailto:masav1997@gmail.com">Получить результат</button>
        </form>
        <div class="gift">
          <h3 class="gift__title">Ваш подарок</h3>
          <div class="gift__photo"></div>
          <div class="gift__info">
            <div class="gift__info-title">Кухонная мойка</div>
            <div class="gift__surprise">
              <p class="gift__surprise-title">
                <span class="gift__surprise-bold">+ СЮРПРИЗ!</span> Петли с доводчиками на всю кухню
              </p>
            </div>
            <p class="gift__description">
              подарок будет забронирован за вашим номером
            </p>
          </div>
          <p class="gift__conditions">
            Этот подарок вы получите, если закажете кухню у нас
          </p>
          <div class="gift__icon"></div>
        </div>
      </div>
      <div class="form__section-arrow"></div>
      <div class="result">
        <img class="result__img" src="./img/done.svg" alt="Готово!" />
        <p class="result__title">
          Стоимость кухни в 3-х комплектациях сформирована.
        </p>
        <p class="result__description">Она откроется сразу после регистрации</p>
      </div>
      <div class="footer">
        <a href="">Политика конфиденциальности</a>
        <a class="footer__site" href="">Разработано в Quiz24.ru</a>
      </div>
    </section>

    <section class="result__block-disabled">
      <img class="result__block-icon" src="./img/block.svg" alt="Заблокировано">
      <p class="result__block-title" >Стоимость кухни в 3-х комплектациях</p>
    </section>
    <dir class="bg"></dir>
  </body>
  <script src="./js/mask.js"></script>
</html>
