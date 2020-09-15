<template>
    <div>
        <mt-button plain id="back">
            <img src="../assets/images/back(b).png" alt="">
        </mt-button>
        <input type="text" placeholder="请输入商品名" class="search">
        <mt-button plain id="search">搜索</mt-button>
        <div class="main">
            <b>搜索发现</b>
            <mt-button slot="right" plain id="refresh">
                <span class="refresh">换一批</span>
                <img src="../assets/images/refresh.png" alt="">
            </mt-button>
            <p>
                <router-link to="/#" style="background-color:red;color:white">紫燕卤味</router-link>
                <router-link to="/#">烧烤</router-link>
                <router-link to="/#">炒饭</router-link>
                <router-link to="/#">水饺</router-link>
            </p>
             <p>
                <router-link to="/#">紫燕卤味</router-link>
                <router-link to="/#">烧烤</router-link>
                <router-link to="/#">炒饭</router-link>
                <router-link to="/#">水饺</router-link>
                <router-link to="/#">乡村基</router-link>
            </p>
        </div>
    </div>
</template>
<style scoped>
    .search{
    width: 190px;
    height: 25px;
    position: relative;
    left:10px;
    background-image: url(../assets/images/search.png);
    background-position-y: 2px;
    background-repeat:no-repeat;
    border: 2px solid #ef5f58;
    padding-left: 35px;
    border-radius: 10px;
    outline: none;
 }
 .mint-button--default.is-plain{
     border: 0;
 }
 #search{
     width: 55px;
     height: 30px;
     font-size: 14px;
     background-color: #ef5f58;
     position: relative;
     left: 20px;
     top: 2px;
     border-radius: 5px;
}
#back{
    position: relative;
    top: 10px;
}
.refresh{
     font-size: 12px;
     position: relative;
     top: -5px;
     left: -2px;
}
#refresh{
    float: right;
    height: 30px;
    line-height: 30px;
    text-align: center;
}
.main{
    margin-top: 15px;
}
.main b{
    font-size: 16px;
    margin-left: 15px;
}
.main p{
    width: 100%;
}
.main p a{
    display:inline-block;
    width: 55px;
    height: 20px;
    line-height: 20px;
    text-align: center;
    text-decoration: none;
    color: rgb(10, 10, 10);
    font-size: 12px;
    margin-left: 15px;
    border-radius: 5px;
    background-color: rgba(179, 179, 179, 0.418);
}
.mint-button::after{
    background-color: #d8d8d8;
}
</style>