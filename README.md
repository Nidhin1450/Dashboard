<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StockVerse Console Dashboard</title>
    <style>
        body {
            font-family: 'Courier New', monospace;
            background-color: #1e1e1e;
            color: #33FF00;
            margin: 0;
            padding: 0;
            overflow: hidden;
            height: 100vh;
        }

        .console-container {
            padding: 20px;
            overflow-y: auto;
            height: 100%;
            background-color: #121212;
            border: 1px solid #33FF00;
        }

        h1 {
            text-align: center;
            font-size: 36px;
            margin-bottom: 40px;
            color: #33FF00;
        }

        .link-list {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        .link-list li {
            font-size: 18px;
            margin: 10px 0;
            transition: transform 0.3s ease, color 0.3s ease;
        }

        .link-list li a {
            color: #33FF00;
            text-decoration: none;
            cursor: pointer;
        }

        .link-list li:hover {
            color: #00FF00;
            transform: scale(1.1);
        }

        .link-list li a:hover {
            color: #FF9900;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #33FF00;
        }
    </style>
</head>
<body>

    <div class="console-container">
        <h1>StockVerse Console Dashboard</h1>
        <ul class="link-list">
            <li><a href="https://horn-jonquil-8bf.notion.site/22fe8ac34a8f80a38145df9d1703555c?source=copy_link" target="_blank">Notion 1st</a></li>
            <li><a href="https://www.bseindia.com" target="_blank">BSE India</a></li>
            <li><a href="https://www.tradingview.com" target="_blank">TradingView</a></li>
            <li><a href="https://kite.zerodha.com" target="_blank">Zerodha Kite</a></li>
            <li><a href="https://www.moneycontrol.com" target="_blank">MoneyControl</a></li>
            <li><a href="https://www.etmarkets.com" target="_blank">ET Markets</a></li>
            <li><a href="https://www.bloomberg.com" target="_blank">Bloomberg</a></li>
            <li><a href="https://www.reuters.com" target="_blank">Reuters</a></li>
            <li><a href="https://www.finanzen.net" target="_blank">Finanzen.net</a></li>
            <li><a href="https://www.cnbc.com" target="_blank">CNBC</a></li>
            <li><a href="https://www.investing.com" target="_blank">Investing.com</a></li>
            <li><a href="https://www.stockcharts.com" target="_blank">StockCharts</a></li>
            <li><a href="https://www.morningstar.com" target="_blank">MorningStar</a></li>
            <li><a href="https://www.screener.in" target="_blank">Screener.in</a></li>
            <li><a href="https://www.nifty50.com" target="_blank">Nifty50</a></li>
            <li><a href="https://www.financialexpress.com" target="_blank">Financial Express</a></li>
            <li><a href="https://www.sensex.com" target="_blank">Sensex</a></li>
            <li><a href="https://www.indiainfoline.com" target="_blank">India Infoline</a></li>
            <li><a href="https://www.sharekhan.com" target="_blank">Sharekhan</a></li>
            <li><a href="https://www.smbcnikko.co.jp" target="_blank">SMBC Nikko</a></li>
        </ul>
        <div class="footer">
            <p>Powered by StockVerse</p>
        </div>
    </div>

    <script>
        // Optional: Adding a console log on hover for fun!
        document.querySelectorAll('.link-list li').forEach(item => {
            item.addEventListener('mouseenter', () => {
                console.log("Link accessed: " + item.innerText);
            });
        });
    </script>

</body>
</html>

</html>
