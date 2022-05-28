# Trabajo-Final-BS
Proyecto final del curso de desarrollo en bootsrap
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Cúmulo Ingenieria
    </title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body style="background-color: black;">
    <header>
      <nav class="navbar bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand">CUMULO WEB</a>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Buscar</button>
          </form>
        </div>
      </nav>
      <div
        class="cover d-flex justify-content-center align-items-center flex-column p-5"
        style="
        height: 300px;
        background-position: center;
        background-size: cover;
          background-image: url(https://cdn.glitch.global/6124bffa-305e-45ab-9581-3d2c96214296/rsz_kaye-lark-ycujcnx-h88-unsplash.jpg?v=1648500572486);
        "
      >
        <h1>Cumulo Ingeniería
        </h1>
        <p>Trabajo final del curso de desarrollo en bootstrap</p>
        <a class="nav-link" href="https://www.instagram.com/cumulo.rosario/">
          <button class="btn btn-primary">Conoce más</button>
        </a>
      </div>
    </header>
    <section>
      <h1 style="color: cyan; font-size: 50px;">Cumulo Ingenieria:</h1>
      <p style="font-size: 25px; color: white">
        Cumulo Ingeniería Rosario es una empresa que ofrece soluciones
        innovadoras para el tratamiento de aguas y una gama de servicios.
        Nuestro objetivo es establecer los estándares de la industria que nos
        posicionen como líderes en nuestra categoría en todo el pais. Fabricando
        la mayoría de nuestros productos. Los miembros del equipo son ingenieros
        comprometidos en ofrecer soluciones diagramadas para proyectos
        relacionados con el agua. Contáctanos para solicitar información acerca
        de nuestros desarrollos.
      </p>
    </section>
    <!--3 PANELES-->
    <section>
      <div class="d-sm-flex">
        <div class="container mt-5 mb-5">
          <div class="card" style="width: 18rem; background-color: gray">
            <img
              src="https://cdn.glitch.global/6124bffa-305e-45ab-9581-3d2c96214296/rsz_daniel-smyth-mljzy6wkupu-unsplash.jpg?v=1653594419514"
              class="card-img-top"
              alt="Shampoo de primera calidad"
            />
            <div class="card-body">
              <h5 class="card-title">Contamos con mas de 15 años de experiencia</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque molestie massa sed lacus condimentum, nec mollis urna efficitur. Morbi in urna et nunc imperdiet mollis nec eu lacus.
              </p>
              <a href="productos.html" class="btn btn-primary"
                >Conoce nuestros productos</a
              >
            </div>
          </div>
        </div>

        <div class="container mt-5 mb-5">
          <div class="card" style="width: 18rem; background-color: gray">
            <img
              src="https://cdn.glitch.global/6124bffa-305e-45ab-9581-3d2c96214296/rsz_nuno-marques-0gbrjl3vzf4-unsplash.jpg?v=1653594297048"
              class="card-img-top"
              alt="Dodo también es animal friendly"
            />
            <div class="card-body">
              <h5 class="card-title">
                Líderes en el mercado
              </h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque molestie massa sed lacus condimentum, nec mollis urna efficitur. Morbi in urna et nunc imperdiet mollis nec eu lacus.
              </p>
              <a href="acercade.html" class="btn btn-primary"
                >Mas Información</a
              >
            </div>
          </div>
        </div>

        <div class="container mt-5 mb-5">
          <div class="card" style="width: 18rem; background-color: gray">
            <img
              src="https://cdn.glitch.global/6124bffa-305e-45ab-9581-3d2c96214296/rsz_yogesh-phuyal-mjwgkmwkdda-unsplash.jpg?v=1648508898654"
              class="card-img-top"
              alt="Shampoo de primera calidad"
            />
            <div class="card-body">
              <h5 class="card-title">
                Productos de primera calidad
              </h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque molestie massa sed lacus condimentum, nec mollis urna efficitur. Morbi in urna et nunc imperdiet mollis nec eu lacus.
              </p>
              <a href="acercade.html" class="btn btn-primary"
                >Conoce nuestro Staff</a
              >
            </div>
          </div>
        </div>
      </div>
    </section>
    <section>
      <h1 style="font-size: 80px; color: white">Nuestros productos:</h1>

      <div class="container mt-5 mb-5">
        <img
          src="https://cdn.glitch.global/6124bffa-305e-45ab-9581-3d2c96214296/Imagen%20boya.webp?v=1648506083511"
          height="400"
          class="float-end ml-4"
        />
        <h2 style="color: white">Boya ionizadora solar:</h2>

        <p style="color: white">
          El ionizador reemplaza en gran parte a los productos de pileta ( hasta
          en un 80%) por los iones de cobre que libera. De esta forma disminuye
          el mantenimiento que requiere y los costos. Al tener menos productos
          uno puede abrir los ojos debajo del agua y no quedan rojos, no daña la
          piel ni el pelo. Este proceso se puede realizar, porque tiene un panel
          solar superior que genera una carga y la hace pasar por dos
          electrodos, un resorte de inoxidable y un ánodo de cobre (este es un
          consumible). Cuando se sumerge en el agua, esta hace de conductora y
          se lleva los iones de cobre por toda la pileta. Al cabo de tres
          semanas, hay que empezar a disminuir el consumo de productos
          gradualmente hasta llegar al punto de equilibrio de cada pileta. Un
          ionizador va alcanza hasta una pileta de 8x4. de ser mas grande se
          necesitan 2, para que halla una buena distribucion de iones.
        </p>

        <h2 style="color: white">Información del producto</h2>
        <p style="color: white">
          El ionizador reemplaza en gran parte a los productos de pileta ( hasta
          en un 80%) por los iones de cobre que libera. De esta forma disminuye
          el mantenimiento que requiere y los costos. Al tener menos productos
          uno puede abrir los ojos debajo del agua y no quedan rojos, no daña la
          piel ni el pelo. Este proceso se puede realizar, porque tiene un panel
          solar superior que genera una carga y la hace pasar por dos
          electrodos, un resorte de inoxidable y un ánodo de cobre (este es un
          consumible). Cuando se sumerge en el agua, esta hace de conductora y
          se lleva los iones de cobre por toda la pileta. Al cabo de tres
          semanas, hay que empezar a disminuir el consumo de productos
          gradualmente hasta llegar al punto de equilibrio de cada pileta. Un
          ionizador va alcanza hasta una pileta de 8x4. de ser mas grande se
          necesitan 2, para que halla una buena distribucion de iones.
        </p>

        <h2 style="color: white">Garantía</h2>
        <p style="color: white">
          Ofrecemos garantía de fabrica cubriendo 6 meses de defectos de
          fabricación
        </p>

        <h2 style="color: white">Información del envío</h2>
        <p style="color: white">
          Realizamos envios a todo el pais sin costo adicional. Y en las
          localidades de Funes, Pueblo Esther y Rosario tambien ofrecemos el
          servicio de pago contra entrega.
        </p>
        <h1 style="color: white">Precio: $8500</h1>
          <a class="nav-link" href="https://walink.co/ffbd65"/>
          <button class="btn btn-primary">Comprar ya</button>
      </div>
    </section>
    <hr />
    <section>
      <div class="container mt-5 mb-5">
        <img
          src="https://cdn.glitch.global/6124bffa-305e-45ab-9581-3d2c96214296/ionizador.webp?v=1648506601365"
          height="400"
          class="float-end ml-4"
        />
        <h2 style="color: white">Ionizador electrónico en bomba:</h2>

        <p style="color: white">
   El ionizador reemplaza en gran parte a los productos de pileta (hasta en un 80%) por los iones de cobre que libera. De esta forma disminuye el mantenimiento que requiere y los costos. Al tener menos productos uno puede abrir los ojos debajo del agua y no quedan rojos, no daña la piel ni el pelo. Se le hace pasar una carga por dos electrodos de cobre produciendose el fenómeno de electrolisis y generando sulfato de cobre (éste cumple la función de alguicida). Al cabo de tres semanas, hay que empezar a disminuir el consumo de productos gradualmente hasta llegar al punto de equilibrio de cada pileta. Un ionizador cubre hasta una pileta de 100000 litros. Este equipo al estar ubicado en la bomba genera una muy buena distribucion de iones.
        </p>

        <h2 style="color: white">Información del producto</h2>
        <p style="color: white">
          El ionizador reemplaza en gran parte a los productos de pileta ( hasta
          en un 80%) por los iones de cobre que libera. De esta forma disminuye
          el mantenimiento que requiere y los costos. Al tener menos productos
          uno puede abrir los ojos debajo del agua y no quedan rojos, no daña la
          piel ni el pelo. Este proceso se puede realizar, porque tiene un panel
          solar superior que genera una carga y la hace pasar por dos
          electrodos, un resorte de inoxidable y un ánodo de cobre (este es un
          consumible). Cuando se sumerge en el agua, esta hace de conductora y
          se lleva los iones de cobre por toda la pileta. Al cabo de tres
          semanas, hay que empezar a disminuir el consumo de productos
          gradualmente hasta llegar al punto de equilibrio de cada pileta. Un
          ionizador va alcanza hasta una pileta de 8x4. de ser mas grande se
          necesitan 2, para que halla una buena distribucion de iones.
        </p>

        <h2 style="color: white">Garantía</h2>
        <p style="color: white">
          Ofrecemos garantía de fabrica cubriendo 6 meses de defectos de
          fabricación
        </p>

        <h2 style="color: white">Información del envío</h2>
        <p style="color: white">
   Se envía sin costo adicional a todo el país
        </p>
        <h1 style="color: white">Precio: $18000</h1>
         <a class="nav-link" href="https://walink.co/ffbd65"/>
          <button class="btn btn-primary">Comprar ya</button>
      </div>
    </section>

      <footer  class="bg-dark text-center text-white">
        <!-- Grid container -->
        <div class="container p-4 pb-0">
          <!-- Section: Social media -->
          <p style="font-size: 40px;">¡Contáctanos!</p>
          <section class="mb-5">
            <!-- Facebook -->
            <a class="btn btn-primary btn-floating m-1" href="https://es-la.facebook.com/" role="button"
              ><i class="fab fa-facebook-f"></i
            >Facebook</a>
      
            
      
            <!-- Instagram -->
            <a class="btn btn-danger btn-floating m-1" href="https://www.instagram.com/cumulo.rosario/" role="button"
              ><i class="fab fa-instagram"></i
            >Instagram</a>
      
            <!-- Whatsapp -->
            <a class="btn btn-success btn-floating m-1" href="https://walink.co/ffbd65" role="button"
              >Whatsapp</a>
      
           
          </section>
          <!-- Section: Social media -->
        </div>
        <!-- Grid container -->
      
        <!-- Copyright -->
        <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
          © 2022 Cumulo Ingeniería, todos los derechos reservados.
        </div>
        <!-- Copyright -->
      </footer>

  </body>
</html>
