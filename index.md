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

    <!-- open model

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

        <!-- read more content
        <div class="modal-content">
            <span class="close">&times;</span>
            <p>This visualisation shows Covid19 cases from Jan 2020 - April 2020. The stock market time frame is September 2019 - April 2020.</p>
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
