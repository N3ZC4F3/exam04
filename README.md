<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Web Aruma</title>
    <!--Iconos Font Awesome-->
    <i class="fa-solid fa-shop"></i>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    <!--Archivos CSS-->
    <link rel="stylesheet" href="css/Style.CSS">

</head>

<body>
    <!--Header empieza-->
    <header class="header">
        <a href="#" class="logo">
            <img src="Imagen/Logo.png">
        </a>
        <nav class="navbar">
            <a href="#Home">Inicio</a>
            <a href="#about">Acerca De</a>
            <a href="#Menu">Menu</a>
           <!-- <a href="#products">Productos</a>-->
            <a href="#contact">Contáctanos</a>
        </nav>
        <div class="icons">
            <div class="fas fa-search" id="search-btn"></div>
            <div class="fas fa-shopping-cart" id="car-btn"></div>
            <div class="fa duotone fa-bars" id="menu-btn"></div>    
        </div>
    </header>
    <!--Header termina-->
    
    <!--Home inicia-->
    <section class="Home">
        <div class="content">
            <h3>El Estilo Que Tu Deseas</h3>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit, beatae natus ducimus, nihil quas saepe quam molestiae sapiente officia, assumenda enim libero corrupti rem fugit inventore perspiciatis modi vero architecto!</p>
            <a href="#" class="btn">Obten tu prenda ahora</a>
        </div>
    </section>
    <!--Home termina-->

    <!--Acerca De inicia-->
    <section class="about" id="about">
        <h1 class="heading"> Acerca de <span>Nosotros</span> </h1>

        <div class="row">
            <div class="Imagen">
                <img src="Imagen/Acerca de.png" alt="">
            </div>

            <div class="content">
                <h3>¿En qué nos inspiramos?</h3>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quia soluta tenetur cum, saepe aut ipsum placeat illum quaerat, ad nisi eius vero cupiditate perferendis dolore suscipit quae, magnam quis impedit.</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Repellat numquam ipsum nam vitae possimus dolorem voluptates, ab beatae, asperiores, voluptatem facilis! Quaerat eligendi quam saepe quae a optio corrupti! Iste.</p>
                <a href="#" class="btn"> Saber más</a>
            </div>

            
        </div>
    </section>
    <!--Acerca De termina-->

    <!--Menu inicia-->
    <section class="Menu" id="Menu">
        <h1 class="heading">Nuestro <span>Catálogo</span> </h1>
        <div class="box-container">

            <div class="box">
                <img src="Imagen/Vestidos.jpg" alt="">
                <h3>Vestidos</h3>
                <div class="Precio">$80.99 - <span>120.99</span> </div>
                <a href="#" class="btn">¡Me lo llevo!</a>
            </div>
            <div class="box">
                <img src="Imagen/Pantalones.webp" alt="">
                <h3>Pantalones</h3>
                <div class="Precio">$30.99 - <span>70.99</span> </div>
                <a href="#" class="btn">¡Me lo llevo!</a>
            </div>
            <div class="box">
                <img src="Imagen/Sobretodo.jpg" alt="">
                <h3>Sobretodo</h3>
                <div class="Precio">$50.99 - <span>90.99</span> </div>
                <a href="#" class="btn">¡Me lo llevo!</a>
            </div>
            <div class="box">
                <img src="Imagen/Trajes de baño.jpg" alt="">
                <h3>Trajes de Baño</h3>
                <div class="Precio">$20.99 - <span>40.99</span> </div>
                <a href="#" class="btn">¡Me lo llevo!</a>
            </div>
            <div class="box">
                <img src="Imagen/Niñas.jpg" alt="">
                <h3>Para Niñas</h3>
                <div class="Precio">$80.99 - <span>120.99</span> </div>
                <a href="#" class="btn">¡Me lo llevo!</a>
            </div>
            <div class="box">
                <img src="Imagen/Niños.jpg" alt="">
                <h3>Para Niños</h3>
                <div class="Precio">$80.99 - <span>120.99</span> </div>
                <a href="#" class="btn">¡Me lo llevo!</a>
            </div>
        </div>
    </section>
    <!--Menu termina-->

    <!--Products inicia
<section class="products" id="Productos">
    <h1 class="heading"> Nuestros <span>Diseños</span> </h1>

    <div class="box-container">

    </div>
</section>
    Products termina-->

    <!--Contacto inicia-->
    <section class="contact" id="contact">

        <h1 class="heading">Puedes <span>Contactarnos</span> </h1>

        <div class="row">

            <form action="">
                <h3>Envíanos un correo</h3>
                <div class="inputBox">
                    <span class="fas fa-user"></span>
                    <input type="text" placeholder="Nombre">
                </div>
                <div class="inputBox">
                    <span class="fas fa-envelope"></span>
                    <input type="email" placeholder="correo">
                </div>
                <div class="inputBox">
                    <span class="fas fa-phone"></span>
                    <input type="number" placeholder="Teléfono">
                </div>
                <input type="submit" value="contact" class="btn">
            </form>

        </div>

    </section>
    <!--Contacto termina-->

    <!--Blog inicia
    <section class="blog" id="blog">

    </section>
    Blog termina-->

    <!--Pie de pagina inicia-->
    <section class="footer">

        <div class="share">
            <a href="#" class="fab fa-facebook-f"></a>
            <a href="#" class="fab fa-twitter"></a>
            <a href="#" class="fab fa-instagram"></a>
        </div>

        <div class="links">
            <a href="#">Inicio</a>
            <a href="#">Acerca De</a>
            <a href="#">Menu</a>
            <a href="#">Contáctanos</a>
            <!--<a href="#">blog</a>-->
        </div>

        <div class="credit">Creado por <span>Nadgirah Salazar</span> /Especialidad: Informática</div>
    </section>
    <!--Pie de pagina termina-->

</body>

</html>
