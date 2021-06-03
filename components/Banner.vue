<template>
    <div class="banner">
        <div class="banner-highlights">
            <div class="container">
                <div class="row">
                    <div class="col-md-8">
                        <h2>Get 30% on top Destination</h2>
                        <p>Book your tickets before 31st march and avail 30% flat discount</p>
                    </div>
                    <div class="col-md-4">
                        <button type="button" class="booking-btn">Book Now</button>
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
.banner{
    height: 80vh;
    background-image:url("../assets/img/banner2.jpg");
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    padding-top: 14%;
}

.banner-highlights{
    padding: 70px 0;
    background: rgba(0,0,0,0.7);
    text-align: center;
    color: #fff;
}

.booking-btn{
    width: 120px;
    padding: 8px 0;
    outline: none;
    border: 2px solid #fff;
    border-radius: 50px;
    background: transparent;
    color: #fff;
    margin-top: 20px;

}
</style>