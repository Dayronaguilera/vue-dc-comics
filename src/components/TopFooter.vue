<template> 
    <div class="bg-top-footer">
        <div class="container">
            <div>
                <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
            </div>
            <div>
                <img src="../assets/buy-comics-merchandise.png" alt="merchandise">
            </div>
            <div>
                <img src="../assets/buy-comics-subscriptions.png" alt="subscriptions">
            </div>
            <div>
                <img src="../assets/buy-comics-shop-locator.png" alt="shop-locator">
            </div>
            <div>
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
    .container{
        div{
            width: 70px;
            img{
                width: 100%;
            }
        }
    }
}
</style>