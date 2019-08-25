<template>
  <div class="header">
    <div class="header-left">
        <span class="iconfont">&#xe696;</span>
    </div>
    <div class="header-input">
        <span class="iconfont">&#xe62b;</span>
        请输入...</div>
    <div class="header-right">
        城市<span class="iconfont">&#xe62e;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss" scoped>
@import '../../../assets/varible.scss';
    .header{
        height:.86rem;
        line-height: .86rem;
        display: flex;
        color:#fff;
        background-color:$bgColor;
        .header-left{
            width:.64rem;
            margin:0 .2rem;
            text-align: center;
        }
        .header-input{
            flex:1;
            line-height:.6rem;
            background: #fff;
            border-radius: .1rem;
            height:.6rem;
            margin-top:.12rem;
            color:#ccc;
            margin-right:.2rem;
            padding-left:.1rem;
        }
        .header-right{
            width:1.24rem;

            text-align: center;
            .iconfont{
                font-size: .2rem;
                margin-left: .06rem;
            }
        }
    }
</style>
