<template>
<div class="body">
    <div class="wrap">
        <div class="box"><h3>登录</h3></div>
      <div class="box"><input type="text" placeholder="请输入用户名"></div>
      <div class="box"><input type="text" placeholder="请输入密码"></div>
      <div class="box"><button>登录</button></div>
    </div>
</div>
</template>
<script>
export default {
components:{
 },
data () {
 return {
 }
},
methods:{
},
mounted(){
}
}
</script>
<style scoped>
.body{
    width: 100vw;
    height: 100vh;
    background:linear-gradient(to right,#543545,#313c5e);
}
.wrap{
    width: 400px;
    height: 280px;
    background: #fff;
    position: absolute;
    top: 150px;
    left: 38%;
    border-radius: 10px;
}
.box{
    width: 300px;
    height: 30px;
    margin: 0 auto;
    margin-top: 30px;
    text-align: center;
}
.box>input{
    width: 300px;
    height: 30px;
    border-radius: 4px;
    border: 2px solid #ccc;
}
.box>button{
    border: none;
    outline: none;
    width: 300px;
    height: 30px;
    background: #409eff ;
    color:#fff;
    cursor: pointer;
    border-radius: 4px;
}
</style>