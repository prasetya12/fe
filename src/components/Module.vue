<template>
    <section class="container-module">
        <div class="container">
            <div class="row">
                <h3 class="title">Modul Lengkap untuk Menjalankan 
                    Aplikasi PHP Anda.</h3>
            </div>
            <div class="d-flex flex-row">
                <ul>
                    <li>Ice PHP</li>
                    <li>apc</li>
                    <li>apcu</li>
                    <li>apm</li>
                    <li>ares</li>
                    <li>bcmatth</li>
                    <li>bcompiler</li>
                    <li>big_int</li>
                    <li>bitset</li>
                    <li>bloomy</li>
                    <li>bz2_filter</li>
                    <li>clamav</li>
                    <li>coin_acceptor</li>
                    <li>Crack</li>
                    <li>dba</li>
                </ul>
                <ul>
                    <li>http</li>
                    <li>huffman</li>
                    <li>idn</li>
                    <li>igbnary</li>
                    <li>imagick</li>
                    <li>imap</li>
                    <li>included</li>
                    <li>inotify</li>
                    <li>intebase</li>
                    <li>intl</li>
                    <li>ioncube_loader</li>
                    <li>ioncube_loader_4</li>
                    <li>jsmin</li>
                    <li>json</li>
                    <li>Idap</li>
                </ul>
                <ul>
                    <li>nd_pdo_MySQL</li>
                    <li>oauth</li>
                    <li>oci8</li>
                    <li>odbc</li>
                    <li>opache</li>
                    <li>pdf</li>
                    <li>pdo</li>
                    <li>pdo_dblib</li>
                    <li>pdo_firebird</li>
                    <li>pdo_mysql</li>
                    <li>pdo_odbc</li>
                    <li>pdo_pgsql</li>
                    <li>pdo_sqlite</li>
                    <li>pgsql</li>
                    <li>phalcon</li>
                </ul>
                <ul>
                    <li>stats</li>
                    <li>stem</li>
                    <li>stomp</li>
                    <li>suhosin</li>
                    <li>sybase_ct</li>
                    <li>sysvmsg</li>
                    <li>sysvsem</li>
                    <li>sysvshm</li>
                    <li>tidy</li>
                    <li>timezonedb</li>
                    <li>trader</li>
                    <li>translit</li>
                    <li>uploadprogress</li>
                    <li>uri_template</li>
                    <li>uuid</li>
                </ul>
            </div>
            <button class="btn btn-outline-black">Selengkapnya</button>

        </div>
    </section>
</template>
<script>
export default {
    name:"Module"
}
</script>
<style lang="scss" scoped>
    .title {
            margin: 0 auto;
            padding-bottom: 30px;
            width: 100%;
        }
    .container-module {
        ul {
            width: 25%;
            padding: 20px;
            @media(max-width: 480px){
                width: 50%;
            }
        }
        .btn {
            margin: 20px auto 0;
            font-weight: 700 !important;
            border-radius: 100px !important;
            padding: 10px 30px !important;
            margin-top: 40px;
            font-size: 1.2em !important;
        }
        .btn-outline-black {
            border: 2px solid #2d3e50 !important;
        }
    }
</style>