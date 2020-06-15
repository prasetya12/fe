<template>
    <div class="header-container">
        <div class="top-header">
            <div class="container">
                <div class="row box-wrap">
                    <div class="left">
                        <span class="icon"><img alt="icon header" src="../assets/images/price.png"></span>
                        <p>gratis ebook 9 cara cerdas menggunakan domain [ x ]</p>
                    </div>
                    <div class="right ml-auto">
                        <ul>
                            <li>
                                <a href="#">
                                    <span class="icon">
                                        <img src="../assets/images/phone.png">
                                    </span>
                                        <p>0274-5305505</p>

                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    <span class="icon"><img alt="Vue icon" src="../assets/images/chat.png"></span>
                                    <p>live chat</p>
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    <span class="icon"><img alt="Vue icon" src="../assets/images/user.svg"></span>
                                    <p>member area</p>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="navbar-menu">
            <div class="container">
                <div class="row box-wrap">
                    <nav class="navbar navbar-expand-lg">
                        <a class="navbar-brand" href="#">
                            <img alt="niagahoster logo" src="../assets/images/niagahoster-logo.png">
                        </a>
                        <button class="navbar-toggler" type="button" data-toogle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon">
                                <img alt="logo button" src="../assets/images/bars.png">
                            </span>
                        </button>

                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav ml-auto">
                                <li class="nav-item active">
                                    <a class="nav-link" href="#">
                                        Hosting
                                        <span class="sr-only">(current)</span>
                                    </a>
                                </li>
                                <li class="nav-item ">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Domain
                                        </span>
                                    </a>
                                </li>
                                <li class="nav-item ">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Server
                                        </span>
                                    </a>
                                </li>
                                <li class="nav-item ">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Website
                                        </span>
                                    </a>
                                </li>
                                <li class="nav-item ">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Afiliasi
                                        </span>
                                    </a>
                                </li>
                                <li class="nav-item ">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Promo
                                        </span>
                                    </a>
                                </li>
                                <li class="nav-item ">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Pembayaran
                                        </span>
                                    </a>
                                </li>
                                <li class="nav-item ">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Review
                                        </span>
                                    </a>
                                </li>
                                <li class="nav-item ">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Kontak
                                        </span>
                                    </a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">
                                        <span>
                                            Blog
                                        </span>
                                    </a>
                                </li>
                            </ul>

                        </div>
                    </nav>
                </div>
            </div>

        </div>

    </div>
</template>

<script>
export default {
    name:'Header'
}
</script>

<style lang="scss" scoped>
    .top-header{
        border-bottom: 1px solid #f4f4f4;
        padding-bottom: 20px;
        .left{
            display: flex;
            align-items: center;
            .icon{
                background-color: #0090EF;
                text-align: center;
                margin-right: 20px;
                position: relative;
                width:27px;
                height: 40px;
                padding:2px 0 0;
                img{
                    width: 18px;
                }
                &::after{
                    content:'';
                    width: 0;
                    height: 0;
                    border-left: 14px solid transparent;
                    border-right: 14px solid transparent;
                    border-bottom: 10px solid #fff;
                    position: absolute;
                    left: 0;
                    right: 0;
                    margin:0 auto;
                    bottom: 0;
                }
            }
        }

        .right{
            ul{
                display: flex;
                position: relative;
                top: 15px;
                li{
                    a{
                        display: flex;
                        padding-left: 20px;
                        align-items: center;
                        color: black;
                        .icon{
                            padding-right: 10px;
                            img{
                                width: 20px;
                            }
                        }
                        p{
                            margin-bottom: 0;
                            text-transform: capitalize;
                            font-size: 14px;
                        }
                    }
                }
            }
        }
        p{
            margin: 0;
            text-transform: capitalize;
            font-size: 14px;
        }
    }

    .navbar-menu{
        padding:10px 0;
        border-bottom: 2px solid #f4f4f4;
        .navbar{
            width:100%;
            padding: 0;
            @media(max-width:1024px){
                display: block ;
            }
            @media(max-width:768px){
                display: flex ;
            }
            .navbar-brand{
                img{
                    width: 300px;
                }
                @media(max-width:480px){
                    width: 200px;
                }
            }
            .navbar-nav {
                .nav-item{
                    a{
                        color: black;

                    }
                    a:hover{
                        color: #27aae1;

                    }
                }
                @media(max-width: 1024px){
                    margin: 0 auto !important;
                }
            }
            .navbar-toggler{
                background-color: #27aae1;
                padding: 0px;
                .navbar-toggler-icon {
                    display: flex;
                    align-items: center;
                    justify-content: center;
                }
                img{
                    width: 20px;
                }
                
            }
            .navbar-collapse{
                ul{
                    padding-top: 20px;
                }
            }
        }
    }

</style>