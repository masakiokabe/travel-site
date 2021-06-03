<template>
<div class="footer">
    <div class="container">
        <div class="row">
            <div class="col-md-3">
                <img src="../assets/img/triptok.png" class="footer-logo">
                <P>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. 
                   Aenean commodo ligula eget dolor. Aenean massa. 
                   Cum sociis natoque penatibus et magnis dis parturient montes,
                   nascetur ridiculus mus.</P>
            </div>
            <div class="col-md-3">
                <h4>Features</h4>
                <p>Deals & Offers</p>
                <p>Customer Reviews</p>
                <p>Cancelation Policies</p>
            </div>
            <div class="col-md-3 contact">
                <h4>Quick Contact</h4>
                <p><i><font-awesome-icon :icon="['fas', 'phone-square']"/></i> +1 0123456789</p>
                <p><i><font-awesome-icon :icon="['fas', 'envelope']"/></i> hello@example.com</p>
                <p><i><font-awesome-icon :icon="['fas', 'home']"/></i> xyz Road, ABC City</p>
            </div>
            <div class="col-md-3">
                <h4>Follow Us on</h4>
                <p><i><font-awesome-icon :icon="['fab', 'facebook']"/></i> Facebook</p>
                <p><i><font-awesome-icon :icon="['fab', 'youtube']"/></i> Youtube</p>
                <p><i><font-awesome-icon :icon="['fab', 'twitter']"/></i> Twitter</p>
            </div>
        </div>
        <hr>
        <p class="copyright">Made with <font-awesome-icon :icon="['fas', 'heart']"/> by me</p>
    </div>
</div>
    
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.footer{
    padding: 100px 20px;
    background-image: linear-gradient(#2d557d, #9610fb);
    color: #fff;
    h4{
        text-align: left;
        margin-top: 15px;
        margin-bottom: 25px;
    }
    p{
        font-size: 12px;
        text-align: justify;
        padding-right: 35px;
        cursor: pointer;
    }
    i{
        padding-right: 20px;
        font-size: 15px;
    }
}

.footer-logo{
    width: 150px;
    margin-top: 15px;
    margin-bottom: 15px;
}

hr{
    margin-top: 10px;
    background: #efefef;
    color: #efefef;

}

.footer{
    text-align: center;
}

.copyright{
    text-align: center;
}

@media screen and (min-width: 767px) and (max-width: 991px){
  .contact{
      i{
          pddding-right: 0;
      }
      p{
          padding-right: 0;
          font-size: 11px;
      }

  }
}

</style> 