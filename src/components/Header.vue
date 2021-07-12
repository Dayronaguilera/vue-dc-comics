<template> 
    <nav class="bg-nav ">
        <div class="container-nav container">
            <div class="img-container">
                <img src="../assets/dc-logo.png" alt="dc-logo">         
            </div>
            <div class="container-menu">
                <ul>
                    <li>CHARACTERS</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </div>  
        </div> 
    </nav>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style lang="scss" scoped>
   .bg-nav{
       
       .container-nav{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px;
            .img-container{
                width: 70px;
                img{
                    width: 100%;
                }
            }
            .container-menu{
                ul{
                    list-style: none;
                    display: flex;
                    li{
                        padding:0px 15px;
                        font-size: 13px;
                        font-weight: bold;
                         cursor: pointer;
                        &:hover{
                            color: blue;
                            border-bottom: 1px blue solid;
                        }
                    }   
                }
            }
        }
   }
</style>