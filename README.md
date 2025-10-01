<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khaana - BBQ Menu</title>
    <style>
        /* --- Color Scheme and Font Definitions --- */
        :root {
            /* Brown and Orange Color Scheme */
            --color-primary-brown: #654321; /* Rich Brown */
            --color-secondary-orange: #FF8C00; /* Dark Orange */
            --color-text-light: #f4f4f4;
            --color-text-dark: #333;
            --color-highlight-green: #006400; /* New Color 1 (Green) */
        }

        body {
            font-family: 'Times New Roman', serif; /* Font Style 1 (Body text) */
            background-color: var(--color-text-light);
            color: var(--color-text-dark);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background-color: var(--color-primary-brown);
            color: var(--color-text-light);
            padding: 25px 0;
            text-align: center;
        }

        h1, h2, h3 {
            font-family: Calibri, sans-serif; /* Font Style 2 (Heading) */
            color: var(--color-secondary-orange); /* Color 2 */
            text-transform: uppercase;
        }

        header h1 {
            font-size: 3em;
            color: var(--color-text-light);
        }

        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }

        /* Font Size 1 */
        .body-text-small {
            font-size: 1.0em;
        }

        /* Font Size 2 */
        .body-text-large {
            font-size: 1.2em;
            font-weight: bold;
            color: var(--color-highlight-green); /* Color 1 */
        }

        .menu-item {
            margin-bottom: 30px;
            padding: 15px;
            border-left: 5px solid var(--color-secondary-orange);
            background-color: #fffaf0; /* Light cream background for menu sections */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: auto; /* To contain floated image */
        }

        .menu-item h2 {
            margin-top: 0;
            border-bottom: 1px dashed var(--color-primary-brown);
            padding-bottom: 5px;
        }

        .price {
            float: right;
            font-weight: bold;
            color: var(--color-primary-brown);
            font-size: 1.5em;
        }

        /* Formatting Requirements CSS */
        .underline {
            text-decoration: underline;
        }
        .italics {
            font-style: italic;
        }
        .bold {
            font-weight: bold;
        }

        /* Styling for the image */
        .food-image {
            float: left;
            margin-right: 20px;
            border: 3px solid var(--color-primary-brown);
            padding: 5px;
            width: 200px; /* Set a fixed width */
            height: auto;
        }

        /* Styling for the download link */
        .download-btn {
            display: inline-block;
            background-color: var(--color-highlight-green); /* Color 1 */
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 4px;
            margin: 10px 0;
        }

        /* Footer styling for the date */
        footer {
            clear: both;
            text-align: center;
            padding: 15px;
            background-color: var(--color-primary-brown);
            color: var(--color-text-light);
            border-top: 1px solid #ccc;
            margin-top: 40px;
            font-size: 0.85em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Khaana's BBQ Menu</h1>
        <h3>The Perfect Pair: Ribs & Mac</h3>
    </header>

    <div class="container">

        <img src="https://static.vecteezy.com/system/resources/previews/059/577/488/non_2x/delicious-barbecue-ribs-served-with-cornbread-baked-beans-and-coleslaw-create-mouthwatering-free-photo.jpeg" alt="Plate of BBQ Ribs and Macaroni and Cheese" class="food-image">

        <p class="body-text-small">
            Welcome to Khaana's kitchen! Our BBQ offerings are prepared daily using the finest ingredients and <span class="italics">traditional smoking techniques</span>. We guarantee a meal you won't forget.
        </p>
        
        <p class="body-text-large">
            <span class="underline">This week's special:</span> <span class="bold">Get a Full Rack and a Large Mac & Cheese for only $30.00!</span>
        </p>

        <div class="menu-item">
            <span class="price">$24.99</span>
            <h2>Slow-Smoked BBQ Pork Ribs</h2>
            <p>
                Our signature ribs are dry-rubbed with a secret blend of spices, then smoked low and slow over hickory for over 8 hours. They're fall-off-the-bone tender and coated with your choice of our tangy Carolina-style or sweet, smoky Kansas City sauce.
            </p>
            <ul>
                <li>Full Rack (feeds 3-4)</li>
                <li>Half Rack (feeds 1-2)</li>
                <li>Served with cornbread and coleslaw.</li>
            </ul>
        </div>

        <div class="menu-item">
            <span class="price">$8.99</span>
            <h2>Khaana's Signature Mac and Cheese</h2>
            <p>
                This is a creamy, cheesy, delicious work of art. Made with <span class="bold">five different kinds of cheese</span>, butter, and a hint of smoked paprika, it's baked until the top is golden-brown and bubbling. This dish is the <span class="italics">ultimate complement</span> to our rich ribs.
            </p>
            <ol>
                <li>Freshly cooked elbow macaroni</li>
                <li>House-made roux and five-cheese blend</li>
                <li>Topped with breadcrumbs</li>
                <li>Baked to perfection</li>
            </ol>
        </div>

        <hr>

        <h3>More Information and Downloads</h3>

        <p class="body-text-small">
            Learn more about the art of slow-smoking meat from the experts: <a href="https://amazingribs.com/more-barbecue-and-grilling-science/" target="_blank" rel="noopener noreferrer" style="color: var(--color-highlight-green); text-decoration: underline;">The Science of BBQ</a>.
        </p>

        <p class="bold">
            Download our full catering menu PDF: 
            <a href="Khaana_Catering_Menu.pdf" download="Khaana_Catering_Menu.pdf" class="download-btn">
                Download Menu
            </a>
        </p>

        <p class="body-text-small">
            For direct inquiries or questions about our ingredients, please <a href="mailto:chef@khaana.com?subject=BBQ%20Menu%20Question" style="color: var(--color-secondary-orange);">email the Head Chef</a>.
        </p>

    </div>

    <footer>
        <p>Date Last Modified: <span id="lastModifiedDate"></span></p>

        <script>
            // JavaScript to get the last modified date of the document
            document.getElementById("lastModifiedDate").textContent = document.lastModified;
        </script>
    </footer>

</body>
</html>
