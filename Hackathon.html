<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chart.js Pie Chart</title>
    <!-- Include Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        .chart-container {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            text-align: center;
            position: absolute;
            width: 100%;
            /* Adjust the width if needed */
            top: 0%;
            /* Center vertically */
            left: 50%;
            /* Center horizontally */
            transform: translate(-50%, -50%);
            margin-top: 2%;
        }

        .chart-container2 {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            text-align: center;
            position: absolute;
            width: 100%;
            margin-top: 10%;
        }

        .chart-container3 {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            text-align: center;
            position: absolute;
            width: 100%;
            margin-top: 15%;
        }

        .chart-container4 {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: absolute;
            width: 100%;
            margin-top: -30%;
        }

        h1 {
            margin: 0;
            /* Remove any default margin to center the title */
        }

        #myPieChart {
            max-width: 1000px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            display: flex;
            justify-content: center;
        }

        #myPieChart2 {
            max-width: 1000px;
            margin-top: 5%;
            position: absolute;
            top: 140%;
            left: 50%;
            transform: translate(-50%, -50%);
            display: flex;
            justify-content: center;
        }

        #myPieChart3 {
            max-width: 1000px;
            margin-top: 54%;
            /* Adjust this margin as needed */
            position: absolute;
            top: 140%;
            left: 50%;
            transform: translate(-50%, -50%);
            display: flex;
            justify-content: center;
        }

        #myPieChart4 {
            max-width: 1000px;
            margin-top: 10%;
            /* Adjust this margin as needed */
            position: absolute;
            top: 300%;
            /* Adjust this top value as needed */
            left: 50%;
            transform: translate(-50%, -50%);
            display: flex;
            justify-content: center;
        }

        .page1 {
            height: 80vh;
        }

        .page2 {
            height: 90vh;
        }

        .page3 {
            height: 150vh;
        }

        .page4 {
            height: 90vh;
        }
    </style>
</head>

<body>
    <div class="page1">
        <div class="chart-container">
            <h1 class="chart-title">Temporary Resident Count- Country Citizenship</h1>
        </div>
        <canvas id="myPieChart" width="1000" height="800"></canvas>
    </div>

    <br>

    <div class="page2">
        <div class="chart-container2">
            <h1>Permanent Resident Count - Country Citizenship</h1>
        </div>
        <canvas id="myPieChart2" width="800" height="800"></canvas>
    </div>

    <br>

    <div class="page3">
        <div class="chart-container3">
            <h1>Permanent Resident Count - Region of Citizenship</h1>
        </div>
        <canvas id="myPieChart3" width="1000" height="1000"></canvas>
    </div>
    <br>
    <div class="page4">
        <div class="chart-container4">
            <h1>Temporary Resident Count - Region of Citizenship</h1>
        </div>
        <canvas id="myPieChart4" width="1000" height="800"></canvas>
    </div>

    <script>
        // CSV data
        var csvData = `Uniqueid,CountryName,Count,Percent,BaseCount,BasePercent,PercentPenetration,Index
        NC23Q1TRCIND,India,25397,4.14,302119,2.00,8.41,207
        NC23Q1TRCCHN,China,5079,0.83,45177,0.30,11.24,276
        NC23Q1TRCPHL,Philippines,1019,0.17,28681,0.19,3.55,87
        NC23Q1TRCNGA,Nigeria,1300,0.21,13944,0.09,9.32,229
        NC23Q1TRCUSA,USA,864,0.14,11632,0.08,7.43,182
        NC23Q1TRCPAK,Pakistan,0,0.00,3848,0.03,0.00,0
        NC23Q1TRCFRA,France,0,0.00,2885,0.02,0.00,0
        NC23Q1TRCIRN,Iran,1865,0.30,11762,0.08,15.86,389
        NC23Q1TRCBRA,Brazil,898,0.15,9053,0.06,9.92,244
        NC23Q1TRCKOR,Korea, Republic of,1125,0.18,8671,0.06,12.97,319
        NC23Q1TRCGBR,UK and Overseas Territories,0,0.00,4055,0.03,0.00,0
        NC23Q1TRCMEX,Mexico,280,0.05,23661,0.16,1.18,29
        NC23Q1TRCJAM,Jamaica,0,0.00,11004,0.07,0.00,0
        NC23Q1TRCCOL,Colombia,776,0.13,7831,0.05,9.91,244
        NC23Q1TRCVIE,Vietnam,402,0.07,8122,0.05,4.95,122
        NC23Q1TRCBAN,Bangladesh,821,0.13,5528,0.04,14.85,365
        NC23Q1TRCMOR,Morocco,64,0.01,1714,0.01,3.73,91
        NC23Q1TRCALG,Algeria,27,0.00,731,0.01,3.69,92
        NC23Q1TRCUKR,Ukraine,593,0.10,42980,0.28,1.38,34
        NC23Q1TRCHKG,Hong Kong,675,0.11,7055,0.05,9.57,235
        NC23Q1TRCOTH,All other countries,6651,1.08,77820,0.52,8.55,210`;

        // Split CSV data into rows
        var rows = csvData.split('\n');

        // Initialize arrays for chart data
        var labels = [];
        var data = [];
        var backgroundColors = [];

        // Start from the second row (index 1) to skip the header
        for (var i = 1; i < rows.length; i++) {
            var row = rows[i].split(',');
            var countryName = row[1];
            var count = parseInt(row[2].replace(/,/g, '')); // Remove commas and parse as integer
            labels.push(countryName);
            data.push(count);
            // Generate random background color for each segment
            backgroundColors.push('#' + Math.floor(Math.random() * 16777215).toString(16));
        }

        // Create a Pie Chart
        var ctx = document.getElementById('myPieChart').getContext('2d');
        var myPieChart = new Chart(ctx, {
            type: 'pie',
            data: {
                labels: labels,
                datasets: [{
                    data: data,
                    backgroundColor: backgroundColors,
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: true,
                        position: 'bottom',
                    }
                }
            }
        });

        // new pie chart 
        // CSV data
        var csvData2 = `Uniqueid,CountryName,Count,%,BaseCount,Base %,% Pen,Index
            NC23Q1PRCIND,India,3011,0.49,64608,0.43,4.66,115
            NC23Q1PRCCHN,China,515,0.08,13593,0.09,3.79,93
            NC23Q1PRCPHL,Philippines,86,0.01,6771,0.04,1.27,31
            NC23Q1PRCNGA,Nigeria,145,0.02,9476,0.06,1.53,38
            NC23Q1PRCUSA,USA,198,0.03,4843,0.03,4.09,101
            NC23Q1PRCPAK,Pakistan,304,0.05,7451,0.05,4.08,100
            NC23Q1PRCFRA,France,26,0.00,1057,0.01,2.46,60
            NC23Q1PRCIRN,Iran,185,0.03,4720,0.03,3.92,96
            NC23Q1PRCBRA,Brazil,87,0.01,2986,0.02,2.91,72
            NC23Q1PRCKOR,Korea, Republic of,59,0.01,1702,0.01,3.47,85
            NC23Q1PRCGBR,UK and Overseas Territories,83,0.01,1617,0.01,5.13,126
            NC23Q1PRCMEX,Mexico,67,0.01,1962,0.01,3.41,84
            NC23Q1PRCJAM,Jamaica,86,0.01,3150,0.02,2.73,67
            NC23Q1PRCCOL,Colombia,119,0.02,1631,0.01,7.30,180
            NC23Q1PRCVIE,Vietnam,168,0.03,2369,0.02,7.09,175
            NC23Q1PRCBAN,Bangladesh,45,0.01,1836,0.01,2.45,60
            NC23Q1PRCMOR,Morocco,60,0.01,1851,0.01,3.24,80
            NC23Q1PRCALG,Algeria,44,0.01,1417,0.01,3.11,77
            NC23Q1PRCUKR,Ukraine,35,0.01,1545,0.01,2.27,56
            NC23Q1PRCHKG,Hong Kong,36,0.01,1721,0.01,2.09,52
            NC23Q1PRCOTH,All other countries,2851,0.46,58842,0.39,4.85,119`;

        // Split CSV data into rows
        var rows2 = csvData2.split('\n');

        // Initialize arrays for chart data
        var labels2 = [];
        var data2 = [];
        var backgroundColors2 = [];

        // Start from the second row (index 1) to skip the header
        for (var i = 1; i < rows2.length; i++) {
            var row2 = rows2[i].split(',');
            var countryName2 = row2[1];
            var count2 = parseInt(row2[2].replace(/,/g, '')); // Remove commas and parse as integer
            labels2.push(countryName2);
            data2.push(count2);
            // Generate random background color for each segment
            backgroundColors2.push('#' + Math.floor(Math.random() * 16777215).toString(16));
        }

        // Create a Pie Chart for the second chart
        var ctx2 = document.getElementById('myPieChart2').getContext('2d');
        var myPieChart2 = new Chart(ctx2, {
            type: 'pie',
            data: {
                labels: labels2,
                datasets: [{
                    data: data2,
                    backgroundColor: backgroundColors2,
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: true,
                        position: 'bottom',
                    }
                }
            }
        });

        var csvData3 = `NC23Q1PRRAMS,Americas,754,0.12,20179,0.13,3.74,92
                NC23Q1PRRNAM,North America,198,0.03,4843,0.03,4.09,101
                NC23Q1PRRCAM,Central America,138,0.02,2836,0.02,4.87,120
                NC23Q1PRRCBB,Caribbean and Bermuda,158,0.03,5885,0.04,2.68,66
                NC23Q1PRRSAM,South America,260,0.04,6615,0.04,3.93,97
                NC23Q1PRREUR,Europe,403,0.07,9745,0.07,4.14,102
                NC23Q1PRRNWE,Northern & Western Europe,157,0.03,3705,0.03,4.24,104
                NC23Q1PRREEU,Eastern Europe,140,0.02,3584,0.02,3.91,96
                NC23Q1PRRSEU,Southern Europe,106,0.02,2456,0.02,4.32,106
                NC23Q1PRRAFR,Africa,1199,0.20,31263,0.21,3.84,94
                NC23Q1PRREAF,Eastern Africa,630,0.10,8877,0.06,7.10,174
                NC23Q1PRRNAF,Northern Africa,258,0.04,6261,0.04,4.12,101
                NC23Q1PRROAF,Other Africa,311,0.05,16125,0.11,1.93,47
                NC23Q1PRRASA,Asia,5845,0.95,133537,0.89,4.38,108
                NC23Q1PRRWCA,West Central Asia and the Middle East,1460,0.24,29308,0.19,4.98,122
                NC23Q1PRREAS,Eastern Asia,623,0.10,17653,0.12,3.53,87
                NC23Q1PRRSEA,Southeast Asia,300,0.05,9941,0.07,3.02,74
                NC23Q1PRRSAS,Southern Asia,3462,0.56,76635,0.51,4.52,111
                NC23Q1PRROCE,Oceania and Other,9,0.00,424,0.00,2.12,54`
        var rows3 = csvData3.split('\n');

        // Initialize arrays for chart data
        var labels3 = [];
        var data3 = [];
        var backgroundColors3 = [];

        // Start from the second row (index 1) to skip the header
        for (var i = 1; i < rows3.length; i++) {
            var row3 = rows3[i].split(',');
            var countryName3 = row3[1];
            var count3 = parseInt(row3[2].replace(/,/g, '')); // Remove commas and parse as integer
            labels3.push(countryName3);
            data3.push(count3);
            // Generate random background color for each segment
            backgroundColors3.push('#' + Math.floor(Math.random() * 16777215).toString(16));
        }

        // Create a Pie Chart for the second chart
        var ctx3 = document.getElementById('myPieChart3').getContext('2d');
        var myPieChart3 = new Chart(ctx3, {
            type: 'bar',
            data: {
                labels: labels3,
                datasets: [{
                    data: data3,
                    backgroundColor: backgroundColors3,
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: false,
                        position: 'bottom',
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true, // Start the Y-axis at zero
                        title: {
                            display: true,
                            text: 'Count', // Y-axis title
                            fontSize: 32, // Increase font size
                        },
                        ticks: {
                            fontSize: 32, // Increase tick font size
                        },
                    },
                    x: {
                        title: {
                            display: true,
                            text: 'Region', // X-axis title
                            fontSize: 32, // Increase font size
                        },
                        ticks: {
                            fontSize: 32, // Increase tick font size
                        },
                    },
                },
            }
        });

        var csvData4 = `NC23Q1TRRAMS,Americas,4104,0.67,78335,0.52,5.24,129
        NC23Q1TRRNAM,North America,864,0.14,11632,0.08,7.43,182
        NC23Q1TRRCAM,Central America,348,0.06,27971,0.18,1.24,31
        NC23Q1TRRCBB,Caribbean and Bermuda,267,0.04,15506,0.10,1.72,42
        NC23Q1TRRSAM,South America,2625,0.43,23226,0.15,11.30,278
        NC23Q1TRREUR,Europe,1733,0.28,64478,0.43,2.69,66
        NC23Q1TRRNWE,Northern & Western Europe,106,0.02,10922,0.07,0.97,24
        NC23Q1TRREEU,Eastern Europe,593,0.10,46890,0.31,1.26,31
        NC23Q1TRRSEU,Southern Europe,1034,0.17,6666,0.04,15.51,381
        NC23Q1TRRAFR,Africa,2471,0.40,30831,0.20,8.01,197
        NC23Q1TRREAF,Eastern Africa,0,0.00,3925,0.03,0.00,0
        NC23Q1TRRNAF,Northern Africa,196,0.03,4709,0.03,4.16,102
        NC23Q1TRROAF,Other Africa,2275,0.37,22197,0.15,10.25,252
        NC23Q1TRRASA,Asia,39528,6.44,453517,3.01,8.72,214
        NC23Q1TRRWCA,West Central Asia and the Middle East,1865,0.30,22629,0.15,8.24,203
        NC23Q1TRREAS,Eastern Asia,8036,1.31,66805,0.44,12.03,296
        NC23Q1TRRSEA,Southeast Asia,1570,0.26,40696,0.27,3.86,95
        NC23Q1TRRSAS,Southern Asia,20996,3.43,292772,1.94,7.17,176
        NC23Q1TRROCE,Oceania and Other,503,0.08,7069,0.05,7.11,175`;
        var rows4 = csvData4.split('\n');

        // Initialize arrays for chart data
        var labels4 = [];
        var data4 = [];
        var backgroundColors4 = [];

        // Start from the second row (index 1) to skip the header
        for (var i = 1; i < rows4.length; i++) {
            var row4 = rows4[i].split(',');
            var countryName4 = row4[1];
            var count4 = parseInt(row4[2].replace(/,/g, '')); // Remove commas and parse as integer
            labels4.push(countryName4);
            data4.push(count4);
            // Generate random background color for each segment
            backgroundColors4.push('#' + Math.floor(Math.random() * 16777215).toString(16));
        }

        // Create a Pie Chart for the second chart
        var ctx4 = document.getElementById('myPieChart4').getContext('2d');
        var myPieChart4 = new Chart(ctx4, {
            type: 'bar',
            data: {
                labels: labels4,
                datasets: [{
                    data: data4,
                    backgroundColor: backgroundColors4,
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: false,
                        position: 'bottom',
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true, // Start the Y-axis at zero
                        title: {
                            display: true,
                            text: 'Count', // Y-axis title
                            fontSize: 32, // Increase font size
                        },
                        ticks: {
                            fontSize: 32, // Increase tick font size
                        },
                    },
                    x: {
                        title: {
                            display: true,
                            text: 'Region', // X-axis title
                            fontSize: 32, // Increase font size
                        },
                        ticks: {
                            fontSize: 32, // Increase tick font size
                        },
                    },
                },
            }
        });
    </script>
</body>

</html>
