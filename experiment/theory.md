<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ring Compression Test</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2 {
            color: #003399;
        }
        .section-title {
            font-size: 20px;
            font-weight: bold;
            color: #0055cc;
            margin-top: 25px;
        }
        table {
            width: 70%;
            border-collapse: collapse;
            margin: 15px 0;
        }
        table, th, td {
            border: 1px solid #444;
        }
        th, td {
            padding: 8px;
            text-align: left;
        }
        .center {
            text-align: center;
        }
    </style>
</head>

<body>

<h1>Ring Compression Test</h1>

<p>
    Ring compression test has been widely used as a test to evaluate the friction condition in metal forming processes.
</p>

<br>
<center>
<iframe width="600" height="400" src="https://www.youtube.com/embed/SIZsIc7U1eM?rel=0" frameborder="0" allowfullscreen></iframe>
</center><br>

<h2 class="section-title">THE PRINCIPLE OF RING TEST</h2>

<p>
    For given conditions of temperature, strain, strain rate and initial specimen geometry of OD:ID:H, 
    the deformation of the internal diameter of the ring may be calculated as a unique function of the interfacial friction coefficient.
</p>

<h2 class="section-title">Geometrical Change and Friction Condition</h2>

<p>
    When a short ring specimen is plastically compressed between two flat parallel platens, the internal diameter increases 
    if interface friction is low, and decreases if friction is high.
</p>
<p>
    By measuring the change in internal diameter, it is possible to evaluate friction conditions using a friction calibration curve.
</p>

<h2 class="section-title">CASE A : RING TEST SIMULATION FOR M = 0.0</h2>

<table>
    <tr><td>Material</td><td>AlZn5.6Mg2.5Cu1.6</td></tr>
    <tr><td>Friction Shear Factor</td><td>m = 0.0</td></tr>
    <tr><td>Dimensions</td><td>OD = 60mm, ID = 30mm, Height = 20mm</td></tr>
    <tr><td>Ring Temperature</td><td>300 °C</td></tr>
    <tr><td>Die Temperature</td><td>250 °C</td></tr>
    <tr><td>% Reduction in Height</td><td>50% (10 mm)</td></tr>
</table>

<h3>Simulation Results</h3>

<table>
    <tr><td>Final ID</td><td>42.0989 mm</td></tr>
    <tr><td>% Decrease in ID</td><td>-40.3297%</td></tr>
    <tr><td>% Reduction in Height</td><td>50%</td></tr>
</table>

<h2 class="section-title">CASE B : RING TEST SIMULATION FOR M = 0.10</h2>

<table>
    <tr><td>Material</td><td>AlZn5.6Mg2.5Cu1.6</td></tr>
    <tr><td>Friction Shear Factor</td><td>m = 0.10</td></tr>
    <tr><td>Dimensions</td><td>OD = 60mm, ID = 30mm, Height = 20mm</td></tr>
    <tr><td>Ring Temperature</td><td>300 °C</td></tr>
    <tr><td>Die Temperature</td><td>250 °C</td></tr>
    <tr><td>% Reduction in Height</td><td>50% (10 mm)</td></tr>
</table>

<h3>Simulation Results</h3>

<table>
    <tr><td>Final ID</td><td>34.5300 mm</td></tr>
    <tr><td>% Decrease in ID</td><td>-15.1000%</td></tr>
    <tr><td>% Reduction in Height</td><td>50%</td></tr>
</table>

<h2 class="section-title">CASE C : RING TEST SIMULATION FOR M = 0.30</h2>

<table>
    <tr><td>Material</td><td>AlZn5.6Mg2.5Cu1.6</td></tr>
    <tr><td>Friction Shear Factor</td><td>m = 0.30</td></tr>
    <tr><td>Dimensions</td><td>OD = 60mm, ID = 30mm, Height = 20mm</td></tr>
    <tr><td>Ring Temperature</td><td>300 °C</td></tr>
    <tr><td>Die Temperature</td><td>250 °C</td></tr>
    <tr><td>% Reduction in Height</td><td>50% (10 mm)</td></tr>
</table>

<h3>Simulation Results</h3>

<table>
    <tr><td>Final ID</td><td>25.8003 mm</td></tr>
    <tr><td>% Decrease in ID</td><td>13.9990%</td></tr>
    <tr><td>% Reduction in Height</td><td>50%</td></tr>
</table>

<h2 class="section-title">CASE D : RING TEST SIMULATION FOR M = 0.40</h2>

<table>
    <tr><td>Material</td><td>AlZn5.6Mg2.5Cu1.6</td></tr>
    <tr><td>Friction Shear Factor</td><td>m = 0.40</td></tr>
    <tr><td>Dimensions</td><td>OD = 60mm, ID = 30mm, Height = 20mm</td></tr>
    <tr><td>Ring Temperature</td><td>300 °C</td></tr>
    <tr><td>Die Temperature</td><td>250 °C</td></tr>
    <tr><td>% Reduction in Height</td><td>50% (10 mm)</td></tr>
</table>

<h3>Simulation Results</h3>

<table>
    <tr><td>Final ID</td><td>22.6611 mm</td></tr>
    <tr><td>% Decrease in ID</td><td>24.4630%</td></tr>
    <tr><td>% Reduction in Height</td><td>50%</td></tr>
</table>

<h2 class="section-title">COMPARISON</h2>

<p>
    A ring test simulation is performed for different friction shear factors using the same material and press setup. 
    The simulation is non-isothermal, meaning heat transfer at the interface is considered.
</p>

<p>
    Results show how temperature and shear friction factor affect metal flow and ring geometry. 
    Compared to isothermal deformation, non-isothermal deformation increases the level of friction.
</p>

</body>
</html>
