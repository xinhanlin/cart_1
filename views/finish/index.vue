<template>
  <Header></Header>
  <div class="cart-wrapper-contain">
    <div class="cartwrapper">
      <div class="innerwrapper">
        <div class="middle">
          <div class="finish">訂單已完成,即刻為您製作</div>
          <br />
          <h2>
            有<span style="color: red">{{ $store.state.nopay.length }}</span
            >項商品為您保存至清單中
          </h2>
          <router-link
            to="/pay"
            style="display: block; margin: 20px 0px 20px 0px"
          >
            <span style="color: red; font-size: 20px"
              >返回訂購單</span
            ></router-link
          >
          <router-link to="/" style="display: block; margin: 20px 0px 20px 0px">
            <span style="color: red; font-size: 20px"
              >返回首頁</span
            ></router-link
          >
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  setup() {},
};
</script>

<style scoped>
.cart-wrapper-contain {
  height: 70vw;
}
.cartwrapper {
  width: 90%;

  border: 2px solid black;
  margin: 50px auto;
  background-color: aliceblue;
  border-radius: 5px;
}
.innerwrapper {
  margin: 100px auto;
  text-align: center;
}
.middle {
  margin: auto;
}
.finish {
  margin-top: 30px;
}
h2 {
  margin-bottom: 20px;
}
</style>
