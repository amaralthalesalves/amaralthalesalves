<style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body{
            background-color: #242424;
            font-size: 1rem;
            font-family: Arial, Helvetica, sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .red-color {
            color: #f07178;
        }
        .purple-color{
            color: #c792ea;
        }
        .white-color{
            color: #eeffff;
        }
        .blue-color{
            color: #82aaff;
        }
        .green-color{
            color: #c3e88d;
        }
        .row {
            margin-left: 1.5rem;
        }
    </style>
</head>
<body>
    <div id="clock-container">
        <div class="row-parent"><span class="purple-color">const</span><span class="red-color"> clock</span><span class="purple-color"> = {</span></div>
            <div class="row"><span class="white-color">hours: </span><span id="hours"></span></div>
            <div class="row"><span class="white-color">minutes: </span><span id="minutes"></span></div>
            <div class="row"><span class="white-color">seconds: </span><span id="seconds"></span></div>
            <div class="row"><span class="white-color">day of week: </span><span id="dayofweek"></span></div>
            <div class="row"><span class="white-color">day: </span><span id="day"></span></div>
            <div class="row"><span class="white-color">month: </span><span id="month"></span></div>
            <div class="row"><span class="white-color">year: </span><span id="year"></span></div>
        <div class="row-parent"><span class="purple-color">}</span></div>
    </div>
