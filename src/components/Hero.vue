<template>
    <section class="w-border-bottom">
        <div class="container">
            <div class="row box-wrap">
                <div class="col-sm-6 col-xs-12 col-xs-12 m-fw text">
                    <div class="left-text hero-title">
                        <h2>
                            <strong>
                                PHP Hosting
                            </strong>
                        </h2>
                        <h2>
                            Cepat, handal, penuh dengan modul PHP yang Anda butuhkan
                        </h2>
                        <ul>
                            <li>
                                <span class="checklist">
                                    <img alt="hero icon" src="../assets/images/checklist.png">
                                </span>
                                <p>Solusi PHP untuk performa query yang lebih cepat.</p>
                            </li>
                            <li>
                                <span class="checklist">
                                    <img alt="hero icon" src="../assets/images/checklist.png">
                                </span>
                                <p>Konsumsi memory yang lebih rendah.</p>
                            </li>
                            <li>
                                <span class="checklist">
                                    <img alt="hero icon" src="../assets/images/checklist.png">
                                </span>
                                <p>Support PHP 5.3, PHP 5.4, PHP 5.5, PHP 5.6, PHP 5.7</p>
                            </li>
                            <li>
                                <span class="checklist">
                                    <img alt="hero icon" src="../assets/images/checklist.png">
                                </span>
                                <p>Fitur enkripsi IonCube dan Zen Guard Loaders.</p>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-sm-6 col-xs-12 col-xs-12 m-fw images">
                    <div class="right-image">
                        <img alt="hero image" src="../assets/svg/banner_php_hosting.svg">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name:'Hero'
}   
</script>

<style lang="scss" scoped>

    .checklist{
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
    .w-border-bottom{
        border-bottom: 2px solid #f4f4f4;
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

    section{
    @media(max-width:768px){
        .box-wrap {
            display: block;
            .m-fw {
                max-width: 100% !important;
                display: table;
            }
            .text {
                display: table-cell;
                .left-text {
                    text-align: left;
                    margin-left: -15px;
                    padding-top: 20px;
                }
            }
            .images {
                display: table-header-group;
            }
        }
    }
    @media(max-width: 480px){
        .row{
            margin: 0;
            .left-text {
                li{
                    p{
                        width: 90%;
                    }

                }
            }
        }
    }

}   
</style>