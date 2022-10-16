<template>
  <Container>
    <div class="cases">
      <h4 class="casesHeading">
        Кейсы
      </h4>
      <div class="casesBank">
        <div class="casesBankImg">
          <div class="casesBankImgName">
            <span>
              корпоративный сайт
            </span>
            <span>
              2022
            </span>
          </div>
          <img src="~/assets/images/bank.png" alt="bank" class="casesBankImgPic">
        </div>
        <div class="casesBankText">
          <h3 class="casesBankTextHeading">
            Новый сайт банка «Центр-инвест»
          </h3>
          <p class="casesBankTextDescription">
            C 25 апреля 2022 года банк «Центр-инвест» запустил новую версию сайта centrinvest.ru. 
            Полномасштабный редизайн обеспечит функциональное преимущество и удобство для клиентов.
          </p>
          <p class="casesBankTextDescription">
            Новый ресурс отличается современным дизайном, усовершенствованной структурой 
            и удобной системой навигации, которая упростит клиентам поиск нужной информации
            и процесс коммуникации с банком.
          </p>
        </div>
      </div>
      <div class="allCases">
        <div class="allCasesOne">
          <div class="allCasesOne1">
            <div class="allCasesOne1Name">
              <span>
                корпоративный сайт
              </span>
              <span>
                2019
              </span>
            </div>
            <img src="~/assets/images/realBot.png" alt="логотип компании" class="allCasesOne1Logo">
            <img src="~/assets/images/bot.png" alt="робот" class="allCasesOne1Bot">
            <p class="allCasesOne1Description">
              Умный ассистент для размещения объявлений о продаже и аренде недвижимости
            </p>
          </div>
          <h4 class="allCasesHeading casesHeadingBlock1">
              Бот для Маралин Ру 
            </h4>
          <div class="allCasesOne2">
            <div class="allCasesOne2Name">
              <span>
                корпоративный сайт
              </span>
              <span>
                2019
              </span>
            </div>
            <img src="~/assets/images/women.png" alt="логотип компании" class="allCasesOne2Logo">
            <p class="allCasesOne2Description">
              Каждая женщина, которая начинает свой бизнес, 
              меняет мир вокруг себя и создает новый кластер.
            </p>
          </div>
          <h4 class="allCasesHeading">
              Сайт для...
            </h4>
        </div>
        <div class="allCasesTwo">
          <div class="allCasesOne3">
            <span>
              приложение
            </span>
            <span>
              2016
            </span>
          </div>
          <h4 class="allCasesHeading">
            Приложение Маралин Ру 
           </h4>
        </div>
      </div>
      <a href="#" class="allCasesBtn">
        <p class="allCasesBtnText">
          Все кейсы
        </p>
        <img src="~/assets/images/arrow.png" alt="стрелка">
      </a>
    </div>
  </Container>
</template>

<script>
import Container from '~/components/uikit/Container';

export default {
  components: {
    Container
  },
}
</script>

<style lang="scss">
  @import '~/components/indexPage/Cases/styles';
</style>