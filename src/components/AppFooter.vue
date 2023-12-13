<script>
export default {
    components: {

    },
    data() {

    },
}
</script>
<template>
    <footer>
        <div class="container">
            <div class="footer-row  d-md-flex  d-sm-flex">
                <div class="footer-body d-flex flex-wrap ">
                    <div class="footer-title">
                        <h3 class="font-weight-bold">BDoctors</h3>
                    </div>
                </div>
                <div class="div d-flex flex-wrap justify-content-between">
                    <div class="footer-text">
                        <ul>
                            <li><a href="#">Home</a></li>
                            <li><a href="/about-us">Chi siamo</a></li>
                            <li><a href="#ancor-spec">Tiplogie Servizi</a></li>
                            
                        </ul>
                    </div>
                    <div class="footer-text">
                        <ul>
                                <h4 class="text-white">Per i professionisti sanitari</h4>
                            <li><a href="#">Formazione e Corsi</a></li>
                            <li><a href="#">Informazioni Struttura Sanitaria</a></li>
                            <li><a href="#">Partnerships</a></li>
                        </ul>
                    </div>
                    <div class="footer-text">
                        <ul>
                            <h4 class="text-white">Termini e condizioni</h4>
                            <li><a href="#">Privacy Policy</a></li>
                            <li><a href="#">Cookie Policy</a></li>
                            <li><a href="#">Condizioni di Servizio</a></li>
                        </ul>
                    </div>
                </div>
                <div class="downloand-app">
                    <div>
                        <img src="https://wi-fi.hk/Images/google_play_n.png" alt="" width="100px">
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<style lang="scss" scoped>
footer {
    background-color: #242424;
    padding: 40px 10px;

    .footer-body {
         padding-left: 2rem;
    }
}

h4{
    color: rgb(175, 175, 35);
}

.footer-row {
    //display: flex;
    justify-content: space-between;
    padding: 20px 0;

    .footer-title {
        color: rgb(175, 175, 35);

        p {
            font-weight: 100;
        }
    }

    .downloand-app {
        h5 {
            color: #fff;
        }
    }

    .footer-text {
        font-size: 14px;

        h4{
            font-weight: bold;
        }
        ul {
            li {
                list-style: none;
                color: #fff;
                font-weight: 100;
            }
        }
        li:hover{
            background-color: #ffffff;
        }

        a {
            text-decoration: none;
            font-size: 1rem;
            color: #fff;
        }
        a:hover{
            color:black;
            font-weight: bold;
        }
    }

}

</style>