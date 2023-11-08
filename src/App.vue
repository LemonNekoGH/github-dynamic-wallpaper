<template>
  <div class="content" :style="`background: ${backgroundColor};`">
    <svg
      class="svg-img"
      aria-hidden="true"
      viewBox="0 0 273 147"
      stroke-width="3"
      stroke-linecap="round"
      stroke-linejoin="round"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <g>
        <path
          :stroke="hillsColor"
          d="M162 140.5c14-29 51-29 65 5h44M175.5 118.001c-20-18-55-11-63.5 27.5H2"
        />
        <path
          :stroke="hillsColor"
          d="M132.001 124.5c-5.999 6-.999 10.999 4.999 4.999 5.999-6 1-10.999-4.999-4.999z"
        />
      </g>
      <g>
        <path
          :stroke="bushColor"
          d="M221 124.5c2.5-4.5 6-7 12-7M94.545 139.515c7.5-5.5 7-12.5 3-12.5-4.682 0-6.5 4.667-7 6 1.5-4.333 3.3-13.1-1.5-13.5-4.8-.4-5 7.167-4.5 11-.667-4.166-3.783-10.32-7.045-9.015-5 2 .046 8.515 2.546 11.515-1.501-.833-6.965-1.757-7.502 2-.5 3.5 3.334 4.5 5.002 4.5"
        />
        <circle :stroke="bushColor" cx="193.5" cy="15.5" r="1.5" />
      </g>
      <g>
        <path :stroke="buildingColor" d="M239.5 139.5v-74l32-27M270.5 139.5v-34h-10M270.5 96.5h-10" />
        <path :stroke="buildingColor" d="M271.5 27.5v60h-11M271.5 21.5v-3" />
      </g>
      <g>
        <path
          :stroke="treeColor"
          d="M48.5 131.5v8M22.5 122.5v17M34.5 103.5c0-7.732 6.268-14 14-14s14 6.268 14 14v14c0 7.732-6.268 14-14 14s-14-6.268-14-14v-14zM62.5 104.5h-13M62.5 113.5h-11"
        />
        <path
          :stroke="treeColor"
          d="M42.5 84.077v-5c0-3.035-.676-5.913-1.886-8.49 2.92-12.337-2.104-19.316-9.063-9.35a19.916 19.916 0 00-9.051-2.16c-3.257 0-6.333.779-9.05 2.16-6.96-9.966-11.985-2.987-9.064 9.351a19.923 19.923 0 00-1.886 8.49V102.5c0 11.046 8.954 20 20 20 2.09 0 4.106-.321 6-.916M20.5 76.5v2M33.5 76.5v2M19.5 93.5l-5 5M19.5 98.5l-5-5"
        />
      </g>
      <g>
        <path
          :stroke="cloudColor"
          d="M9.5 5.5a7 7 0 000 14H49a4 4 0 010 8h-5a7 7 0 100 14h39a7 7 0 100-14H66a4 4 0 010-8h.5a7 7 0 100-14h-57z"
        />
        <circle :stroke="cloudColor" cx="89" cy="12.5" r="7" />
      </g>
      <g>
        <path
          :fill="starColor"
          d="M17.89 34.27a1.745 1.745 0 00-3.361.01c-.267.966-.42 1.16-.492 1.232-.075.075-.278.23-1.256.5a1.745 1.745 0 00.01 3.367c.981.265 1.185.418 1.26.492.073.072.227.266.5 1.23a1.745 1.745 0 003.363-.012c.266-.966.419-1.16.49-1.232.075-.075.278-.23 1.258-.5a1.746 1.746 0 00-.011-3.368c-.982-.264-1.186-.418-1.262-.492-.072-.07-.226-.264-.498-1.227zM96.89 97.27a1.745 1.745 0 00-3.361.01c-.267.966-.42 1.16-.492 1.232-.075.075-.278.23-1.256.5a1.746 1.746 0 00.01 3.367c.981.265 1.185.418 1.26.492.073.072.227.266.5 1.23a1.745 1.745 0 003.363-.012c.266-.966.419-1.161.49-1.232.075-.075.278-.229 1.258-.5a1.746 1.746 0 00-.011-3.368c-.982-.264-1.186-.418-1.262-.492-.072-.07-.226-.263-.498-1.227zM120.891 23.27a1.745 1.745 0 00-3.362.01c-.267.966-.42 1.16-.492 1.232-.074.075-.278.23-1.256.5a1.746 1.746 0 00.01 3.367c.981.264 1.185.418 1.261.492.072.072.227.266.5 1.23a1.745 1.745 0 003.362-.012c.266-.966.419-1.16.491-1.232.074-.075.277-.23 1.257-.5a1.744 1.744 0 00-.011-3.368c-.982-.264-1.186-.418-1.262-.492-.072-.07-.226-.264-.498-1.227zM252.891 27.27a1.745 1.745 0 00-3.362.01c-.267.966-.42 1.16-.492 1.232-.074.075-.278.23-1.256.5a1.746 1.746 0 00.01 3.367c.981.265 1.185.418 1.261.492.072.072.227.266.5 1.23a1.745 1.745 0 003.362-.012c.266-.966.419-1.16.491-1.232.074-.075.277-.23 1.257-.5a1.744 1.744 0 00-.011-3.368c-.982-.264-1.186-.418-1.262-.492-.072-.07-.226-.264-.498-1.227z"
        />
      </g>
      <g>
        <circle :stroke="gitColor" cx="187.5" cy="75.5" r="4" transform="rotate(180 187.5 75.5)" />
        <circle :stroke="gitColor" cx="203.5" cy="98.5" r="6" transform="rotate(180 203.5 98.5)" />
        <circle :stroke="gitColor" cx="219.5" cy="84.5" r="4" transform="rotate(180 219.5 84.5)" />
        <path
          :stroke="gitColor"
          d="M203.5 92V49M203.5 51.5c0 11.202-16 5.894-16 20M203.5 60.5c0 11.202 16 5.894 16 20M231.5 29.562c-4.41 11.148-15.284 19.033-28 19.033s-23.59-7.885-28-19.033M179.5 25.5h48M175.5 21.032a30.077 30.077 0 014.824-8.14c-2.658-9.41.25-13.137 7.829-6.69A29.959 29.959 0 01203.5 2a29.96 29.96 0 0115.347 4.2c7.579-6.445 10.487-2.717 7.829 6.693a30.079 30.079 0 014.824 8.14"
        />
      </g>
    </svg>
  </div>
  <div class="time-layer">
    <div class="time-container" :style="`color: ${fontColor};`">{{ hour }}:{{ minute }}:{{ second }}</div>
  </div>
  <div class="date-layer">
    <div class="date-container" :style="`color: ${fontColor};`">{{ year }}年{{ month }}月{{ day }}日 星期{{ weekDay }}</div>
  </div>
</template>

<script setup lang="ts">
import { useIntervalFn } from '@vueuse/core';
import moment from 'moment'
import { computed, ref } from 'vue';

// 当数字小于 10 时添加前置 0
const addPrefix0 = (num: number) => {
  if (num < 10) {
    return "0" + num
  } else {
    return "" + num
  }
}
// 获取时间
const time = ref(moment())
const hour = computed(() => {
  return addPrefix0(time.value.hour())
})
const minute = computed(() => {
  return addPrefix0(time.value.minute())
})
const second = computed(() => {
  return addPrefix0(time.value.second())
})
// 获取日期
const day = computed(() => {
  return time.value.format('DD')
})
const month = computed(() => {
  return addPrefix0(time.value.month() + 1)
})
const year = computed(() => {
  return addPrefix0(time.value.year())
})
const weekDay = computed(() => {
  switch (time.value.weekday()) {
    case 0: return '日'
    case 1: return '一'
    case 2: return '二'
    case 3: return '三'
    case 4: return '四'
    case 5: return '五'
    case 6: return '六'
    default: return '柠'
  }
})
// 是否是白天
const isDayTime = computed(() => {
  return parseInt(hour.value) >= 6 && parseInt(hour.value) < 18
})
// 背景颜色
const backgroundColor = computed(() => {
  return isDayTime.value ? 'white' : 'rgb(13, 17, 23)'
})
// 山的颜色
const hillsColor = computed(() => {
  return isDayTime.value ? '#d1d5da' : '#da3633'
})
// 杂物的颜色
const bushColor = computed(() => {
  return isDayTime.value ? '#d1d5da' : '#f08831'
})
// 云的颜色
const cloudColor = computed(() => {
  return isDayTime.value ? '#d1d5da' : '#388bfd'
})
// 星星的颜色
const starColor = computed(() => {
  return isDayTime.value ? '#d1d5da' : '#e3b341'
})
// 树的颜色
const treeColor = computed(() => {
  return isDayTime.value ? '#d1d5da' : '#3fb950'
})
// 建筑的颜色
const buildingColor = computed(() => {
  return isDayTime.value ? '#d1d5da' : '#db61a2'
})
// 空中git的颜色
const gitColor = computed(() => {
  return isDayTime.value ? '#d1d5da' : '#6e40c9'
})
// 时间与日期颜色
const fontColor = computed(() => {
  return isDayTime.value ? '#d1d5da' : 'rgb(248, 213, 132)'
})

// 每秒自动更新时间
useIntervalFn(() => {
  time.value = moment()
}, 1000)
</script>

<style>
/* 定义字体 */
@font-face {
  font-family: "JetBrains Mono";
  src: url("assets/JetBrainsMono-Regular.woff2");
}
@font-face {
  font-family: "Alibaba Puhui";
  src: url("assets/Alibaba-PuHuiTi-Medium.woff");
}

body {
  margin: 0;
}
html,
body,
#app {
  height: 100%;
  overflow: hidden;
}
.content {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.svg-img {
  width: 80vw;
}
.time-layer {
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
.time-container {
  position: relative;
  top: 14vw;
  left: 15vw;
  font-size: 7vw;
  width: 80vw;
  height: calc(80vw / 273 * 147);
  font-family: "JetBrains Mono";
  user-select: none;
}
.date-layer {
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
.date-container {
  position: relative;
  top: 22vw;
  left: 20vw;
  font-size: 2.5vw;
  width: 80vw;
  height: calc(80vw / 273 * 147);
  font-family: "JetBrains Mono", "Alibaba Puhui";
  user-select: none;
}
</style>
