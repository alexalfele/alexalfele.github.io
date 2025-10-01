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
        }

        body {
            font-family: 'Times New Roman', serif; /* Body text font */
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
            font-family: Calibri, sans-serif; /* Heading font */
            color: var(--color-secondary-orange);
            text-transform: uppercase;
        }

        header h1 {
            font-size: 3em;
            color: var(--color-text-light); /* Keep primary heading light for contrast */
        }

        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }

        .menu-item {
            margin-bottom: 30px;
            padding: 15px;
            border-left: 5px solid var(--color-secondary-orange);
            background-color: #fffaf0; /* Light cream background for menu sections */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
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
    </style>
</head>
<body>

    <header>
        <h1>Khaana's BBQ Menu</h1>
        <h3>The Perfect Pair: Ribs & Mac</h3>
    </header>

    <div class="container">

        <p>
            Welcome to Khaana's kitchen! Our BBQ offerings are prepared daily using the finest ingredients and tradtional smoking techniques.
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
                This is a creamy, cheesy, delicious work of art. Made with five different kinds of cheese, butter, and a hint of smoked paprika, it's baked until the top is golden-brown and bubbling. This dish is the ultimate complement to our rich ribs.
            </p>
            <ol>
                <li>Freshly cooked elbow macaroni</li>
                <li>House-made roux and five-cheese blend</li>
                <li>Topped with breadcrumbs</li>
                <li>Baked to perfection</li>
            </ol>
        </div>

        <h3>Order and Inquiry</h3>
        <p>
            Ready to experience the best BBQ in town? <a href="mailto:orders@khaana.com?subject=BBQ%20Order%20Inquiry" style="color: var(--color-secondary-orange);">Contact us to place an order</a> or discuss catering options.
        </p>

    </div>

</body>
</html>
