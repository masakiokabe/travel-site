<template>
    <div class="users-feedback">
        <div class="title-text">
            <h1>Users Review</h1>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <div class="user-review">
                        <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
                           Aenean commodo ligula eget dolor. Aenean massa.
                        </p>
                        <h5>Pravel Sharma</h5>
                        <small>Los Angels</small>
                    </div>
                    <img src="../assets/img/user1.jpg"/>
                </div>
                <div class="col-md-4">
                    <div class="user-review">
                        <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
                           Aenean commodo ligula eget dolor. Aenean massa.
                        </p>
                        <h5>Mike Rison</h5>
                        <small>Los Angels</small>
                    </div>
                    <img src="../assets/img/user2.jpg"/>
                </div>
                <div class="col-md-4">

                    <div class="user-review">
                        <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
                           Aenean commodo ligula eget dolor. Aenean massa.
                        </p>
                        <h5>Shelly Rockwell</h5>
                        <small>Los Angels</small>
                    </div>
                    <img src="../assets/img/user3.jpg"/>
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

    .users-feedback{
        padding: 100px 0;
        img{
            width: 60px;
            height: 60px;
            border-radius: 50%;
            position: relative;
            margin: -30px 0 20px 40%;
        }
    }

    .user-review{
        text-align: center;
        box-shadow: 0 0 10px 0 rgba(0,0,100,0.2);
        padding-bottom: 50px;
        p{
            padding:50px 10px 10px 10px;
        }
        p::before{
            content: '\201d';
            display: block;    
            position: absolute;
            font-size: 100px;
            color: #6495ed;
            font-family: sans-serif;
            left: 44%;
            top: -7%;
        }
    }

    .col-md-4{
        transition: 0.6s;
        cursor: pointer;
    }

    .col-md-4:hover{
        transform: translateY(-10px);
    }

</style>