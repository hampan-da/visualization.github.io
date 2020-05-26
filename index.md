<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COVID-19 & Stock Prices</title>
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="" />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/noUiSlider/14.0.3/nouislider.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles/style.css">
</head>

<body>
    <div id="title">
        COVID-19 & Stock Prices
        <button id="readMoreBtn">Read More</button>
    </div>

    <!-- Trigger/Open The Modal -->

    <div id="svgMap">
    </div>
    <h2 id="totalCases"></h2>
    <p id="info"></p>

    <!-- noUiSlider -->
    <div id="slide">
        <div class="sliderContainer" id="mySlider"></div>
        <div>
            <p></p>
            <p id="sliderP">
                <span class="left" id="startEvent"></span>
            </p>
        </div>
    </div>

    <div id="container"></div>

    <!-- The Modal itself-->
    <div id="readMoreModal" class="modal">

        <!-- Modal content: Change Lorem Ipsum to your content here -->
        <div class="modal-content">
            <span class="close">&times;</span>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam vel tempore autem doloribus nam velit possimus voluptatibus blanditiis, doloremque aliquid, corporis beatae aliquam fugiat deleniti numquam eaque totam nulla eos.</p>
        </div>

    </div>


    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.js"></script>
    <script src="scripts/utils.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/noUiSlider/14.0.3/nouislider.min.js"></script>
    <script src="https://d3js.org/d3.v3.js"></script>
    <script src="https://d3js.org/d3-geo-projection.v2.min.js"></script>
    <script src="https://d3js.org/topojson.v1.min.js"></script>
    <script src="https://d3js.org/queue.v1.min.js"></script>
    <script src="scripts/script.js"></script>
</body>

</html>