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
        <div class="qwert">
          <span class="projectManagementTimeBlockNumber2">
            1165
          </span>
          <span class="">
            часов
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  components: {

  },
}
</script>

<style lang="scss">
  @import '~/components/indexPage/ProjectManagement/styles';
</style>