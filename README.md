/* styles.css */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: white;
}

header {
    background-color: #333;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 24px;
    color: #fff;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

.search-bar {
    padding: 20px;
    text-align: center;
}

.search-bar input {
    padding: 10px;
    width: 80%;
    font-size: 18px;
    border-radius: 5px;
    border: none;
    background-color: #333;
    color: white;
}

.catalog {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

.game-card {
    background-color: #1f1f1f;
    border-radius: 8px;
    overflow: hidden;
    text-align: center;
    padding: 15px;
    transition: transform 0.3s;
}

.game-card:hover {
    transform: scale(1.05);
}

.game-card img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.game-card h3 {
    font-size: 20px;
    margin: 10px 0;
}

.game-card p {
    font-size: 14px;
    color: #bbb;
}

.game-card button {
    background-color: #ff6347;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 10px;
}

footer {
    background-color: #333;
    padding: 10px;
    text-align: center;
    margin-top: 20px;
}
