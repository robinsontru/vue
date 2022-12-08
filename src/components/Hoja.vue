<template>

    <main>
        <nav class="menu">
            <li>Curriculum Vitae</li>
            <!-- <li> <a href="robin">acerca de</a> </li> -->
            <li><a href="#hola">acerca de </a></li>
            <li> cv</li>
            <li> conctacto</li>
            <img src="" alt="logo" srcset="" width="16%">
        <p id="p">descarga cv</p>


        </nav>
        <section class="img">
           
        </section>
        <section class="info">
            <h1><b>Robinson truque valencia</b> </h1>
            <h2>aprendiz de adsi</h2>
            <LI><b>telefono</b> 3016038492</LI>
            <li><b>emaill</b> rtrque6@misena.edu.co</li>
            <li><b>direccion</b> popayan/cauca</li>
   

        </section>
        <hr>
        <section id="hola">
            <div id="robin">
                <h1> acerca de</h1>
                <p>Párrafo. Haz clic aquí para agregar tu propio texto y editarlo. Es fácil. Haz clic en "Editar texto"
                    o doble clic aquí para agregar tu contenido y cambiar la fuente. En este espacio puedes contar tu
                    historia y permitir que los usuarios sepan más sobre ti.

                </p>
            </div>
             <hr>
            <h1>HABILIDADES CLAVE </h1>


            <div class="habi">
                <li>manejo bien los programas como html, js,css,python,java,vue

                </li>
                <li>

                </li>
                <li>
                </li>
                <li>

                </li>
            </div>
            <hr>
            <h1>VIDA LABORAL</h1>

            <div>


                <li>Ninguna por el momento

                </li>
                <!-- <li>Párrafo. Haz clic aquí para agregar tu propio texto y editar. Aquí puedes contar tu historia y
                    permitir que tus usuarios sepan más sobre ti.

                </li>
                <li>Párrafo. Haz clic aquí para agregar tu propio texto y editar. Aquí puedes contar tu historia y
                    permitir que tus usuarios sepan más sobre ti.

                </li>
                <li>Párrafo. Haz clic aquí para agregar tu propio texto y editar. Aquí puedes contar tu historia y
                    permitir que tus usuarios sepan más sobre ti.

                </li> -->
            </div>

            <hr>
            <div>
                
                <p><b>2022-2022</b></p>
                <p><b>creador de sitios web</b></p>
                <p>entrenamiento de algoritmia fabrica </p>
                <p>popayan/cauca</p>
                <hr>
                <p><b>2022-actual</b></p>
                <p><b>creador de sitios web</b></p>
                <p>tecnologo adsi</p>
                <p>popayan/cauca</p>
<hr>

                <p><b>2022-2023</b></p>
                <p><b>creador de sitios web</b></p>
                <p>tecnologo adsi</p>
                <p>popayan/cauca</p>
<hr>


                <p><b>2022-2023</b></p>
                <p><b>creador de sitios web</b></p>
                <p>tecnologo adsi</p>
                <p>popayan/cauca</p>
            </div>
            <hr>
            <div>

                <p><b>2022-2023</b></p>
                <p><b>sena</b></p>
                <p>tecnologo adsi</p>
                <p>popayan/cauca</p>

            </div>

            <hr>
            <h1>MAYORES LOGROS</h1>
            <div>

                <li>
                    aprender los direntes lengfuajes y tener la oportunidad de participar en un bootcamp
                </li>
                <li>megusta la progrmacion y me siemto bien tanto backen como frontend
    
                </li>
                <li>he estado en difrentes complementarios de larabel, node js 
    
                </li>


            </div>

            <hr>
            <h1>CONTACTO</h1>
            <div class="conctacto">


                <LI><b>telefono</b> 3016038492</LI>
                <li><b>emaill</b> rtrque6@misena.edu.co</li>
                <li><b>direccion</b> popayan/cauca</li>
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
    border: solid 1px;
    
}

.img {

    display: flex;
    justify-content: end;
    border: solid 1px;

}

.info {
    list-style: none;

    border: solid 1px;

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
    border: solid 1px;
}

.conctacto {
    list-style: none;

}
a:hover {
    color: #07d544;
    cursor: pointer;
  }
 
</style>