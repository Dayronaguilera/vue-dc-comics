<template> 
    <nav class="bg-nav ">
        <div class="container-nav container">
            <div class="img-container">
                <img src="../assets/dc-logo.png" alt="dc-logo">         
            </div>
            <div class="container-menu">
                <ul>
                    <li v-for="element in nav" :key="element.id">
                        <a href="#">{{element.name}}</a>
                    </li>
                    <!-- <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li> -->
                </ul>
            </div>  
        </div> 
    </nav>
</template>

<script>
export default {
    name: "Header",
    data: function() {
        return {
            nav: [
                {
                    id: 0,
                    name: 'CHARACTERS',
                },
                {
                    id: 1,
                    name: 'COMICS',
                },
                {
                    id: 2,
                    name: 'MOVIES',
                },
                {
                    id: 3,
                    name: 'TV',
                },
                {
                    id: 4,
                    name: 'GAMES',
                },
                {
                    id: 5,
                    name: 'COLLECTIBLES',
                },
                {
                    id: 6,
                    name: 'VIDEOS',
                },
                {
                    id: 7,
                    name: 'FANS',
                },
                {
                    id: 8,
                    name: 'NEWS',
                },
                {
                    id: 9,
                    name: 'SHOP',
                },
            ]
        }
    } 
    
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
                         a{
                             text-decoration: none;
                             color: rgb(156, 156, 156);

                            &:hover{
                                color: rgb(22, 123, 240);
                                text-decoration: underline;
                            }
                         }
                    }   
                }
            }
        }
   }
</style>