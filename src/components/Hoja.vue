<template>

    <main>
        <nav class="menu">
            <li>Curriculum Vitae</li>
            <!-- <li> <a href="robin">acerca de</a> </li> -->
            <li><a href="@/components/Acerca.vue">acerca de </a></li>
            <li> cv</li>
            <li> conctacto</li>
            <img src="../assets/yo.jpeg" alt="yop" srcset="" width="16%">
            <p id="p">descarga cv</p>


        </nav>
        <section class="img">

        </section>
        <br>
        <p></p>
        <section class="info">
            <h1><b>Robinson truque valencia</b> </h1>
            <h2>Aprendiz de adsi</h2>
            <li><b>Fecha nacimiento</b>febrero 11/2004</li>
            <li><b>lugar nacimiento</b>popayan/cauca</li>
            <LI><b>Telefono</b> 3016038492</LI>
            <li><b>Genero</b>Masculino</li>
            <li><b>Emaill</b> rtruque6@misena.edu.co</li>
            <li><b>Direccion</b> Popayan/Cauca</li>


        </section>
        <hr>
        <section id="hola">
            <div id="robin">
            <h1> Acerca de</h1>


                <p>soy Aprendiz de CTPI  de el programaa ADSI  </p>
            </div>
            <hr>
            <h1>HABILIDADES CLAVE </h1>
            <div class="habi">
            <li>Manejo bien los programas como html, js,css,python,java,vue</li>
            </div>
            <hr>
            <h1>VIDA LABORAL</h1>

            <div>
                <li>Ninguna por el momento</li>
          
            <p><b>2022-actual</b></p>
            <p><b>creador de sitios web</b></p>
            <p>Tecnologo ADSI</p>
            <p>Popayan/Cauca</p>
                <hr>
            
            <p><b>2022-2023</b></p>
            <p><b>Creador de sitios web</b></p>
            <p>Tecnologo adsi</p>
            <p>Popayan/Cauca</p>
            </div>
            <hr>
            <div>

                <p><b>2022-2023</b></p>
                <p><b>Sena</b></p>
                <p>Tecnologo adsi</p>
                <p>Popayan/Cauca</p>

            </div>

            <hr>
            <h1>MAYORES LOGROS</h1>
            <div>

                <li>
                    Aprender los direntes lenguajes y tener la oportunidad de participar en un bootcamp
                </li>
                <li>Megusta la progrmacion y me siemto bien tanto backen como frontend

                </li>
                <li>He estado en difrentes complementarios de larabel, node js

                </li>


            </div>

            <hr>
            <h1>CONTACTO</h1>
            <div class="conctacto">


                <LI><b>Telefono</b> 3016038492</LI>
                <li><b>Emaill</b> rtrque6@misena.edu.co</li>
                <li><b>Direccion</b> Popayan/Cauca</li>
            </div>

        </section>
    </main>
</template>
<script>

export default {

    name: 'Hoja-',
    props: {
        msg: String
    }
}
</script>

<style>
.menu {
    list-style: none;
    display: flex;
    justify-content: space-between;
    border: solid 2px;

}

.img {

    display: flex;
    justify-content: end;
    border: solid 2px;

}

.info {
    list-style: none;

    border: solid 2px;

}

h1 {
    display: flex;
    justify-content: center;
}

#p {
    background-color: black;
    color: aliceblue;
    height: 5%;
}

#acerca {

    width: 85vh;
    border: solid 2px;
}

.conctacto {
    list-style: none;

}

a:hover {
    color: #07d544;
    cursor: pointer;
}
</style>