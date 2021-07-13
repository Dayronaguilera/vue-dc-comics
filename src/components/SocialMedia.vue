<template> 
    <section class="social-media">
        <div class="container">
            <div class="left-cont">
                <span>SIGN-UP NOW</span>
            </div>
            <div class="right-cont">
                <span>FOLLOW US</span>
                <img src="../assets/footer-facebook.png" alt="" />
                <img src="../assets/footer-twitter.png" alt="" />
                <img src="../assets/footer-youtube.png" alt="" />
                <img src="../assets/footer-pinterest.png" alt="" />
                <img src="../assets/footer-periscope.png" alt="" />
            </div>
        </div>
    </section>
</template>


<script>
export default {
    name: "SocialMedia"
}
</script>

<style lang="scss" scoped>
.social-media{
    background: rgb(46, 46, 46);
    color: white;
    .container{
        display: flex;
        justify-content: space-between;
        padding: 30px;
        .left-cont{
            border: 1px rgb(12, 99, 199) solid;
            padding: 15px 20PX;
            span{
                font-size: 20px;
                
            }
        }
        .right-cont{
            display: flex;
            align-items: center;
            span{
                font-size: 20px;
                margin-right: 20px;
                color: rgb(12, 99, 199);
            }
            img{
                padding: 10px;
            }
        }
    }
}
</style>