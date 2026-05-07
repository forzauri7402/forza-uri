[style.css](https://github.com/user-attachments/files/27470390/style.css)
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #fff;
}

/* Navbar Styling */
.navbar {
    background-color: #000;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    letter-spacing: 2px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 13px;
    text-transform: uppercase;
}

.icons span {
    margin-left: 15px;
    cursor: pointer;
}

/* Hero Section Layout */
.hero-container {
    display: flex;
    align-items: center;
    height: 80vh;
    padding: 0 50px;
}

.hero-text {
    flex: 1;
    padding-right: 20px;
}

.hero-text h1 {
    font-size: 40px;
    margin-bottom: 5px;
    font-weight: normal;
}

.hero-text p {
    color: #666;
    margin-bottom: 30px;
}

/* Buy Button Styling */
.buy-btn {
    background-color: #000;
    color: #fff;
    border: none;
    padding: 15px 30px;
    cursor: pointer;
    font-weight: bold;
    font-size: 12px;
    letter-spacing: 1px;
}

.buy-btn:hover {
    background-color: #333;
}

/* Image Section */
.hero-image {
    flex: 2;
    position: relative;
}

.hero-image img {
    width: 100%;
    display: block;
}

.overlay-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #fff;
    font-size: 60px;
    font-weight: bold;
    letter-spacing: 5px;
}
