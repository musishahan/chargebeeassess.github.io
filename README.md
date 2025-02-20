<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://js.chargebee.com/v2/chargebee.js" data-cb-site="chargebee-assessment4-test" ></script>
    <title>Pricing Plans</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f7fc;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .pricing-container {
            display: flex;
            justify-content: space-around;
            gap: 20px;
        }
        .pricing-card {
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            width: 250px;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .pricing-card:hover {
            transform: scale(1.05);
        }
        .pricing-card h2 {
            margin: 0;
            color: #333;
        }
        .price {
            font-size: 36px;
            font-weight: bold;
            color: #3498db;
            margin: 20px 0;
        }
        .price span {
            font-size: 18px;
            color: #555;
        }
        .features {
            list-style: none;
            padding: 0;
            margin: 0;
            text-align: left;
        }
        .features li {
            padding: 5px 0;
        }
        .cta-button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .cta-button:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>
    <div class="pricing-container">
        <!-- Go Plan -->
        <div class="pricing-card">
            <h2>Go</h2>
            <div class="price">$20 <span>/ month</span></div>
            <ul class="features">
                <li>1 Project</li>
                <li>5 GB Storage</li>
                <li>Basic Support</li>
            </ul>
            <a href="javascript:void(0)" data-cb-type="checkout" data-cb-item-0="Go-Plan-USD-Monthly" class="cta-button">Get Started</a>
        </div>

        <!-- Rise Plan -->
        <div class="pricing-card">
            <h2>Rise</h2>
            <div class="price">$40 <span>/ month</span></div>
            <ul class="features">
                <li>5 Projects</li>
                <li>25 GB Storage</li>
                <li>Priority Support</li>
            </ul>
            <a href="javascript:void(0)" data-cb-type="checkout" data-cb-item-0="Rise-Plan-USD-Monthly" class="cta-button">Get Started</a>
        </div>

        <!-- Scale Plan -->
        <div class="pricing-card">
            <h2>Scale</h2>
            <div class="price">$60 <span>/ month</span></div>
            <ul class="features">
                <li>Unlimited Projects</li>
                <li>100 GB Storage</li>
                <li>24/7 Support</li>
            </ul>
            <a href="javascript:void(0)" data-cb-type="checkout" data-cb-item-0="Scale-Plan-USD-Monthly" class="cta-button">Get Started</a>
        </div>
    </div>
</body>
</html>
