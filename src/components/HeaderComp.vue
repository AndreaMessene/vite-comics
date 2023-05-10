<script >
    export default{
        name: 'HeaderCompt', 
        data(){
            return{
                menuLinks: [

                    {
                        url:'#',
                        name:'characters',
                        current: false
                    },

                    {
                        url:'#',
                        name:'comics',
                        current: true
                    },

                    {
                        url:'#',
                        name:'movies',
                        current: false
                    },

                    {
                        url:'#',
                        name:'tv',
                        current: false
                    },

                    {
                        url:'#',
                        name:'games',
                        current: false
                    },

                    {
                        url:'#',
                        name:'collectibles',
                        current: false
                    },

                    {
                        url:'#',
                        name:'videos',
                        current: false
                    },

                    {
                        url:'#',
                        name:'fans',
                        current: false
                    },

                    {
                        url:'#',
                        name:'news',
                        current: false
                    },

                    {
                        url:'#',
                        name:'shop',
                        current: false
                    }

                ]
            }
        }
    }
</script>

<template>
    <header>
        <nav class="">
            
            <img src="../../public/img/dc-logo.png" alt="">
            <ul>
                <li v-for="(element, index) in menuLinks" 
                    :key="index"
                    :class="element.current ? 'active' : '' ">
                    <a href="element.url"> {{ element.name}} </a>
                </li> 
            </ul>

        </nav>
    </header>

    
</template>

<style scoped lang="scss">
    header{
        nav{
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: space-around;
            
            img{
                height: 60px;
            }
            ul{
                display: flex;
                li{
                    list-style: none;
                    margin: 0 10px;
                    line-height: 100px;
                    a{
                        text-decoration: none;
                        color: black;
                        text-transform: uppercase;
                        font-weight: bold;
                        font-size: 0.85rem;
                    }
                    &.active{
                        border-bottom: 3px solid blue;
                        
                    }
                    &.active a{
                        color: blue;
                    }
                }
            }
        }
    }
</style>