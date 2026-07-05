header {
    align-items: center;
    top: 10;
    width: 15;
    background: dodgerblue;
    text-align: center;
}
nav {
    align-items: center;
    top: 0;
    width: 50;
    background: lightskyblue;
    position: relative;
    text-align: center;
}
.navbar {
    background-color: #1f2937;
    padding: 12px 0;
    text-align: center;
    margin-bottom: 20px;
}
.nav-link {
    color: white;
    text-decoration: none;
    font-size: 1rem;
    font-weight: 500;
    padding: 6px 12px;
    margin: 0 6px;
    border-radius: 20px;
    transition: all 0.3s ease;
}
.nav-link:hover {
    background-color: #374151;
    color: #60a5fa;
    transform: translateY(-2px);
}
.nav-link.active {
    background-color: #3b82f6;
    color: white;
    font-weight: 700;
    box-shadow: 0 4px 10px rgba(59, 130, 246, 0.4);
}
body {
    background-color: lightsteelblue; 
    font-family: initial;
}
h1 {
    font-style: oblique;
    text-align: center;
    font-family: cursive;
}
.center-image img {
    display: block;
    margin: 0 auto;
    max-width: 250px;
}
footer {
    align-items: center;
    top: 0;
    width: 50;
    background: lightskyblue;
    position: relative;
    text-align: center;
}
section {
    margin: 30px auto;
    padding: 30px 20px;
    max-width: 1100px;
    border: 2px solid #4169e1;
    border-radius: 12px;
    background-color: white;
    box-shadow: 0 4px 15px rgba(65, 105, 225, 0.1);
}
.hero {
    background: linear-gradient(to right, #4169e1, #1e90ff);
    color: white;
    border: 3px solid #1e3a8a;
    box-shadow: 0 8px 20px rgba(30, 58, 138, 0.3);
}
.featured {
    border: 2px solid royalblue;
}
.why-us {
    background: #f0f4ff;
    border: 2px solid #4169e1;
}
.about-brief {
    border: 2px dashed royalblue;
    font-style: italic;
    color: #333;
}
.tagline {
    border: none;
    background: none;
    padding: 0;
    margin: 15px 0;
}
.product-card {
    border: 2px solid #ddd;
    transition: all 0.3s;
}
.product-card:hover {
    border-color: royalblue;
    transform: translateY(-5px);
}
.email-link {
    color: royalblue;
    font-weight: bold;
    text-decoration: none;
    transition: all 0.3s;
}
.email-link:hover {
    color: #1e3a8a;
    text-decoration: underline;
    background-color: #f0f4ff;
    padding: 2px 6px;
    border-radius: 4px;
}
table {
    width: 100%;
    margin: 15px 0;
    border-collapse: collapse;
}
table td {
    padding: 10px 12px;
    border-bottom: 1px solid #eee;
}
table td:first-child {
    font-weight: bold;
    color: #222;
    width: 40%;
    background-color: #fafafa;
}
table tr:last-child td {
    border-bottom: none;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechZone Gadgets</title>
    <link rel="stylesheet" type="text/css" href="stylesheet.css">
</head>
<body>
    <header>
        <img src="logo.jpg" alt="TechZone Logo" class="logo-image" width="150" height="150">
        <h1>WELCOME TO TECHZONE GADGETS</h1>
    </header>
    <nav>
        <div class="navbar">
	        <a href="1home.html" class="nav-link active">Home</a> &nbsp; &nbsp;
            <a href="2devices(laps+phones).html" class="nav-link active">Devices</a> &nbsp; &nbsp;
            <a href="3gaming.html" class="nav-link active">Game Zone</a> &nbsp; &nbsp;
            <a href="4accessories(wearables+audio).html" class="nav-link active">Accessories</a> &nbsp; &nbsp;
            <a href="5contact.html" class="nav-link active">Contact Us</a> &nbsp; &nbsp;
        </div>
    </nav>
    <hr>
    <h3 class="tagline" align="center">No noise, no chaos. Just tech and vibes.</h3>
    <hr>
      <section class="hero">
        <h2>Discover Tomorrow's Tech Today</h2>
        <p>Premium gadgets, unbeatable prices, and the best shopping experience.</p>
    </section>
    <section class="about-brief">
        <p>TechZone — an idea made alive in 2025 by a tech enthusiast and gamer. 
           Couldn't find what I needed in one store, so I created it.</p>
    </section>
    <section class="featured">
        <h2>Special Offers!!</h2>
        <div class="products-grid">
            <div class="product-card">
                <img src="sennheiser-momentum-5-single.jpg" alt="Sennheiser Momentum 5" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="sennheiser-momentum-5-colors.jpg" alt="Sennheiser Momentum 3 colors" width="250" height="150">
                <h3>SENNHEISER MOMENTUM 5</h3>
                <p>Premium wireless headphones with Hybrid Adaptive ANC</p>
                <p class="price"><s>LKR 145,000</s>&nbsp;LKR 125,000</p>
                <a href="accessories(wearables+audio).html" class="btn-small">View</a>
            </div>
            <div class="product-card">
                <img src="samsung-odyssey-g9-front.jpg" alt="Samsung Odyssey OLED G9" width="200" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="samsung-odyssey-g9-back.jpg" alt="Samsung Odyssey OLED G9" width="200" height="150">
                <h3>Samsung Odyssey OLED G9 (Gaming Monitor)</h3>
                <p>49-inch curved QD-OLED ultrawide display with immersive 32:9 aspect ratio and blazing 240Hz refresh rate</p>
                <p class="price"><s>LKR 600,000</s>&nbsp;LKR 545,000</p>
                <p>Premium gaming monitor with Smart TV features (Tizen OS)</p>
                <a href="gaming.html" class="btn-small">View</a>
            </div>
            <div class="product-card">
                <img src="samsung-galaxy-watch-8-single.jpg" alt="Samsung Galaxy Watch 8" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="samsung-galaxy-watch-8-colors.jpg" alt="Samsung Galaxy Watch 8 colors" width="150" height="150">
                <h3>Samsung Galaxy Watch 8</h3>
                <p>Feature-rich smartwatch with advanced health tracking</p>
                <p class="price"><s>LKR 97,900</s>&nbsp;LKR 94,799</p>
                <a href="accessories(wearables+audio).html" class="btn-small">View</a>
            </div>
    </section>
    <section class="why-us">
        <h2>Why Choose TechZone?</h2>
        <div class="features">
            <div>🚚 Free Shipping on orders over $100</div>
            <div>🔒 1 Year Warranty</div>
            <div>💳 Secure Payment</div>
            <div>🛠 Expert Support</div>
        </div>
    </section>
    <footer>
        <p style="text-align: center;">&copy; 2025 TechZone Gadgets. All Rights Reserved.</p>
        <p style="text-align: center;">Made with ❤️ for tech lovers</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>
		TechZone Devices
	</title>
	<link rel="stylesheet" type="text/css" href="stylesheet.css">
</head>
<body>
	<header>
		<img src="logo.jpg" alt="TechZone Logo" width="50" height="50" align="left";>
		<h1>TECHZONE GADGETS</h1>
	</header>
    <nav>
        <div class="navbar">
            <a href="1home.html" class="nav-link active">Home</a> &nbsp; &nbsp;
            <a href="2devices(laps+phones).html" class="nav-link active">Devices</a> &nbsp; &nbsp;
            <a href="3gaming.html" class="nav-link active">Game Zone</a> &nbsp; &nbsp;
            <a href="4accessories(wearables+audio).html" class="nav-link active">Accessories</a> &nbsp; &nbsp;
            <a href="5contact.html" class="nav-link active">Contact Us</a> &nbsp; &nbsp;
        </div>
    </nav>
<section class="featured">
        <h2>Smart Phones</h2>
        <div class="products-grid">
        <div class="product-card">
                <img src="apple-iphone-17 single product.jpg" alt="Apple iPhone 17" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="apple-iphone-17 all colors.jpg" alt="Apple iPhone 17 in Black, White, Mist Blue, Sage, Lavender" width="200" height="150">
                <h3>Apple iPhone 17</h3>
                <p>6.3", 177g, 8mm thickness, 1206x2622 pixels</p>
                <p class="price">LKR 317,319.17</p>
                <p>Available in Black, White, Mist Blue, Sage and Lavender</p>
                <table>
                <tr>
                    <td>Processor</td>
                    <td>Apple A19</td>
                </tr>
                <tr>
                    <td>Storage</td>
                    <td>512GB 8GB RAM</td>
                </tr>
                <tr>
                    <td>Battery Capacity</td>
                    <td>3692mAh</td>
                </tr>
                <tr>
                    <td>Camera Quality</td>
                    <td>48MP</td>
                </tr>
                </table>
        </div>
        <div class="product-card">
                <img src="samsung-galaxy-s26-ultra single product.jpg"alt="Samsung Galaxy S26 Ultra" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="samsung-galaxy-s26-ultra all colors.jpg"alt="Samsung Galaxy S26 Ultra in White, Sky Blue, Silver Shadow, Black" width="200" height="150">
                <h3>Samsung Galaxy S26 Ultra</h3>
                <p>6.9", 214g, 7.9mm thickness, 1440x3120 pixels</p>
                <p class="price">LKR 386,105.82</p>
                <p>Available in Sky Blue, Black, White, Silver Shadow</p>
                <table>
                <tr>
                    <td>Processor</td>
                    <td>Qualcomm SM8850-1-AD Snapdragon 8 Elite Gen 5</td>
                </tr>
                <tr>
                    <td>Storage</td>
                    <td>512GB 12GB RAM</td>
                </tr>
                <tr>
                    <td>Battery Capacity</td>
                    <td>5000mAh</td>
                </tr>
                <tr>
                    <td>Camera Quality</td>
                    <td>200MP</td>
                </tr>
                </table>
        </div>
        <div class="product-card">
                <img src="xiaomi-redmi-note-15-pro-global single product.jpg"alt="Xiaomi Redmi Note 15 Pro" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="xiaomi-redmi-note-15-pro-global all products.jpg"alt="Xiaomi Redmi Note 15 Pro in Black, Glacier Blue, Mist Purple, Titanium" width="200" height="150">
                <h3>Xiaomi Redmi Note 15 Pro</h3>
                <p>6.83", 210g, 8mm thickness, 1280x2772 pixels</p>
                <p class="price">LKR 110,723.99</p>
                <p>Available in Black, Glacier Blue, Mist Purple, Titanium</p>
                <table>
                <tr>
                    <td>Processor</td>
                    <td>Mediatek Dimensity 7400 Ultra</td>
                </tr>
                <tr>
                    <td>Storage</td>
                    <td>512GB 12GB RAM</td>
                </tr>
                <tr>
                    <td>Battery Capacity</td>
                    <td>6580mAh</td>
                </tr>
                <tr>
                    <td>Camera Quality</td>
                    <td>200MP</td>
                </tr>
                </table>
        </div>
    </section>
<section class="featured">
        <h2>Laptops</h2>
        <div class="product-card">
                <img src="macbook-air-m5-single.jpg" alt="Apple MacBook Air M5" width="200" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="macbook-air-m5-colors.jpg" alt="Apple MacBook Air M5 colors" width="200" height="150">
                <h3>Apple MacBook Air M5</h3>
                <p>13.6-inch or 15.3-inch Liquid Retina display, ultra-thin aluminum chassis, ~2.7–3.3 lbs</p>
                <p class="price">LKR 439,000</p>
                <p>Available in Space Gray, Silver, Midnight, Starlight</p>
                <table>
                <tr>
                    <td>Processor</td>
                    <td>Apple M5 chip, 10-core CPU (4 performance + 6 efficiency cores)</td>
                </tr>
                <tr>
                    <td>Memory</td>
                    <td>16GB unified memory (configurable to 24GB or 32GB)</td>
                </tr>
                <tr>
                    <td>Storage</td>
                    <td>512GB SSD (configurable to 1TB, 2TB, or 4TB)</td>
                </tr>
                <tr>
                    <td>GPU</td>
                    <td>Integrated 8-core or 10-core GPU with ray tracing and 16-core Neural Engine</td>
                </tr>
                <tr>
                    <td>Display</td>
                    <td>13.6-inch or 15.3-inch Liquid Retina (500 nits)</td>
                </tr>
                <tr>
                    <td>Battery Life</td>
                    <td>Up to 18 hours</td>
                </tr>
                <tr>
                    <td>Ports & Connectivity</td>
                    <td>2x Thunderbolt 4, MagSafe 3, 3.5mm jack, Wi-Fi 7, Bluetooth 6</td>
                </tr>
                </table>
        </div>
        <div class="product-card">
                <img src="lenovo-legion-7i-single.jpg" alt="Lenovo Legion 7i" width="200" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="lenovo-legion-7i-colors.jpg" alt="Lenovo Legion 7i colors" width="200" height="150">
                <h3>Lenovo Legion 7i</h3>
                <p>16-inch WQXGA OLED (165/240Hz, HDR), ~0.63–0.7 inches thick, under 5 lbs</p>
                <p class="price">LKR 1,050,000</p>
                <p>High-performance gaming laptop</p>
                <p>Available in Glacier White and Eclipse Black</p>
                <table>
                <tr>
                    <td>Processor</td>
                    <td>Intel Core Ultra 7 255HX or Ultra 9 275HX</td>
                </tr>
                <tr>
                    <td>Memory</td>
                    <td>16GB or 32GB DDR5-5600/6400</td>
                </tr>
                <tr>
                    <td>Storage</td>
                    <td>1TB SSD (configurable higher)</td>
                </tr>
                <tr>
                    <td>GPU</td>
                    <td>NVIDIA RTX 5060 or 5070 Laptop GPU (8GB GDDR7)</td>
                </tr>
                <tr>
                    <td>Display</td>
                    <td>16-inch WQXGA OLED (165/240Hz, HDR)</td>
                </tr>
                <tr>
                    <td>Battery Life</td>
                    <td>High-capacity battery optimized for gaming</td>
                </tr>
                <tr>
                    <td>Ports & Connectivity</td>
                    <td>USB-C/Thunderbolt, HDMI, USB-A, Ethernet, Wi-Fi 7, Bluetooth 5.4</td>
                </tr>
                </table>
        </div>
        <div class="product-card">
                <img src="asus-zenbook-14-single.jpg" alt="Asus ZENBOOK 14" width="200" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="asus-zenbook-14-colors.jpg" alt="Asus ZENBOOK 14 colors" width="200" height="150">
                <h3>Asus ZENBOOK 14</h3>
                <p>14-inch 3K OLED (120Hz), ~0.59 inches thin, ~2.6–2.8 lbs</p>
                <p class="price">LKR 232,000</p>
                <p>Premium ultrathin laptop</p>
                <p>Available in Foggy Silver, Inkwell Gray, Sandstone Beige and Ponder Blue</p>
                <table>
                <tr>
                    <td>Processor</td>
                    <td>Intel Core Ultra 7 155H or Ultra 9 185H</td>
                </tr>
                <tr>
                    <td>Memory</td>
                    <td>Up to 32GB LPDDR5X</td>
                </tr>
                <tr>
                    <td>Storage</td>
                    <td>Up to 1TB PCIe SSD</td>
                </tr>
                <tr>
                    <td>GPU</td>
                    <td>Integrated Intel Arc Graphics</td>
                </tr>
                <tr>
                    <td>Display</td>
                    <td>14-inch 3K OLED (120Hz)</td>
                </tr>
                <tr>
                    <td>Battery Life</td>
                    <td>15–18+ hours</td>
                </tr>
                <tr>
                    <td>Ports & Connectivity</td>
                    <td>2x Thunderbolt 4, USB-A, HDMI 2.1, 3.5mm jack, Wi-Fi 6E</td>
                </tr>
                </table>
        </div>
    </section>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>
	Game Zone
	</title>
	<link rel="stylesheet" type="text/css" href="stylesheet.css">
</head>
<body>
	<header>
		<img src="logo.jpg" alt="TechZone Logo" width="50" height="50" align="left";>
		<h1>TECHZONE GADGETS</h1>
	</header>
    <nav>
        <div class="navbar">
            <a href="1home.html" class="nav-link active">Home</a> &nbsp; &nbsp;
            <a href="2devices(laps+phones).html" class="nav-link active">Devices</a> &nbsp; &nbsp;
            <a href="3gaming.html" class="nav-link active">Game Zone</a> &nbsp; &nbsp;
            <a href="4accessories(wearables+audio).html" class="nav-link active">Accessories</a> &nbsp; &nbsp;
            <a href="5contact.html" class="nav-link active">Contact Us</a> &nbsp; &nbsp;
        </div>
    </nav>
       <section class="featured">
    <h2>Gaming Peripherals</h2>
    <div class="products-grid">
        <div class="product-card">
            <img src="razer-viper-v3-pro-single.jpg" alt="Razer Viper V3 Pro" width="200" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="razer-viper-v3-pro-colors.jpg" alt="Razer Viper V3 Pro colors" width="100" height="150">
            <h3>Razer Viper V3 Pro (Gaming Mouse)</h3>
            <p>Symmetrical ultralight esports design, ultra-responsive Focus Pro 35K sensor, 8K Hz polling</p>
            <p class="price">LKR 45,000 – 55,000</p>
            <p>Available in Black and White</p>
            <table>
                <tr>
                    <td>Sensor</td>
                    <td>Focus Pro 35K Optical Sensor Gen-2</td>
                </tr>
                <tr>
                    <td>Max DPI</td>
                    <td>35,000</td>
                </tr>
                <tr>
                    <td>Polling Rate</td>
                    <td>Up to 8,000 Hz</td>
                </tr>
                <tr>
                    <td>Switches</td>
                    <td>Razer Optical Mouse Switches Gen-3 (90 million clicks)</td>
                </tr>
                <tr>
                    <td>Weight</td>
                    <td>54g (Black) / 55g (White)</td>
                </tr>
                <tr>
                    <td>Battery Life</td>
                    <td>Up to 95 hours (at 1kHz)</td>
                </tr>
                <tr>
                    <td>Connectivity</td>
                    <td>Razer HyperSpeed Wireless + wired</td>
                </tr>
            </table>
        </div>
        <div class="product-card">
            <img src="samsung-odyssey-g9-front.jpg" alt="Samsung Odyssey OLED G9" width="200" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="samsung-odyssey-g9-back.jpg" alt="Samsung Odyssey OLED G9" width="200" height="150">
            <h3>Samsung Odyssey OLED G9 (Gaming Monitor)</h3>
            <p>49-inch curved QD-OLED ultrawide display with immersive 32:9 aspect ratio and blazing 240Hz refresh rate</p>
            <p class="price"><s>LKR 600,000</s>&nbsp;LKR 545,000</p>
            <p>Premium gaming monitor with Smart TV features (Tizen OS)</p>
            <table>
                <tr>
                    <td>Screen Size</td>
                    <td>49-inch curved (1800R)</td>
                </tr>
                <tr>
                    <td>Resolution</td>
                    <td>5120 x 1440 (Dual QHD, 32:9)</td>
                </tr>
                <tr>
                    <td>Panel Type</td>
                    <td>QD-OLED</td>
                </tr>
                <tr>
                    <td>Refresh Rate</td>
                    <td>240 Hz</td>
                </tr>
                <tr>
                    <td>Response Time</td>
                    <td>0.03ms (GTG)</td>
                </tr>
                <tr>
                    <td>Brightness</td>
                    <td>250 nits (typical), higher in HDR</td>
                </tr>
                <tr>
                    <td>Contrast Ratio</td>
                    <td>1,000,000:1</td>
                </tr>
            </table>
        </div>
        <div class="product-card">
            <img src="xbox-elite-series3-single.jpg" alt="Xbox Elite Wireless Controller Series 3" width="200" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="xbox-elite-series3-colors.jpg" alt="Xbox Elite Wireless Controller Series 3 colors" width="250" height="150">
            <h3>Xbox Elite Wireless Controller Series 3</h3>
            <p>Premium customizable controller with interchangeable components and advanced features</p>
            <p class="price">LKR 65,000 – 85,000</p>
            <p>Compatible with Xbox Series X/S, PC, and cloud gaming</p>
            <table>
                <tr>
                    <td>Features</td>
                    <td>Interchangeable thumbsticks, D-pad, paddles (up to 4), adjustable triggers, rubberized grips</td>
                </tr>
                <tr>
                    <td>Connectivity</td>
                    <td>Bluetooth, Wi-Fi 6, USB-C, 3.5mm jack</td>
                </tr>
                <tr>
                    <td>Battery</td>
                    <td>Rechargeable (improved life)</td>
                </tr>
                <tr>
                    <td>Weight</td>
                    <td>Around 345g (with attachments)</td>
                </tr>
                <tr>
                    <td>Customization</td>
                    <td>Xbox Accessories app for profiles and button mapping</td>
                </tr>
            </table>
        </div>
    </div>
</section>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title> 
		TechZone Accessories
	</title>
<link rel="stylesheet" type="text/css" href="stylesheet.css">
</head>
<body>
	<header>
		<img src="logo.jpg" alt="TechZone Logo" width="50" height="50" align="left";>
		<h1>TECHZONE GADGETS</h1>
	</header>
    <nav>
        <div class="navbar">
            <a href="1home.html" class="nav-link active">Home</a> &nbsp; &nbsp;
            <a href="2devices(laps+phones).html" class="nav-link active">Devices</a> &nbsp; &nbsp;
            <a href="3gaming.html" class="nav-link active">Game Zone</a> &nbsp; &nbsp;
            <a href="4accessories(wearables+audio).html" class="nav-link active">Accessories</a> &nbsp; &nbsp;
            <a href="5contact.html" class="nav-link active">Contact Us</a> &nbsp; &nbsp;
        </div>
    </nav>
        <section class="featured">
        <h2>Headphones</h2>
        <div class="products-grid">
            <div class="product-card">
                <img src="sennheiser-momentum-5-single.jpg" alt="Sennheiser Momentum 5" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="sennheiser-momentum-5-colors.jpg" alt="Sennheiser Momentum 3 colors" width="250" height="150">
                <h3>SENNHEISER MOMENTUM 5</h3>
                <p>Premium wireless headphones with Hybrid Adaptive ANC</p>
                <p class="price"><s>LKR 145,000</s>&nbsp;LKR 125,000</p>
                <p>Available in Black, White, and Denim</p>
                <table>
                    <tr><td>Impedance</td><td>520 Ω (active)</td></tr>
                    <tr><td>Sensitivity</td><td>108 dB SPL (1 kHz)</td></tr>
                    <tr><td>Frequency Response</td><td>6 Hz – 40 kHz</td></tr>
                    <tr><td>Driver Size</td><td>42 mm dynamic drivers</td></tr>
                    <tr><td>Bluetooth Version</td><td>5.4 (Bluetooth 6.0 ready)</td></tr>
                    <tr><td>Audio Codecs</td><td>SBC, AAC, aptX, aptX Adaptive, aptX HD/Lossless</td></tr>
                    <tr><td>Active Noise Cancellation</td><td>Yes, Hybrid Adaptive ANC</td></tr>
                    <tr><td>IP Rating</td><td>IP54</td></tr>
                    <tr><td>Battery Life</td><td>Up to 57 hours with ANC</td></tr>
                </table>
            </div>
            <div class="product-card">
                <img src="sony-wh-1000xm6-single.jpg" alt="Sony WH-1000XM6" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="sony-wh-1000xm6-colors.jpg" alt="Sony WH-1000XM6 colors" width="250" height="150">
                <h3>Sony WH-1000XM6</h3>
                <p>Industry-leading noise cancelling wireless headphones</p>
                <p class="price">LKR 105,800</p>
                <p>Available in Black, Silver, and Midnight Blue</p>
                <table>
                    <tr><td>Impedance</td><td>48 Ω (wired, powered)</td></tr>
                    <tr><td>Sensitivity</td><td>103 dB/mW</td></tr>
                    <tr><td>Frequency Response</td><td>4 Hz – 40 kHz (wired)</td></tr>
                    <tr><td>Driver Size</td><td>30 mm</td></tr>
                    <tr><td>Bluetooth Version</td><td>5.3</td></tr>
                    <tr><td>Audio Codecs</td><td>SBC, AAC, LDAC, LC3</td></tr>
                    <tr><td>Active Noise Cancellation</td><td>Yes, advanced Adaptive ANC</td></tr>
                    <tr><td>Battery Life</td><td>Up to 30 hours with ANC</td></tr>
                </table>
            </div>
            <div class="product-card">
                <img src="airpods-max-2-single.jpg" alt="AirPods Max 2" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="airpods-max-2-colors.jpg" alt="AirPods Max 2 colors" width="200" height="150">
                <h3>AirPods Max 2</h3>
                <p>Premium over-ear headphones with excellent sound and ANC</p>
                <p class="price">LKR 179,900</p>
                <p>Available in Midnight, Starlight, Blue, Purple, and Orange</p>
                <table>
                    <tr><td>Driver Size</td><td>40 mm dynamic drivers</td></tr>
                    <tr><td>Bluetooth Version</td><td>5.3</td></tr>
                    <tr><td>Audio Codecs</td><td>AAC, SBC (Lossless via wired)</td></tr>
                    <tr><td>Active Noise Cancellation</td><td>Yes, advanced ANC</td></tr>
                    <tr><td>Battery Life</td><td>Up to 20 hours with ANC</td></tr>
                </table>
            </div>
        </div>
    </section>
    <section class="featured">
        <h2>Wearables</h2>
        <div class="products-grid">
            <div class="product-card">
                <img src="apple-watch-series-11-single.jpg" alt="Apple Watch Series 11" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="apple-watch-series-11-colors.jpg" alt="Apple Watch Series 11 colors" width="175" height="150">
                <h3>Apple Watch Series 11</h3>
                <p>Advanced health and fitness smartwatch</p>
                <p class="price">LKR 129,500</p>
                <p>Available in Midnight, Starlight, Purple, and Graphite</p>
                <table>
                    <tr><td>Display</td><td>Always-On Retina LTPO3 OLED</td></tr>
                    <tr><td>Display Resolution</td><td>496x416 (46mm) / 446x374 (42mm)</td></tr>
                    <tr><td>Processor</td><td>S11 chip</td></tr>
                    <tr><td>Storage</td><td>64 GB</td></tr>
                    <tr><td>IP Rating</td><td>IP6X, 50m water resistant</td></tr>
                    <tr><td>Battery</td><td>Rechargeable lithium-ion</td></tr>
                    <tr><td>Bluetooth</td><td>5.3</td></tr>
                    <tr><td>Sensors</td><td>ECG, Blood Oxygen, Temperature, Heart Rate + more</td></tr>
                </table>
            </div>
            <div class="product-card">
                <img src="samsung-galaxy-watch-8-single.jpg" alt="Samsung Galaxy Watch 8" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="samsung-galaxy-watch-8-colors.jpg" alt="Samsung Galaxy Watch 8 colors" width="150" height="150">
                <h3>Samsung Galaxy Watch 8</h3>
                <p>Feature-rich smartwatch with advanced health tracking</p>
                <p class="price"><s>LKR 97,900</s>&nbsp;LKR 94,799</p>
                <p>Available in Graphite and Silver</p>
                <table>
                    <tr><td>Display</td><td>Super AMOLED</td></tr>
                    <tr><td>Display Resolution</td><td>~480x480</td></tr>
                    <tr><td>Processor</td><td>Exynos W1000 series</td></tr>
                    <tr><td>RAM / Storage</td><td>2 GB / 16–32 GB</td></tr>
                    <tr><td>IP Rating</td><td>IP68 + 5 ATM + MIL-STD</td></tr>
                    <tr><td>Battery</td><td>~590 mAh</td></tr>
                    <tr><td>Bluetooth</td><td>5.3</td></tr>
                    <tr><td>Sensors</td><td>BioActive (HR, ECG, BIA, SpO2), Temperature</td></tr>
                </table>
            </div>
            <div class="product-card">
                <img src="google-pixel-watch-4-single.jpg" alt="Google Pixel Watch 4" width="125" height="150"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="google-pixel-watch-4-colors.jpg" alt="Google Pixel Watch 4 colors" width="300" height="150">
                <h3>Google Pixel Watch 4</h3>
                <p>Smartwatch with deep Fitbit integration</p>
                <p class="price">LKR 116,500</p>
                <p>Available in Porcelain, Hazel, Lemongrass, Bay, and Obsidian</p>
                <table>
                    <tr><td>Display</td><td>AMOLED</td></tr>
                    <tr><td>Display Resolution</td><td>~450x450</td></tr>
                    <tr><td>Processor</td><td>Snapdragon W5 / Tensor integrated</td></tr>
                    <tr><td>RAM / Storage</td><td>2 GB / 32 GB</td></tr>
                    <tr><td>IP Rating</td><td>IP68, 5 ATM</td></tr>
                    <tr><td>Battery</td><td>~300–400 mAh</td></tr>
                    <tr><td>Bluetooth</td><td>5.3</td></tr>
                    <tr><td>Sensors</td><td>ECG, SpO2, Skin Temperature, HR</td></tr>
                </table>
            </div>
        </div>
    </section>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>TechZone Contact</title>
<link rel="stylesheet" type="text/css" href="stylesheet.css">
</head>
<body>
        <header>
                <img src="logo.jpg" alt="TechZone Logo" width="50" height="50" align="left";>
                <h1>TECHZONE GADGETS</h1>
        </header>
    <nav>
        <div class="navbar">
                <a href="1home.html" class="nav-link active">Home</a> &nbsp; &nbsp;
            <a href="2devices(laps+phones).html" class="nav-link active">Devices</a> &nbsp; &nbsp;
            <a href="3gaming.html" class="nav-link active">Game Zone</a> &nbsp; &nbsp;
            <a href="4accessories(wearables+audio).html" class="nav-link active">Accessories</a> &nbsp; &nbsp;
            <a href="5contact.html" class="nav-link active">Contact Us</a> &nbsp; &nbsp;
        </div>
    </nav>
        <section class="featured products">
        <h2>Got a question? Contact us!</h2>
        <p>
        📧 Email: <a href="mailto:techzone.gadgets@gmail.com" class="email-link">techzone.gadgets@gmail.com </a></techzone.gadgets@gmail.com><br>
        📞 Call: 0112345678<br>
        💬 WhatsApp: +94 77 123 4567<br>
        </p>
       </body>
</html>
