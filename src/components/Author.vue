<style lang="stylus" scoped>
.avatar
    width 10%
    border-radius 50%
.info
    display flex
    flex-direction column
    justify-content center
    align-items center
    padding 50px 0px
h3
    margin-block-start 1px
h2
    margin-block-end 1px
.social
    display flex
    flex-direction row
    justify-content space-around
    align-items center
    padding 50px 0
</style>

<template>
    <div class="author">
        <div class="info">
            <!--<img class="avatar" src="../assets/chariesgavin.jpg" alt="chariesgavin">-->
            <h2> Charies Gavin</h2>
            <h4>Stay Hungry, Stay Foolish.</h4>
        </div>
        <div class="social">
            <a class="github" href="https://github.com/guobinhit"><i class="iconfont icon-github"></i> GitHub</a>
            <a class="csdn" href="https://guobinhit.blog.csdn.net/"><i class="iconfont icon-csdn"></i> CSDN</a>
            <a class="twitter" href="https://twitter.com/guobinhit"><i class="iconfont icon-twitter"></i> Twitter</a>
            <a class="gmail" href="mailto:guobinhit@qq.com"><i class="iconfont icon-gmail"></i> Email</a>
        </div>
    </div>
</template>
