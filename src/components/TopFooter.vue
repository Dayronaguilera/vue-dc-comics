<template> 
    <div class="bg-top-footer">
        <div class="container">
            <div>
                <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                <span>DIGITAL COMICS</span>
            </div>
            <div>
                <img src="../assets/buy-comics-merchandise.png" alt="merchandise">
                <span>DC MERCHANDISE</span>
            </div>
            <div>
                <img src="../assets/buy-comics-subscriptions.png" alt="subscriptions">
                <span>SUBSCRIPTION</span>
            </div>
            <div>
                <img src="../assets/buy-comics-shop-locator.png" alt="shop-locator">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div>
                 <img src="../assets/buy-comics-subscriptions.png" alt="subscriptions">
                 <span>DC POWER VISA</span>
                <!-- <img src="../assets/buy-dc-power-visa-svg" alt="power-visa"> -->
            </div>
        </div> 
    </div>
</template>

<script>
export default {
    name: "TopFooter"
}
</script>

<style lang="scss" scoped>
.bg-top-footer{
    background-color: rgb(12, 99, 199);
    .container{
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        padding: 35px;
        div{
            display: flex;
            align-items: center;
            color: white;
            img{
                width: 40px;
                margin-right: 15px; 
            }
            span{
                font-size: 15px;
            }
        } 
    }
}
</style>