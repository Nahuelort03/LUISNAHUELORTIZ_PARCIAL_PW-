body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1, h2 {
    color: #333;
}

section {
    margin: 20px;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

table {
    width: 100%;
    border-collapse: collapse;
}

th, td {
    padding: 10px;
    border: 1px solid #ddd;
    text-align: left;
}

.social-icons {
    display: flex;
    gap: 10px;
}

.icon {
    display: inline-block;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: #333;
    color: #fff;
    text-align: center;
    line-height: 40px;
    transition: background-color 0.3s;
}

.icon:hover {
    background-color: #555;
}

.icon.facebook:hover {
    background-color: #3b5998;
}

.icon.twitter:hover {
    background-color: #1da1f2;
}

.icon.instagram:hover {
    background-color: #e1306c;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

#galeria {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.imagen {
    position: relative;
    width: 200px;
    height: 200px;
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.imagen img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.imagen:hover {
    transform: scale(1.05);
}

.imagen:nth-child(odd) {
    animation: rotate 5s infinite alternate;
}

.imagen:nth-child(even) {
    animation: zoom 5s infinite alternate;
}

.imagen:hover .descripcion {
    opacity: 1;
}

.descripcion {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: rgba(0, 0, 0, 0.7);
    color: #fff;
    padding: 10px;
    text-align: center;
    opacity: 0;
    transition: opacity 0.3s;
}

@keyframes rotate {
    from { transform: rotate(0); }
    to { transform: rotate(360deg); }
}

@keyframes zoom {
    from { transform: scale(1); }
    to { transform: scale(1.2); }
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1, h2 {
    color: #333;
}

.paso {
    margin: 20px;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    opacity: 0;
    transform: translateY(50px);
    transition: opacity 1s ease-out, transform 1s ease-out;
}

.paso img {
    width: 100%;
    height: auto;
    border-radius: 8px 8px 0 0;
}

.paso h2 {
    margin-top: 10px;
}

.paso p {
    margin-top: 10px;
    color: #666;
}

.leer-mas {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    color: #fff;
    background-color: #333;
    border-radius: 4px;
    text-decoration: none;
    transition: background-color 0.3s;
}

.leer-mas:hover {
    background-color: #555;
}
