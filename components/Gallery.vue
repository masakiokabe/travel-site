<template>
    <div class="gallery">
        <div class="title-text">
            <h1>Travelling Gallery</h1>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <div class="gallery-box">
                        <img src="../assets/img/travel-1.jpg"/>
                        <h4>Los Angels</h4>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="gallery-box">
                        <img src="../assets/img/travel-2.jpg"/>
                        <h4>Paris</h4>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="gallery-box">
                        <img src="../assets/img/travel-3.jpg"/>
                        <h4>Australia</h4>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="gallery-box">
                        <img src="../assets/img/travel-4.jpg"/>
                        <h4>Spain</h4>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.gallery{
    padding: 50px 0 150px 0;
    background: #efefef;
}

.title-text{
    margin-bottom: 50px;
}

.gallery-box{
    position: relative;
    width: 100%;
    border-radius: 10px;
    cursor: pointer;
    transition: 1s;
    &:hover{
        transform: scale(1.1);
        z-index: 2;
    }
    img{
        width: 100%;
        border-radius: 10px;
    }
    h4{
        position: absolute;
        width: 200px;
        text-align: center;
        font-weight: 600;
        font-size: 20px;
        top: 50%;
        left: 50%;
        color: #fff;
        text-shadow: -2px 2px 2px #000;
        transform: translate(-50%, -50%);

    }

}

</style>