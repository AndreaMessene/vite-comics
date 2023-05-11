<script>
    export default{
        name: "FooterComp",

    }

</script>

<template>
    <footer>
        <div class="container">
            <div class="col-1">
                <div id="footer-info-generali">
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
                <div id="footer-info-generali">
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
                <div id="footer-info-generali">
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
            <div>

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
    }

</style>