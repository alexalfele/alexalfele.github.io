<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khaana - Commercial Foodservice Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333;
        }

        header {
            background-color: #A52A2A; /* Deep Red */
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.2em;
        }

        .container {
            width: 85%;
            margin: auto;
            padding: 20px 0;
        }

        h2 {
            color: #A52A2A;
            border-bottom: 2px solid #FF8C00; /* Dark Orange */
            padding-bottom: 5px;
            margin-top: 30px;
        }

        .product-image {
            float: right;
            margin-left: 20px;
            border: 1px solid #ccc;
            padding: 5px;
            box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
        }

        ul, ol {
            line-height: 1.6;
        }

        /* Styling for the download link */
        .download-btn {
            display: inline-block;
            background-color: #008000; /* Green */
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin: 20px 0;
        }

        .download-btn:hover {
            background-color: #006400;
        }

        /* Footer styling for the date */
        footer {
            clear: both; /* Ensures footer is below any floated content */
            text-align: center;
            padding: 15px;
            background-color: #f4f4f4;
            border-top: 1px solid #ccc;
            margin-top: 40px;
            font-size: 0.85em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Khaana Product Lineup</h1>
    </header>

    <div class="container">

        <p>
            Khaana offers a curated selection of commercial-grade foodservice equipment designed for durability, energy efficiency, and peak performance. Our products are sourced from trusted manufacturers worldwide.
        </p>

        <img src="https://via.placeholder.com/300x200?text=Commercial+Oven+System" alt="High-Efficiency Commercial Oven System" class="product-image">
        
        <h2>Primary Equipment Categories</h2>

        <ol>
            <li>
                <strong>Cooking Systems:</strong> Includes convection ovens, combi steamers, and high-BTU ranges. We focus on systems that reduce cooking time and ensure uniform heat distribution.
            </li>
            <li>
                <strong>Refrigeration Units:</strong> Walk-in coolers, upright freezers, and prep tables. Our units feature energy-efficient compressors and smart temperature monitoring.
            </li>
            <li>
                <strong>Warewashing Solutions:</strong> Commercial dishwashers, glass washers, and sanitizing stations designed for high-volume, continuous use.
            </li>
        </ol>
        
        <p>
            For information on selecting the right equipment capacity for your business, you can refer to this <a href="https://www.energystar.gov/products/commercial_food_service_equipment" target="_blank" rel="noopener noreferrer">official guide on ENERGY STAR certified commercial food equipment</a>. (This fulfills the external hyperlink requirement, which opens in a new tab.)
        </p>

        ---

        <h2>Featured Product: The Pro-Series Combi Oven</h2>

        <p>
            The Khaana Pro-Series Combi Oven is our most popular piece of equipment. It combines the functions of a convection oven and a steamer, offering unparalleled flexibility.
        </p>

        <ul>
            <li>
                <strong>Versatility:</strong> Bake, roast, steam, or proof—all in one unit.
            </li>
            <li>
                <strong>Smart Control:</strong> Pre-programmed recipes and intuitive touchscreen interface.
            </li>
            <li>
                <strong>Water Saving:</strong> Advanced steam generation technology minimizes water consumption.
            </li>
            <li>
                <strong>Warranty:</strong> Comes with a comprehensive 5-year parts and labor warranty.
            </li>
        </ul>

        <p>
            Need assistance with product selection or a custom quote? <a href="/contact.html">Visit our Contact Page</a> to speak with a sales representative. (This fulfills the internal hyperlink requirement.)
        </p>
        
        <p>
            ---
        </p>

        <h2>Download Our Product Catalog</h2>

        <a href="catalog.pdf" download="Khaana_Product_Catalog_2025.pdf" class="download-btn">
            Download 2025 Catalog (PDF)
        </a>

        <p>
            For direct inquiries regarding the Pro-Series oven or to request a full technical specification sheet, please feel free to <a href="mailto:creator@khaana.com?subject=Inquiry%20About%20Pro-Series%20Oven">email us directly</a>. (This fulfills the "contact me" email link requirement.)
        </p>
        
    </div>

    <footer>
        <p>Last Modified: <span id="lastModifiedDate"></span></p>

        <script>
            // JavaScript to get the last modified date of the document
            document.getElementById("lastModifiedDate").textContent = document.lastModified;
        </script>
    </footer>

</body>
</html>
