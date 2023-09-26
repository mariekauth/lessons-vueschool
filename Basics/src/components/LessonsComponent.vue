<script setup>
import LessonItem from './Lessons/LessonItem.vue'
import LessonOne from './Lessons/LessonOne.vue'
</script>
<template>
  <LessonItem>
    <template #heading>Lesson One</template>
    <template #lesson><LessonOne /></template>
    The template tag. Place basic HTML within the template tag.<br />
    I have chosen to use Single-File Component (SFC) format to complete the tutorial.
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Two</template>
    <template #lesson><LessonTwo /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Three</template>
    <template #lesson><LessonThree /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Four</template>
    <template #lesson><LessonFour /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Five</template>
    <template #lesson><LessonFive /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Six</template>
    <template #lesson><LessonSix /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Seven</template>
    <template #lesson><LessonSeven /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Eight</template>
    <template #lesson><LessonEight /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Nine</template>
    <template #lesson><LessonNine /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Ten</template>
    <template #lesson><LessonTen /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Eleven</template>
    <template #lesson><LessonEleven /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Twelve</template>
    <template #lesson><LessonTwelve /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Thirteen</template>
    <template #lesson><LessonThirteen /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Fourteen</template>
    <template #lesson><LessonFourteen /></template>
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Fifteen</template>
    <template #lesson><LessonFifteen /></template>
    <hr />
  </LessonItem>
</template>
<style scoped>
</style>