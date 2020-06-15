<template>
    <section class="container-chat">
        <div class="container">
            <div class="row align-center">
                <h2>Perlu <strong>BANTUAN?</strong>  Hubungi kami : <strong>0274-5305505</strong></h2>
                <button class="btn btn-outline-white ml-auto"> <img alt="Vue logo" src="../assets/images/chat-white.png">Live Chat</button>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name:"Chat"
}
</script>

<style lang="scss" scoped>
    .container-chat {
        background: #2b8cea;
        color: #fff;
        .btn {
            margin-top: 0;
            color: #fff;
            img {
                width: 30px;
                margin-right: 10px;
            }
        }
        .align-center {
            @media(max-width: 1024px){
            display: block;}
            .btn{
                margin-top: 20px;
            }
        }
    }

    .btn {
        font-weight: 700 !important;
        border-radius: 100px !important;
        padding: 10px 30px !important;
        margin-top: 40px;
        font-size: 1.2em !important;
    }

    .btn-outline-white {
        border: 2px solid #fff !important;
        color: #fff;
    }

    .right-image {
        margin-right: -15px;
        text-align: right;
        @media(max-width:768px){
            margin-right: 0;
            text-align: center;
            img{
                width: 70% !important;
            }
        }
        @media(max-width:480px){
            img{
                width: 100% !important;
            }
        }
        img {
            width: 90%;
        }
    }
</style>