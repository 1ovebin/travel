<template>
  <div class="detail-baseinfo">
    <div class="flex-card">
      <div class="flex-item flexlink-con">
        <a class="card-link" href="javascript:void(0)"></a>
        <div>
          <span class="commentcard-score">4.9</span>
          <span class="commentcard-text">分</span>
          <span class="commentcard-desc">很棒</span>
        </div>
        <div>
          <span class="totalcommentnum">7879条评论</span>
          <span class="totalcommentnum">11条攻略</span>
          <span class="iconfont rightarrow">&#xe624;</span>
        </div>
      </div>
      <div class="flex-item border-left flexlink-con">
        <a href="javascript:void(0)" class="card-link">
          <div>
            <span class="sightcard-title">景点简介</span>
          </div>
          <div>
            <span class="sightcard-text">开放时间、贴士</span>
            <span class="iconfont rightarrow" style="right: 0;">&#xe624;</span>
          </div>
        </a>
      </div>
    </div>
    <!--  -->
    <div class="baseinfo-address border-top">
      <p class="baseinfo-address-txt">
        <span class="iconfont baseinfo-address-icon">&#xe62f;</span>
        山东省济南市历下区经十一路18号
        <span class="iconfont baseinfo-address-arrow">&#xe624;</span>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'DetailBaseinfo'
}
</script>

<style scoped>
  .detail-baseinfo{position: relative;top: -.1rem;padding: .1rem .2rem 0 .2rem;margin-bottom: .1rem;background: #fff;-webkit-border-radius: .1rem .1rem 0 0;-moz-border-radius: .1rem .1rem 0 0;border-radius: .1rem .1rem 0 0;}
  .flex-card{display: -webkit-box;display: -moz-box;display: -webkit-flex;display: -moz-flex;display: -ms-flexbox;display: flex;width: 100%;padding-top: .1rem;padding-bottom: .2rem;}
  .flex-item{-webkit-box-flex: 1;-moz-box-flex: 1;-webkit-flex: 1;-moz-flex: 1;-ms-flex: 1;flex: 1;}
  .flexlink-con{position: relative;}
  .card-link{position: absolute;left: 0;top: 0;width: 100%;height: 100%;}
  .commentcard-score{font-size: .44rem;color: #ff8300;line-height: .44rem;}
  .commentcard-text{font-size: .28rem;color: #ff8300;line-height: .48rem;}
  .commentcard-desc{font-size: .28rem;color: #ff8300;line-height: .48rem;margin-left: .2rem;}
  .totalcommentnum{font-size: .24rem;color: #9e9e9e;line-height: .32rem;margin-right: .2rem;}
  .rightarrow{position: absolute;top: .3rem;right: .2rem;color: #9e9e9e;font-size: .24rem;transform: rotate(180deg);font-weight: bold;}
  .border-left{border-left: 1px solid #e0e0e0;}
  .sightcard-title{font-size: .28rem;color: #212121;line-height: .48rem;padding-left: .3rem;}
  .sightcard-text{color: #9e9e9e;font-size: .24rem;padding-left: .3rem;}
  .baseinfo-address{display: block;position: relative;padding: .2rem 0;line-height: .36rem;color: #212121;}
  .border-top{border-top: 1px solid #f0f0ef;}
  .baseinfo-address-txt{padding-right: .56rem;position: relative;padding-left: .56rem;}
  .baseinfo-address-icon{display: block;height: 100%;line-height: 100%;position: absolute;left: 0;top: .16rem;margin-top: -.16rem;margin-right: .2rem;color: #9e9e9e;font-size: .36rem;}
  .baseinfo-address-arrow{position: absolute;right: 0;top: 50%;margin-top: -.14rem;color: #9e9e9e;font-size: .24rem;font-weight: bold;transform: rotate(180deg);}
</style>
