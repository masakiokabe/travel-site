<template>
    <div class="header">
        <div class="container">
            <img src="../assets/img/triptok.png"/>
            <button type="button" class="login-btn">Login</button>
        </div>
        <h1>Travel Across The Globe</h1>
        <p>Subscribe My Youtube Channel</p>
        <div class="input-group">
            <input type="text" class="form-control" placeholder="Search Country or City" />
            <div class="input-group-append">
                <button type="submit" class="input-group-text btn">Search</button>
            </div>
        </div>
    </div> 
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.header{
    height: 100vh;
    background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.6)), url("../assets/img/banner1.jpg");
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    padding-top: 20px;
    text-align: center;
    color: #fff;
    img{
        width: 170px;
        float: left;
        cursor: pointer;
        margin-top: 40px;
    }
    h1{
        padding-top: 200px;
        padding-bottom:0;
        font-size: 55px;
        margin-top: 80px;
    }
    p{
        margin: 18px 0;
    }
}

.login-btn{
    width: 100px;
    padding: 8px 0;
    outline: none;
    border: 2px solid #fff;
    border-radius: 50px;
    background: transparent;
    color: #fff;
    float: right;
    margin-top:40px;
}

.input-group{
    width: 90%;
    max-width: 500px;
    border-radius: 30px;
    background: #fff;
    margin: auto;
    padding: 2px;
}

.form-control{
    border: 0;
    border-radius: 30px 0 0 30px;
    margin: 2px;
    box-shadow: none;
}

.input-group-text{
    width: 100px;
    background-image: linear-gradient(#00ff7e, #1f3d90);
    border: 0;
    color: #fff;
    padding: 0 25px;
    border-radius: 30px;
    box-shadow: none;
}

@media screen and (max-width: 400px){
        h1{
            font-size: 35px;
        }
}
</style>