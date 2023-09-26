<script setup>
import LessonItem from './Lessons/LessonItem.vue'
import LessonOne from './Lessons/LessonOne.vue'
import LessonTwo from './Lessons/LessonTwo.vue'
import LessonThree from './Lessons/LessonThree.vue'
import LessonFour from './Lessons/LessonFour.vue'
import LessonFive from './Lessons/LessonFive.vue'
import LessonSix from './Lessons/LessonSix.vue'
import LessonSeven from './Lessons/LessonSeven.vue'
import LessonEight from './Lessons/LessonEight.vue'
import LessonNine from './Lessons/LessonNine.vue'
import LessonTen from './Lessons/LessonTen.vue'
import LessonEleven from './Lessons/LessonEleven.vue'
import LessonTwelve from './Lessons/LessonTwelve.vue'
import LessonThirteen from './Lessons/LessonThirteen.vue'
import LessonFourteen from './Lessons/LessonFourteen.vue'
import LessonFifteen from './Lessons/LessonFifteen.vue'
</script>
<template>
  <LessonItem>
    <template #heading>Lesson One - Getting Started</template>
    <template #lesson><LessonOne /></template>
    The template tag. Place basic HTML within the template tag.<br />
    I have chosen to use Single-File Component (SFC) format to complete the tutorial.
    <hr />
  </LessonItem>
  <LessonItem>
    <template #heading>Lesson Two - Declarative Rendering</template>
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