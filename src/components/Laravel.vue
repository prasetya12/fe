<template>
    <section class="container-laravel w-border-bottom">
        <div class="container">
            <div class="row box-wrap">
                <h3 class="title">
                    Mendukung Penuh Framework Laravel
                </h3>
                <div class="col-md-7 col-sm-6 col-xs-12 m-fw text">
                    <div class="left-text">
                        <p class="sub-title">Tak perlu menggunakan dedicated server ataupun VPS yang mahal. 
                            Layanan PHP hosting murah dari kami mendukung penuh framework favorit Anda</p>
                        <ul>
                            <li>
                                <span class="checklist"><img alt="laravel images" src="../assets/images/checklist.png"></span>
                                <p>Install Laravel <strong>1 klik</strong> dengan Softaculous Installer.</p>
                            </li>
                            <li>
                                <span class="checklist"><img alt="laravel images" src="../assets/images/checklist.png"></span>
                                <p>Mendukung ekstensi <strong>PHP MCrypt, phar, mbstring, json,</strong> dan <strong>fileinfo</strong>.</p>
                            </li>
                            <li>
                                <span class="checklist"><img alt="laravel images" src="../assets/images/checklist.png"></span>
                                <p>Tersedia <strong>Composer</strong> dan <strong>SSH</strong> untuk menginstal packages pilihan Anda</p>
                            </li>
                        </ul>
                        <p class="small nb">Nb. Composer dan SSH hanya tersedia pada paket Personal dan Bisnis</p>
                        <button class="btn btn-rounded btn-solid-blue">Pilih Hosting Anda</button>
                    </div>
                </div>
                <div class="col-md-5 col-sm-6 col-xs-12 m-fw images">
                    <div class="right-image">
                        <img alt="Vue logo" src="../assets/svg/laravel_hosting.svg">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name:"Laravel"
}
</script>

<style lang="scss" scoped>
    .title {
        margin: 0 auto;
        padding-bottom: 30px;
        width: 100%;
    }

    .container-laravel{
        .sub-title{
            font-size: 19px;
        }
        .right-image{
            img {
                width: 100%;
                position: relative;
                right: 0;
                top: 76px;
                @media(max-width:768px){
                    top: 0;
                }
            }
        }
        .nb {
            padding-top: 20px;
        }
    }

    .left-text{
        text-align: left;
        margin-left: -15px;
        ul {
            li {
                display: flex;
                align-items: center;
                padding: 15px 0 0;
                p{
                    padding-left: 10px;
                }
            }
        }
    }

    .checklist {
        background: #00B348;
        width: 20px;
        height: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 100%;
        img {
            width: 10px;
        }
    }

    .btn {
        font-weight: 700 !important;
        border-radius: 100px !important;
        padding: 10px 30px !important;
        margin-top: 40px;
        font-size: 1.2em !important;
    }

    .btn-solid-blue {
        background: #2a8dea !important;
        color: #fff !important;
    }
</style>