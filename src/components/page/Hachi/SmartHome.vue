<template>
  <div id="hc-SmartHome">
    <div class="designImg">
      <div class="hachi_home_01">
         <div class="hachi_home home_01_01">
             <div class="hachi_slogan1">哈奇智慧家庭解决方案</div>
              <div class="hachi_slogan2">聚焦智慧创新，为你带来安全、舒适、便捷和艺术的高品质居家生活体验</div>
        </div>
      </div>
    </div>
    <div class="designImg">
      <div class="hachi_home_02">
         <div class="hachi_home home_02_01">
             <div class="hachi_slogan3">4种控制方式 任意选择</div>
              <div class="hachi_slogan4">满足不同场景和不同人群的需求</div>
        </div>
      </div>
    </div>
    <div class="typical_config">
        典型配置方案
    </div>
    <div class="designImg border_2px">
      <div class="hachi_home home_03">
      </div>
    </div>
    <div class="designImg border_2px">
      <div class="hachi_home home_04">
      </div>
    </div>
        <div class="designImg border_2px">
      <div class="hachi_home home_05">
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'SmartHome'
}
</script>


<style lang="scss" scoped>

.designImg {
    text-align: center;
    width: 100%;
    img {
        display: block;  
        margin: 0 auto;

    }
}

    .hachi_home_01 {
        background-image:url('./../../../assets/images/hachi/home/div_01_01.jpg'); 
        background-repeat: repeat-y;
        background-size: 100% 100%;
        height: 900px;
        position: relative;
        overflow: hidden;
        width: 100%;
    }

    .home_01_01 {
        min-width: 1280px;
        max-width: 2580px;
        height: 900px;
        background-image: url("./../../../assets/images/hachi/home/div_01.jpg");
    }

     .hachi_slogan1 {
        width: 100%;
        text-align: center;
        color: white;
        font-size: 32pt;
        font-weight:lighter;
        margin-top: 182px;
    }

    .hachi_slogan2 {
        width: 100%;
        text-align: center;
        color: white;
        font-size: 18pt;
        font-weight: lighter;
        margin-top: 10px;

    }

    .hachi_slogan3 {
        width: 100%;
        text-align: center;
        font-size: 34pt;
        font-weight:lighter;
        margin-top: 180px;
    }

    .hachi_slogan4 {
        width: 100%;
        text-align: center;
        font-size: 18pt;
        font-weight: lighter;
        margin-top: 10px;

    }

    .hachi_home_02 {
        background-image:url('./../../../assets/images/hachi/home/div_02_01.jpg'); 
        background-repeat: repeat-y;
        background-size: 100% 100%;
        height: 770px;
        position: relative;
        overflow: hidden;
    }

    .home_02_01 {
        min-width: 1280px;
        max-width: 1280px;
        height: 770px;
        background-image: url("./../../../assets/images/hachi/home/div_02.jpg");
    }

    .typical_config{
        height: 222px;
        line-height: 222px;
        text-align: center;
        font-size: 32pt;
    }

    .hachi_home {
        background-size: cover;
        display: block;
        position: relative;
        overflow: hidden;
        margin: 0 auto;
        background-repeat: no-repeat;
        background-position: center center;
    }

    .home_03 {
        max-width: 1440px;
        height: 888px;
        background-image: url("./../../../assets/images/hachi/home/div_03.jpg");
    }

    .home_04 {
        max-width: 1440px;
        height: 1205px;
        background-image: url("./../../../assets/images/hachi/home/div_04.jpg");
    }

    .home_04 {
        max-width: 1440px;
        height: 1035px;
        background-image: url("./../../../assets/images/hachi/home/div_05.jpg");
    }

    .border_2px {
        border-top: 2px solid #e6e7e8;
    }

</style>
