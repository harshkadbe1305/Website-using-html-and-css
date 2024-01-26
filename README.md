# Website-using-html-and-css
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
        integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />

    <style>
        body {

            flex-direction: column;
            height: auto;
            background-color: white;
        }

        .container {
            margin: 0;
            display: flex;
            align-items: first baseline;
            justify-content: center;
            position: relative;
            text-align: center;

        }

        img {
            width: 100vw;
            height: 30vw;
        }

        .text-container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: #f2f1e6;
            text-align: center;
        }

        .header {
            font-size: 4vw;
            /* Adjust font size based on your preference */
            font-weight: bolder;
            white-space: nowrap;
        }

        .tagline {
            font-size: 2vw;
            /* Adjust font size based on your preference */
            white-space: nowrap;
        }

        .section-container {
            --bs-gutter-x: 1.5rem;
            --bs-gutter-y: 0;
            display: flex;
            flex-wrap: wrap;

        }

        .section-container .columns {
            flex: 0 0 auto;
            width: 50%;

        }

        .section-container .columns.image {
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }

        .section-container .columns.content .content-container {
            color: white;
            padding: 40px 50px;
            background-color: rgb(35, 35, 35);

        }

        .section-container .columns.content .content-container h5 {
            font-weight: 700;
            font-size: 25px;
            margin-bottom: 20px;

        }

        .section-container .columns.content .content-container p {
            font-weight: 400;
            font-size: 16px;
            margin-bottom: 20px;
            margin-bottom: 15px;
            text-align: justify;

        }

        footer {
            background-color: rgb(35, 35, 35);
        }

        .footercontainer {
            width: 100%;
            padding-top: 30px;

            padding: auto;
        }

        .socialincons {
            display: flex;
            justify-content: center;
        }

        .socialincons a {
            text-decoration: none;
            padding: 10px;
            background-color: antiquewhite;
            margin: 10px;
            border-radius: 50%;
        }

        .socialincons a i {
            font-size: 2em;
            color: black;
            opacity: 0.9;
        }

        .socialincons a:hover {
            background-color: black;
            transition: 0.3s;
        }

        .socialincons a:hover i {
            color: white;
            transition: 0.3s;
        }

        .footernav {
            margin: 20px 0;
        }

        .footernav ul {
            display: flex;
            justify-content: center;
            list-style: none;


        }

        .footernav ul li a {

            color: white;
            margin: 20px;
            text-decoration: none;
            font-size: 1.3em;
            opacity: 0.7;
            transition: 0.3s;
        }

        .footernav ul li a:hover {
            opacity: 2;
        }

        .footerbottom {
            background-color: black;
            padding: 20px;
            text-align: center;

        }

        .footerbottom p {
            color: white;
        }

        .contact-container {
            background-color: rgb(35, 35, 35);
            height: 70vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .contact-right {
            display: flex;
            flex-direction: column;
            align-items: start;
            gap: 30px;
        }

        .contact-right-title h2 {

            font-weight: 500;
            color: white;
            font-size: 70px;
            margin-bottom: auto;


        }

        .contact-right-title hr {
            border: none;
            width: auto;
            height: 5px;
            background-color: aliceblue;
            border-radius: 20px;
            margin-bottom: 10px;
        }

        .contact-inputs {
            
            width: 250px;
            height: 8px;
            border: none;
            outline: none;
            padding: 20px;
            font-weight: 5000;
            color: rgb(9, 8, 8);
            border-radius: 20px;
        }

        .contact-right textarea {
            height: 150px;
            padding-top: 15px;
            border-radius: 20px;
        }

        .contact-inputs:focus {
            border: 2px solid;
        }
        .contact-right button{
            display: flex;
            align-items: center;
            padding: auto;
            font-size: 20px;
            color: rgb(90, 84, 84);
            gap: 10px;
            border: none;
            border-radius: 25px;
            cursor: pointer;
           
        }


        @media screen and (max-width:767px) {
            .section-container {
                flex-flow: row wrap;
            }

            .section-container .columns.image {
                display: block;
                order: 2;
                width: 100%;
                height: 250px;

            }

            .section-container .columns.content {
                display: block;
                order: 1;
                width: 100%;

            }

            .section-container .columns.content .content-container {
                background-color: #f2f1e6;
                padding: 20px 35px;
                background-color: rgb(35, 35, 35);
            }

            .section-container .columns.content .content-container h5 {
                margin-bottom: 5px;
            }

            .footernav ul {
                flex-direction: column;
                list-style-type: none;
            }

            .footernav ul li {
                width: 100%;
                text-align: center;
                margin: 10px;
            }
           
        }
    </style>

</head>

<body>

    <section>

        <div class="container">
            <img src="sectiononeimg.jpeg" alt="oops...">
            <div class="text-container">
                <div class="header">MEAL ON WHEEL</div>
                <div class="tagline">A taste of home in every bite</div>

            </div>

        </div>
    </section>

    <div class="section-container">
        <div class="columns image" style="background-image:url(sectiontwoimg.jpeg) ;">
            &nbsp;
        </div>

        <div class="columns content">
            <div class="content-container">
                <h2>About Us</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam quo neque dignissimos corrupti
                    pariatur nihil, voluptas unde sed repellat soluta harum repudiandae enim quod blanditiis cum, rerum
                    provident eius deleniti recusandae. Beatae quod perspiciatis voluptatibus necessitatibus minima
                    eligendi, molestias dolor, neque illo magni suscipit qui quo eveniet, temporibus corrupti
                    consectetur.</p>
                <h2>our story</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem ipsa sequi consequatur optio,
                    aliquid cumque eius! Tempore repellat, dolorem nemo debitis voluptatum accusantium ullam iste cum
                    vitae, enim voluptate ipsum?</p>
                <h2>review</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rem corrupti mollitia quaerat quam, vero
                    consectetur magni aspernatur cumque recusandae architecto excepturi iste assumenda atque porro
                    aperiam. Maiores voluptatum et facilis!</p>
            </div>

        </div>


    </div>


    <div class="section-container">


        <div class="columns content">
            <div class="content-container">
                <h2>About Us</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam quo neque dignissimos corrupti
                    pariatur nihil, voluptas unde sed repellat soluta harum repudiandae enim quod blanditiis cum, rerum
                    provident eius deleniti recusandae. Beatae quod perspiciatis voluptatibus necessitatibus minima
                    eligendi, molestias dolor, neque illo magni suscipit qui quo eveniet, temporibus corrupti
                    consectetur.</p>
                <h2>our story</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem ipsa sequi consequatur optio,
                    aliquid cumque eius! Tempore repellat, dolorem nemo debitis voluptatum accusantium ullam iste cum
                    vitae, enim voluptate ipsum?</p>
                <h2>review</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rem corrupti mollitia quaerat quam, vero
                    consectetur magni aspernatur cumque recusandae architecto excepturi iste assumenda atque porro
                    aperiam. Maiores voluptatum et facilis!</p>
            </div>


        </div>
        <div class="columns image" style="background-image:url(sectionthreeimg.jpeg) ;">
            &nbsp;
        </div>


    </div>


    </div>

    <div class="section-container">
        <div class="columns image">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3666.1705350494703!2d77.43356510000001!3d23.236880600000003!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x397c4265d835c0cf%3A0xa603ff3ac0cc3739!2sVijay%20Stambh!5e0!3m2!1sen!2sin!4v1705754650899!5m2!1sen!2sin"
                width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"></iframe>

        </div>

        <div class="columns content">
            <div class="contact-container">
                <form action="" class="contact-right">
                    <div class="contact-right-title">
                        <h2>Contact us</h2>
                        <hr>

                    </div>
                    <input type="text" name="name" placeholder="Your Name" class="contact-inputs" required />
                    <input type="email" name="email" placeholder="Your Email" class="contact-inputs" required />
                    <input type="message" name="Your message" placeholder="Your message" class="contact-inputs"
                        required />
                    <button type="submit">Submit</button>

                </form>


            </div>

        </div>


    </div>
    <!-- 3 -->
    <footer>


        <div class="footercontainer">
            <div class="socialincons">
                <a href=""> <i class="fa-brands fa-facebook"></i></a>
                <a href=""> <i class="fa-brands fa-instagram"></i></a>
                <a href=""> <i class="fa-brands fa-twitter"></i></a>
                <a href=""> <i class="fa-brands fa-google-plus"></i></a>
                <a href=""> <i class="fa-brands fa-youtube"></i></a>
            </div>


            <div class="footernav">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#home">About</a></li>
                    <li><a href="#home">NEW</a></li>
                    <li><a href="#home">Join us</a></li>
                    <li><a href="#home">Contact</a></li>

                </ul>
            </div>


        </div>
        <div class="footerbottom">
            <p>&copy; 2023 Meal on Wheel. All rights reserved. MADE BY HARSH</p>
        </div>



    </footer>




</body>

</html>
