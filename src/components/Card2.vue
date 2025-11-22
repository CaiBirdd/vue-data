<script setup>
</script>
<template>
  <div class="container">
    <div class="container-outline">
      <div class="header">
        <div class="decorative-line"></div>
        <h2 class="title">Our product empowers you to:</h2>
        <div class="decorative-line"></div>
      </div>
      <div class="cards">
        <div class="card-item">
          <div class="image-wrapper">
            <img src="../assets/ImageWithFallback-1.png" alt="">
          </div>
          <p class="description">
            Generate personalized strategies based on participants, calendar events, and historical data, helping you
            <span class="highlight"> predict key concerns and prepare effectively.</span>
          </p>
        </div>

        <div class="card-item">
          <div class="image-wrapper">
            <img src="../assets/ImageWithFallback-2.png" alt="">
          </div>
          <p class="description">
            <span class="highlight"> Track participant profiles and in-meeting signals</span>
            like speaking ratio, emotions, hesitation, and pushback points.
          </p>
        </div>

        <div class="card-item">
          <div class="image-wrapper">
            <img src="../assets/ImageWithFallback-3.png" alt="">
          </div>
          <p class="description">
            Predict potential sharp questions and provide tailored response strategies to
            <span class="highlight">avoid being caught off guard.</span>
          </p>
        </div>

        <div class="card-item">
          <div class="image-wrapper">
            <img src="../assets/ImageWithFallback-4.png" alt="">
          </div>
          <p class="description">
            Get your speaking strategy ready in just 5 minutes before the meeting,
            <span class="highlight">saving you valuable time.</span>
          </p>
        </div>

        <div class="card-item">
          <div class="image-wrapper">
            <img src="../assets/ImageWithFallback-5.png" alt="">
          </div>
          <p class="description">
            Each meeting with the same participant improves your data, making
            <span class="highlight"> decisions more precise over time.</span>
          </p>
        </div>

        <div class="card-item">
          <div class="image-wrapper">
            <img src="../assets/ImageWithFallback-6.png" alt="">
          </div>
          <p class="description">
            Get a detailed post-meeting summary stored in your database,
            <span class="highlight">building a memory of past meetings.</span>
          </p>
        </div>
      </div>
    </div>
  </div>

</template>
<style lang="scss" scoped>
.container {
  width: 1440px;
  background-color: #ffff;
  margin: 0 auto;

  .container-outline {
    margin: 0 auto;
    width: 1240px;
    height: 1265px;
    border: 2px solid rgba(0, 0, 0, 0.08);
    border-radius: 40px;
    background: rgba(255, 255, 255, 0.30);
    box-shadow: 0 8px 20px 0 rgba(0, 0, 0, 0.06);

    .header {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 40px;
      margin-top: 63px;

      .decorative-line {
        width: 79.004px;
        height: 3px;
        background: #B4EA7E;
      }

      .title {
        width: 730px;
        height: 66px;
        color: #000;
        font-size: 44px;
        line-height: 1.5;
        font-family: Martel;
        font-weight: 700;
        text-align: center;
        letter-spacing: 1.8px;
      }
    }

    .cards {
      display: grid;
      grid-template-columns: 1fr 1fr;
      margin: 50px auto;
      gap: 40px;
      max-width: 1136px;

      .card-item {
        display: flex;
        align-items: center;
        padding: 45px;
        gap: 30px;
        width: 547px;
        height: 300px;
        border: 1.5px solid #d4d4d4;
        border-radius: 36px;
        background-color: #fff;
        box-shadow: 3px 4px 4px 0 rgba(0, 0, 0, 0.25);

        .image-wrapper {
          width: 190px;
          height: 190px;
          border-radius: 20px;
          overflow: hidden;
        }

        img {
          width: 100%;
          height: 100%;
          object-fit: cover;
        }

        .description {
          width: 241px;
          color: #000;
          font-family: Martel;
          font-size: 18px;
          line-height: 1.5;
          font-weight: 300;

          .highlight {
            color: #6B9D4A;
            font-weight: 700;
          }
        }
      }
    }
  }
}
</style>