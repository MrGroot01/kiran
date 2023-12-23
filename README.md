<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Netflix Homepage</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <!-- Navbar -->
        <nav class="navbar">
            <div class="logo">
                <img src="netflix-logo.png" alt="Netflix Logo">
            </div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">TV Shows</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">New & Popular</a></li>
                <li><a href="#">My List</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Main content -->
        <section class="hero-section">
            <div class="hero-text">
                <h1>Unlimited movies, TV shows, and more.</h1>
                <p>Watch anywhere. Cancel anytime.</p>
                <button class="cta-button">Try It Now</button>
            </div>
        </section>

        <!-- Featured content section -->
        <section class="featured-section">
            <h2>Featured Titles</h2>
            <!-- Add featured movies/TV shows -->
            <div class="featured-titles">
                <!-- Example card -->
                <div class="title-card">
                    <img src="movie-thumbnail.jpg" alt="Movie Title">
                    <h3>Movie Title</h3>
                </div>
                <!-- Add more title cards -->
            </div>
        </section>
    </main>

    <footer>
        <!-- Footer content -->
        <p>&copy; 2023 Netflix Clone</p>
    </footer>
</body>

</html>                                                        





/* CSS Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styles */
body {
    font-family: Arial, sans-serif;
}

/* Navbar styles */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #000;
    color: #fff;
}

.nav-links li {
    display: inline;
    margin-right: 20px;
}

.nav-links a {
    text-decoration: none;
    color: #fff;
}

/* Hero section styles */
.hero-section {
    background-image: url('hero-background.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.hero-text h1 {
    font-size: 3em;
    margin-bottom: 20px;
}

.hero-text p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

.cta-button {
    padding: 10px 20px;
    font-size: 1.2em;
    background-color: red;
    color: #fff;
    border: none;
    cursor: pointer;
}

/* Featured section styles */
.featured-section {
    text-align: center;
    padding: 50px 0;
}

.featured-section h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

.featured-titles {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.title-card {
    margin: 10px;
}

.title-card img {
    width: 200px;
    height: 300px;
    object-fit: cover;
    border-radius: 5px;
}

