<template>
  <div class="accordionBlock">
    <div class="accordionDescription">
      <h2>
        Открытые вакансии
      </h2>
    </div>
    <div class="ac-container">
      <div>
        <input id="ac-1" name="accordion-1" type="checkbox" />
        <label for="ac-1" >
          <div class="accordion" @click="open = !open">
            <div>
              <span class="accordionHeading">
                Frontend Developer
              </span>
              <div class="accordionList">
                <TagsList :list="list1" />
              </div>
            </div>
            <div>
              <img src="~/assets/images/arrowAcc.png" alt="" class="accordionplus" :class="{opened: open}">
            </div>
          </div>
        </label>
        <article>
          <div class="articleBlock">
            <h3 class="articleBlockHeading">
              В процессе работы нужно будет:
            </h3>
            <ul>
              <li class="articleBlockList">
                тестировать приложения и смотреть, что из этого выйдет;
              </li>
              <li class="articleBlockList">  
                взаимодействовать с нашими разработчиками,дизайнерами,
                менеджерами,аналитиками и другими членами команды;
              </li>
              <li class="articleBlockList">
                улучшать текущие процессы и развивать проекты вместе с нами;
              </li>
              <li class="articleBlockList">
                расти и помогать расти другим ребятам.
              </li>
            </ul>
            <h3 class="articleBlockHeading">
              Что мы ждем от тебя:
            </h3>
            <ul>
              <li class="articleBlockList">чтобы ты был паинькой</li>
              <li class="articleBlockList">чтобы ты был паинькой</li>
              <li class="articleBlockList">чтобы ты был паинькой</li>
              <li class="articleBlockList">чтобы ты был паинькой</li>
              <li class="articleBlockList">чтобы ты был паинькой</li>
              <li class="articleBlockList">чтобы ты был паинькой</li>
              <li class="articleBlockList">чтобы ты был паинькой</li>
              <li class="articleBlockList">чтобы ты был паинькой</li>
            </ul>
          </div>
        </article>
      </div>
      <div>
        <input id="ac-2" name="accordion-1" type="checkbox" />
        <label for="ac-2">
          <div class="accordion">
            <div>
              <span class="accordionHeading">
                Backend Developer
              </span>
              <div>
                <TagsList :list="list2" />
              </div>
            </div>
            <div>
              <img src="~/assets/images/arrowAcc.png" alt="" class="accordionplus">
            </div>
          </div>
        </label>
        <article>
          <p>
            Lorem ipsum dolor sit amet, consectetur 
            adipisicing elit. Minima, ducimus modi non aperiam 
            placeat ipsum atque reprehenderit amet sunt expedita explicabo 
            assumenda? Debitis deleniti officiis ipsum veniam quos repellat expedita?
          </p>
        </article>
      </div>
      <div>
        <input id="ac-3" name="accordion-1" type="checkbox" />
        <label for="ac-3">
          <div class="accordion bord">
            <div>
              <span class="accordionHeading">
                QA engineer
              </span>
              <div>
                <TagsList :list="list3" />
              </div>
            </div>
            <div>
              <img src="~/assets/images/arrowAcc.png" alt="" class="accordionplus">
            </div>
          </div>
        </label>
        <article>
          <p>
            Lorem ipsum dolor sit amet, consectetur 
            adipisicing elit. Minima, ducimus modi non aperiam 
            placeat ipsum atque reprehenderit amet sunt expedita explicabo 
            assumenda? Debitis deleniti officiis ipsum veniam quos repellat expedita?
          </p>
        </article>
      </div>
    </div>
  </div>
</template>

<script>
import TagsList from "~/components/uikit/TagsList";

export default {
  name: "Index",
  components: {
    TagsList
  },
  props: {
    list1: {
      type: Array,
      default: []
    },
    list2: {
      type: Array,
      default: []
    },
    list3: {
      type: Array,
      default: []
    },
  },
  data() {
    return {
      open: false,
    }
  },
}
</script>

<style lang="scss">
  @import '~/components/jobPage/AccordionBlock/styles';
</style>