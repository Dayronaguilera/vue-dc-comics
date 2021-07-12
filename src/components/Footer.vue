<template> 
    <div class="bg-footer">
        <div class="container">
            <div class="menu-container">
                <ul>
                    <li>DC COMICS</li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <ul>
                    <li>DC SHOP</li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
            <div class="menu-container">
                <ul>
                    <li>DC</li>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy Policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li> 
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div class="menu-container">
                <ul>
                    <li>SITES</li>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">DC UNIVERSE INFINITE</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Shop</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                </ul>
            </div>
            <div class="bottom-footer">

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss" scoped>
    .bg-footer{
        background: url(../assets/footer-bg.jpg);
        .container{
            display: flex;
            padding: 50px;
            .menu-container{
                margin-right: 50px;
                ul{
                    list-style: none;
                    li{
                        padding: 3px 0px;
                        &:first-child{
                            color: white;
                            font-size: 20px;
                            font-weight: bold;
                            margin: 15px 0px;
                        }
                        a {
                            color: rgb(156, 156, 156);
                            text-decoration: none;

                            &:hover {
                                text-decoration: underline;
                                color: blue;
                            } 
                        }
                    }
                }
            }

        }
    }

</style>