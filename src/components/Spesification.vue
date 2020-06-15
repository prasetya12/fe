<template>
    <section class="container-spesification">
        <div class="container">
            <div class="row center">
                <h2 class="title">Powerfull dengan Limit PHP yang lebih Besar</h2>
                <table class="table-spesification">
                    <tr>
                        <td>
                            <span class="checklist"><img alt="Vue icon" src="../assets/images/checklist.png"></span>
                        </td>
                        <td><p>max execution time 300s</p></td>
                    </tr>
                    <tr>
                        <td><span class="checklist"><img alt="Vue icon" src="../assets/images/checklist.png"></span></td>
                        <td><p>max execution time 300s</p></td>
                    </tr>
                    <tr>
                        <td><span class="checklist"><img alt="Vue icon" src="../assets/images/checklist.png"></span></td>
                        <td><p>php memory limit 1024 MB</p></td>
                    </tr>
                </table>
                <table class="table-spesification">
                    <tr>
                        <td>
                            <span class="checklist"><img alt="Vue icon" src="../assets/images/checklist.png"></span>
                        </td>
                        <td><p>post max size 128 MB</p></td>
                    </tr>
                    <tr>
                        <td><span class="checklist"><img alt="Vue icon" src="../assets/images/checklist.png"></span></td>
                        <td><p>upload max filesize 128 MB</p></td>
                    </tr>
                    <tr>
                        <td><span class="checklist"><img alt="Vue icon" src="../assets/images/checklist.png"></span></td>
                        <td><p>max input vars 2500</p></td>
                    </tr>
                </table>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name:"Spesification"
}
</script>
<style lang="scss" scoped>
    .title {
        margin: 0 auto;
        padding-bottom: 30px;
        width: 100%;
    }
    .center{
        text-align: center;
        .table-spesification {
            width: 47%;
            border-collapse: collapse;
            border: 1px solid #f4f4f4;
            margin: 20px auto;
            @media(max-width: 480px){
                width: 100%;
            }
            tr {
                td {
                    border-bottom: 1px solid #f4f4f4;
                    border-top: 1px solid #f4f4f4;
                    padding: 10px 0 10px 20px;
                }
                &:nth-child(even) {
                    background: #F7F7F7;
                }
            }
        }
    }

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
</style>