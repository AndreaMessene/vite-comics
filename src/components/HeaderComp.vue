<script >
    export default{
        name: 'HeaderCompt',
        data(){
            return{
                menuLinks: [

                    {
                        url:'#',
                        name:'CHARACTERS',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'COMICS',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'MOVIES',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'TV',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'GAMES',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'COLLECTIBLES',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'VIDEOS',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'FANS',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'NEWS',
                        current:'false'
                    },

                    {
                        url:'#',
                        name:'SHOP',
                        current:'false'
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

</style>