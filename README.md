* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background: #050805;
    color: white;
}

/* NAVBAR */
.navbar {
    display: flex;
    justify-content: space-between;
    padding: 20px 40px;
    background: black;
    position: sticky;
    top: 0;
}

.logo {
    color: #00ff88;
    font-weight: 700;
}

nav a {
    margin-left: 25px;
    text-decoration: none;
    color: white;
    transition: 0.3s;
}

nav a:hover {
    color: #00ff88;
}

/* HERO */
.hero {
    height: 90vh;
    background: url('images/kit1.jpg') center/cover no-repeat;
    position: relative;
}

.overlay {
    position: absolute;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.7);
}

.hero-content {
    position: relative;
    text-align: center;
    top: 50%;
    transform: translateY(-50%);
}

.hero h2 {
    font-size: 50px;
}

.hero p {
    margin: 15px 0;
}

.btn {
    padding: 12px 25px;
    background: #00ff88;
    color: black;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: 0.3s;
}

.btn:hover {
    background: white;
}

/* SECTIONS */
.section {
    padding: 70px 20px;
    text-align: center;
}

.section h2 {
    color: #00ff88;
    margin-bottom: 20px;
}

/* CARDS */
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: #0c140c;
    border-radius: 10px;
    overflow: hidden;
    transition: 0.3s;
}

.card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

.card:hover {
    transform: translateY(-10px) scale(1.03);
}

/* FEATURES */
.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    margin-top: 20px;
}

/* CONTACT */
.contact a {
    color: #00ff88;
    text-decoration: none;
    margin: 10px;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    background: black;
}