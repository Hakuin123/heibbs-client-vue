<template>
  <div class="index">
    <br>
    <br>
    <h1 class="text" style="
     text-align: center;
     font-size: 1000%;">
      404
    </h1>

    <br>
    <br>
    <br>

    <p class="text" style="
     text-align: center;
     font-weight: bold;
     font-size: 200%;">
      啥 都 木 有 _(:з」∠)_
    </p>

    <br>
    <br>

    <div style="
      width: 300px;
      height: 300px;
      display: block;
      margin: auto
    ">
      <img src="https://static.hk256.top/s/6990635f400d484c.jpg" title="小黑表示不知道你在找啥" style="
       border-radius: 20px;
       width: 80%" />
    </div>

    您可以尝试：<br />
    • 检查来源网址是否有误<br />
    • 通过顶部搜索功能检索信息<br />
    • <a href="https://2048lxh.hk256.top" style="text-decoration: underline;">玩玩罗小黑版2048</a>


    <div class="GoBackHome" @click="$router.push('/index')">
      返回首页
    </div>

  </div>

  <img src="https://static.hk256.top/IYDUEYCRTB.png" style="display: block; margin: auto">

  <br>

  <div style="
    border: none;
    background: rgb(254, 180, 69);
    border-radius: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
  ">

    <p style="margin: 10px;">
      广告位招租 电话：+11 4514-1919810
    </p>
  </div>

</template>

<script>
export default {
  name: "App",
  mounted() {
    this.consoleEgg();
  },
  
  methods: {
    consoleEgg() {
      console.clear();
      console.log("%cฅ՞•ﻌ•՞ฅ这里是白熊！静静地呆在这里维护论坛服务器", "padding:30px; background: linear-gradient(to right, white, orange)");
      console.log("%c", "padding:50px; background-image: url(https://static.hk256.top/avatar.jpg);");
      console.warn("白熊要吃光你的内存啦！");
      console.log("好啦好啦，咱是开玩笑的嘛xwx");
      console.info("记得来找我玩呀~")

    },
  },
}
</script>

<style lang="scss" scoped>
.index {
  background: rgba(255, 255, 255, 0.9);
  margin-top: 90px;
  margin-bottom: 70px;
  padding: 20px 10px;
  border-radius: 10px;
  line-height: 1.5em;

  .GoBackHome {
    width: 100px;
    margin: auto;
    color: rgb(255, 248, 226);
    background: rgb(254, 180, 69);
    border-radius: 10px;
    padding: 10px 5px;
    font-weight: 550;
    text-align: center;
  }
}
</style>