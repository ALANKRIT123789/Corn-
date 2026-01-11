<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Premium adult video streaming website">
    <title>Premium Adult Video Streaming</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#categories">Categories</a></li>
                <li><a href="#premium">Premium</a></li>
                <li><a href="#upload">Upload</a></li>
                <li><a href="#login">Login/Sign Up</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Join Premium for Exclusive Perks!</h1>
        <p>Ad-free experience, exclusive content, and HD quality.</p>
        <button onclick="openPremiumModal()">Join Now</button>
    </section>

    <main>
        <div class="video-grid">
            <div class="video-placeholder">
                <img src="thumbnail1.jpg" alt="Video Title 1">
                <h3>Video Title 1</h3>
                <p>Views: 1000 | Duration: 5:00 | Uploader: User1</p>
            </div>
            <!-- Repeat for 11 more video placeholders -->
        </div>

        <aside class="sidebar">
            <div class="ad-banner">Ad Banner 1</div>
            <div class="ad-banner">Ad Banner 2</div>
        </aside>
    </main>

    <section class="categories">
        <h2>Categories</h2>
        <ul>
            <li><a href="#amateur">Amateur</a></li>
            <li><a href="#hd-porn">HD Porn</a></li>
            <!-- Add more categories as needed -->
        </ul>
    </section>

    <div id="premium-modal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closePremiumModal()">&times;</span>
            <h2>Choose Your Premium Tier</h2>
            <p>Basic: $9.99/mo</p>
            <button onclick="subscribe('basic')">Subscribe</button>
            <p>Unlimited Downloads: $19.99/mo</p>
            <button onclick="subscribe('unlimited')">Subscribe</button>
        </div>
    </div>

    <footer>
        <ul>
            <li><a href="#terms">Terms</a></li>
            <li><a href="#privacy">Privacy</a></li>
            <li><a href="#partners">Partner Links</a></li>
        </ul>
    </footer>

    <div id="age-verification" class="popup">
        <div class="popup-content">
            <h2>Age Verification</h2>
            <p>You must be 18 years or older to enter.</p>
            <button onclick="confirmAge()">I am 18+</button>
        </div>
    </div>
</body>
</html>
