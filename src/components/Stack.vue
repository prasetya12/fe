<template>
    <section class="box-wrapper">
        <div class="container">
            <div class="row">
                <div class="col-md-4 item">
                    <span class="icon">
                        <img src="../assets/svg/icon_hosting_zendguard.svg">
                    </span>
                    <p>PHP Send Guard Loader</p>
                </div>
                 <div class="col-md-4 item">
                    <span class="icon">
                        <img src="../assets/svg/icon_hosting_composer.svg">
                    </span>
                    <p>PHP Composer</p>
                </div>
                <div class="col-md-4 item">
                    <span class="icon">
                        <img src="../assets/svg/icon_hosting_ioncube.svg">
                    </span>
                    <p>PHP IonCube Loader</p>
                </div>
                <!-- <ul>
                    <li>
                        <span class="icon">
                            <img src="../assets/svg/icon_hosting_zendguard.svg">
                        </span>
                        <p>PHP Send Guard Loader</p>
                    </li>
                    <li>
                        <span class="icon">
                            <img src="../assets/svg/icon_hosting_composer.svg">
                        </span>
                        <p>PHP Composer</p>
                    </li>
                    <li>
                        <span class="icon">
                            <img src="../assets/svg/icon_hosting_ioncube.svg">
                        </span>
                        <p>PHP IonCube Loader</p>
                    </li>
                </ul> -->
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name:'Stack'
}
</script>

<style lang="scss" scoped>
    .box-wrapper {
        font-family: 'Montserrat', sans-serif;
        ul {
            text-align: center;
            width: 100%;
            li {
                display: inline-block;
                padding: 0 70px;
                @media(max-width: 768px){
                    padding: 20px 30px;
                }
                .icon {
                    height: 200px;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    @media(max-width: 480px){
                        height: unset;
                        padding-bottom: 20px;
                    }
                    img {
                        width: 200px;
                    }
                }
                &:nth-of-type(2){
                    .icon{
                        img {
                            width: 130px;
                        }
                    }
                }
            }
        }

        .item{
            padding: 0 70px;
            @media(max-width: 768px){
                padding: 20px 30px;
            }
            .icon {
                    height: 200px;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    @media(max-width: 480px){
                        height: unset;
                        padding-bottom: 20px;
                    }
                    img {
                        width: 200px;
                    }
                }
                &:nth-of-type(2){
                    .icon{
                        img {
                            width: 130px;
                        }
                    }
                }
        }
    }
</style>