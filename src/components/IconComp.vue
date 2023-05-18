<script>
export default {
    name: "IconComp",
    data() {
        return {
            icons: [
                {
                    nome: "digital Comics",
                    path: "buy-comics-merchandise.png"
                },
                {
                    nome: "digital Comics",
                    path: "buy-comics-merchandise.png"
                },
                {
                    nome: "digital Comics",
                    path: "buy-comics-merchandise.png"
                },
                {
                    nome: "digital Comics",
                    path: "buy-comics-merchandise.png"
                },
                {
                    nome: "digital Comics",
                    path: "buy-comics-merchandise.png"
                },
            ]
        }

    }
}

</script>

<template>
    <div id="area-icons">
        <div class="container">
            <ul>
                <li v-for="(element, index) in icons" :key="index">
                    <img :src="`/img/${element.path}`" alt="nome icona">
                    <span class="icon-text"> {{ element.nome }} </span>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss">
#area-icons {
    background-color: #0282F9;
    padding: 15px 0;

    .container {
        width: 80%;
        margin: 0 auto;

        ul {
            display: flex;
            align-items: center;
            justify-content: space-around;

            li {
                display: flex;
                align-items: center;
                list-style: none;

                img {
                    width: 40px;
                    margin-right: 10px;
                }

                span {
                    font-size: 15px;
                    color: white;
                }
            }
        }
    }
}</style>