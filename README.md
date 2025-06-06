* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    padding: 20px 0;
}

.container {
    width: 80%;
    max-width: 1200px;
    margin: 0 auto;
}

header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #222;
    color: #fff;
    padding: 20px 0;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.profile-img {
    border-radius: 50%;
    width: 120px;
    height: 120px;
    object-fit: cover;
}

.info h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.info p {
    font-size: 1.2rem;
    color: #ccc;
}

h2 {
    margin-top: 50px;
    font-size: 2rem;
    color: #333;
    text-align: center;
}

.skills-list {
    display: flex;
    justify-content: space-around;
    margin-top: 30px;
}

.skill {
    text-align: center;
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 30%;
}

.skill h3 {
    font-size: 1.5rem;
    color: #333;
    margin-bottom: 10px;
}

.projects {
    margin-top: 50px;
}

.project {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #222;
    color: #fff;
    margin-top: 50px;
    border-radius: 8px;
}

footer a {
    color: #ff7f00;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
