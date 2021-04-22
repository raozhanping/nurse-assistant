<template>
  <view class="home">
    <view class="home__timer">
      <view class="home__timer__num">12 : 34</view>
      <view class="home__timer__subtitle">创建记录</view>
      <view class="home__timer__arrow">
        <AtIcon value='chevron-right' size='24' color='#fff'></AtIcon>
      </view>
    </view>
    <AtButton>记录</AtButton>
  </view>
</template>

<script>
import {AtButton} from 'taro-ui-vue3'

export default {
  name: 'Index',
  components: {
    AtButton
  }
}
</script>

<style>
.home {
  --timer-bg: #070417;
  --default-color: #fff;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 15px;
}
.home__timer {
  padding: 22px 26px;
  border-radius: 12px;
  background-color: var(--timer-bg);
}
.home__timer__num {
  font-size: 32px;
  color: var(--default-color);
}
</style>
