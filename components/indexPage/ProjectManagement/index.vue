<template>
  <div class="projectManagement">
    <h3 class="projectManagementHeading">
      Технология ведения проектов
    </h3>
    <div class="projectManagementGroup">
      <p class="projectManagementGroupText">
        рабочая группа специалистов на проекте 
      </p>
      <button class="projectManagementGroupBtn1">
        AIC
      </button>
      <button class="projectManagementGroupBtn2">
        QSOFT
      </button>
    </div>
    <div class="projectManagementTime">
      <p class="projectManagementTimeText">
        Среднее соотношение общего и затраченного времени на специалистов на проекте
      </p>
      <div class="projectManagementTimeBlock">
        <span class="projectManagementTimeBlockNumber1">
          684
        </span>
        <div class="projectManagementTimeBlock2">
          <span class="projectManagementTimeBlockNumber2">
            1165
          </span>
          <span class="projectManagementTimeBlockText2">
            часов
          </span>
        </div>
      </div> 
      <div class="blockCircle">
        <div class="blockCircleOne">
          <span class="blockCircleOneText circleText1">
            руководитель проекта
          </span>
          <circle-progress 
            :size="507" 
            :percent="83" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#1B85A3'
            :viewport="true" 
            class="circle1"
          />
          <span class="blockCircleOneText circleText2">
            аналитик
          </span>
          <circle-progress 
            :size="383" 
            :percent="64" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#1B85A3'
            :viewport="true" 
            class="circle2"
          />
          <span class="blockCircleOneText circleText3">
            проектировщик
          </span>
          <circle-progress 
            :size="259" 
            :percent="38" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#1B85A3'
            :viewport="true" 
            class="circle3"
          />
          <span class="blockCircleOneText circleText4">
            дизайнер                
          </span>
          <circle-progress 
            :size="160" 
            :percent="73" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#1B85A3'
            :viewport="true" 
            class="circle4"
          />
          <circle-progress 
            :size="60" 
            :percent="100" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#1B85A3'
            class="circleCentre"
          />
          <img src="~/assets/images/ball.png" alt="ball" class="circleBall">
        </div>
        <div class="blockCircleTwo">
          <span class="blockCircleOneText circleText5">
            ?
          </span>
          <circle-progress 
            :size="507" 
            :percent="83" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#5715AB'
            :viewport="true" 
            class="circle5"
          />
          <span class="blockCircleOneText circleText6">
            ?
          </span>
          <circle-progress 
            :size="383" 
            :percent="64" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#5715AB'
            :viewport="true" 
            class="circle6"
          />
          <span class="blockCircleOneText circleText7">
            ?
          </span>
          <circle-progress 
            :size="259" 
            :percent="38" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#5715AB'
            :viewport="true" 
            class="circle7"
          />
          <span class="blockCircleOneText circleText8">
            ?
          </span>
          <circle-progress 
            :size="160" 
            :percent="73" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#5715AB'
            :viewport="true" 
            class="circle8"
          />
          <circle-progress 
            :size="60" 
            :percent="100" 
            :border-width="4" 
            :border-bg-width="0" 
            fill-color='#1B85A3'
            class="circleCentre2"
          />
          <img src="~/assets/images/ball.png" alt="ball" class="circleBall2">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "vue3-circle-progress/dist/circle-progress.css";
import CircleProgress from "vue3-circle-progress";

export default {
  components: {
    CircleProgress
  },
  setup() {
    const percent = ref(75);

    onMounted(() => {
      setInterval(() => {
        if (percent.value === 25) {
          percent.value = 75;
        } else {
          percent.value = 25;
        }
      }, 1000);
    });

    return {
      percent,
    };
  },
}
</script>

<style lang="scss">
  @import '~/components/indexPage/ProjectManagement/styles';
</style>