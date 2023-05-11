<script>
    export default{
        name: "FooterComp",
        data(){
            return{
                footerIcons:[
                    {
                        path:"footer-facebook.png"
                    },
                    {
                        path:"footer-periscope.png"
                    },
                    {
                        path:"footer-pinterest.png"
                    },
                    {
                        path:"footer-twitter.png"
                    },
                    {
                        path:"footer-youtube.png"
                    }          

                ]
            }
        }

    }

</script>

<template>
    <footer>
        <div class="container">
            
            <div class="col-1">
                <div id="footer-info-col-1">
                    <h4>de comics</h4>
                    <ul>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                    </ul>
                    <h4>de comics</h4>
                        <ul>
                            <li>
                                <a href="">ciao</a>
                            </li>
                            <li>
                                <a href="">ciao</a>
                            </li>
                            <li>
                                <a href="">ciao</a>
                            </li>
                        </ul>
                </div>

                <div id="footer-info-col-2">
                    <h4>de comics</h4>
                    <ul>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                    </ul>
                </div>

                <div id="footer-info-col-3">
                    <h4>de comics</h4>
                    <ul>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                        <li>
                            <a href="">ciao</a>
                        </li>
                    </ul>
                </div>

            </div>
        </div>
        <!-- footer icone -->
        <div class="container-icons">
            <div class="centramento">
                <div>
                    <button>sign-up now</button>                
                </div>
                <div class="footer-social">
                    <a href="">follow us</a>
                    <div class="footer-icons">
                        <ul>
                            <li v-for="(element,index) in footerIcons" :key="index">
                                <img :src="`/img/${element.path}`" alt="icon">                                
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </footer>

</template>

<style lang="scss">
    footer{
        background-image: url('/img/footer-bg.jpg');
        color: white;
        .container{
            padding: 30px 0;
            margin: 0 auto;
            width: 80%;
            background-image: url('/img/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-size: 35%;
            background-position: center right;
            div{
                width: 50%;
                h4{
                    text-transform: uppercase;
                }
                ul{
                    li{
                        list-style: none;
                        line-height: 190%;
                        a{
                            text-decoration: none;
                            color: white;
                        }
                        
                    }
                }
            }
            .col-1{
                display: flex;
            }
        }
        //footer icone social
        .container-icons{
            background-color: #292929;
            .centramento{
                width: 80%;
                margin: 0 auto;
                display: flex;
                justify-content: space-between;
                align-items: center;
                .footer-social{
                    display: flex;
                    align-items: center;
                a{
                    text-decoration: none;
                }
                div{
                    ul{
                        display: flex;
                        li{
                            list-style: none;
                        }
                    }
                }
            }
            }

        }

    }

</style>