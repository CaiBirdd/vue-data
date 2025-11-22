<script setup>

</script>

<template>
  <div class="container">
    <div class="card">
      <div class="card-header">
        <div class="decorative-line"></div>
        <h2 class="title">Do you face any of these struggles before or<br>during your meetings?</h2>
        <div class="decorative-line"></div>
      </div>
      <div class="card-content">
        <div class="content-item">
          <div class="dot"></div>
          <p>Not sure what to focus on before the meeting</p>
        </div>
        <div class="content-item">
          <div class="dot"></div>
          <p>Wasting time on unimportant details</p>
        </div>
        <div class="content-item">
          <div class="dot"></div>
          <p>Unsure how to respond to tough questions</p>
        </div>
        <div class="content-item">
          <div class="dot"></div>
          <p>Forgetting key details from past meetings</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: 1440px;
  flex-shrink: 0;
  background-color: #ffff;
  margin-bottom: 49.5px;

  .card {
    width: 1240px;
    height: 431.5px;
    border: 2px solid rgba(0, 0, 0, 0.08);
    border-radius: 34px;
    margin: 50px 100px;
    background: rgba(255, 255, 255, 0.80);
    box-shadow: 2px 3px 4px rgba(0, 0, 0, 0.15);

    .card-header {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 45px;
      margin-top: 65.67px;

      .decorative-line {
        width: 57.005px;
        height: 3px;
        background: #B4EA7E;
      }

      .title {

        width: 866px;
        height: 108px;
        color: #000;
        font-size: 36px;
        line-height: 1.5;
        font-family: Martel;
        font-weight: 700;
        text-align: center;
        letter-spacing: 1.6px;
      }
    }
  }

  .card-content {
    display: grid;
    grid-template-columns: 1fr 1fr; //此时容器宽度被均分为两列，每列宽度为容器宽度的50% 。
    column-gap: 80px;
    row-gap: 44px;
    max-width: 1024px; //不设置最大宽度会把car左右铺满 调不了margin
    margin: 47px auto  80.5px auto;

    .content-item {
      display: flex;
      align-items: flex-start;
      gap: 9px;

      .dot {
        width: 12px;
        height: 12px;
        border-radius: 50%;
        background-color: #B4EA7E;
        margin-top: 8px;
      }
      p {
        color: #000;
        font-size: 21px;
        font-weight: 300;
        line-height: 1.5;
        font-family: Martel;
      }
    }
  }
}
</style>
