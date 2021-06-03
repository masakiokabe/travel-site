<template>
    <div class="features">
        <h1>Featured Destinations</h1>
        <div >
            <dov class="row">
                <div class="col-md-4">
                    <div class="feature-box">
                        <div class="feature-img">
                            <img src="../assets/img/1.jpg"/>
                            <div class="price">
                                <p>78$</p>
                            </div>
                            <div class="rating">
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star-half']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star-o']"/></i>
                            </div>
                        </div>
                        <div class="feature-details">
                            <h4>Los Angels</h4>
                            <p>
                                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. 
                                Aenean commodo ligula eget dolor. Aenean massa. Cum sociis 
                                natoque penatibus et magnis dis parturient montes, nascetur 
                                ridiculus mus. Donec quam felis,
                            </p>
                            <span><i><font-awesome-icon :icon="['fas', 'map-marker']"/></i>Los Angeles</span>
                            <span><i><font-awesome-icon :icon="['fas', 'sun']"/></i>4 Days</span>
                            <span><i><font-awesome-icon :icon="['fas', 'moon']"/></i>3 Nights</span>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-box">
                        <div class="feature-img">
                            <img src="../assets/img/2.jpg"/>
                            <div class="price">
                                <p>88$</p>
                            </div>
                            <div class="rating">
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star-half']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star-o']"/></i>
                            </div>
                        </div>
                        <div class="feature-details">
                            <h4>Miami</h4>
                            <p>
                                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. 
                                Aenean commodo ligula eget dolor. Aenean massa. Cum sociis 
                                natoque penatibus et magnis dis parturient montes, nascetur 
                                ridiculus mus. Donec quam felis,
                            </p>
                            <span><i><font-awesome-icon :icon="['fas', 'map-marker']"/></i>Miami</span>
                            <span><i><font-awesome-icon :icon="['fas', 'sun']"/></i>3 Days</span>
                            <span><i><font-awesome-icon :icon="['fas', 'moon']"/></i>2 Nights</span>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-box">
                        <div class="feature-img">
                            <img src="../assets/img/3.jpg"/>
                            <div class="price">
                                <p>99$</p>
                            </div>
                            <div class="rating">
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star-half']"/></i>
                                <i><font-awesome-icon :icon="['fas', 'star-o']"/></i>
                            </div>
                        </div>
                        <div class="feature-details">
                            <h4>New York</h4>
                            <p>
                                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis 
                                natoque penatibus et magnis dis parturient montes, nascetur 
                                ridiculus mus. Donec quam felis,
                            </p>
                            <span><i><font-awesome-icon :icon="['fas', 'map-marker']"/></i>New York</span>
                            <span><i><font-awesome-icon :icon="['fas', 'sun']"/></i>4 Days</span>
                            <span><i><font-awesome-icon :icon="['fas', 'moon']"/></i>3 Nights</span>
                        </div>
                    </div>
                </div>
            </dov>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.features{
    padding: 50px 0 100px 0;
    h1{
        text-align: center;
        padding-bottom: 30px;
    }
}

.feature-img{
    position: relative;
    img{
        width: 100%;
    }
}

.price{
    width: 50px;
    height: 50px;
    background: #ff5722;
    color: #fff;
    font-weight: 600;
    border-radius: 50%;
    padding: 10px;
    box-shadow: 0 0 10px 1px rgba(37, 73, 214, 0.18);
    position: absolute;
    left: 20px;
    bottom: 10px;   
}

.rating{
    padding: 3px;
    float: right;
    background: #fff;
    bottom: -1px;
    right: 0px;
    position: absolute;
}

i{
    font-size: 15px;
    color: #ff5722;
}

.feature-details{
    padding: 20px 10px;
    text-align: center;
    height: 100%;
    h4{
        font-weight: 600;
        margin-top: 20px;
    }
    i{
        margin-right: 5px;
    }
    
}

.feature-box{
    box-shadow: 0 0 10px 10px rgba(37,73,214,0.18);
    margin-bottom: 30px;
}

.col-md-4{
    transition: 0.6s;
    cursor: pointer;
}

.col-md-4:hover{
    transform: translateY(-10px);
}

@media screen and (min-width:701px) and (max-width: 1000px){
    .feature-details{
        span{
            display: block;
            text-align: left;
            line-height: 25px;
            padding-left: 10px;
        }
    }

}
</style>