/* إعدادات عامة */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9;
    color: #333;
}

/* الرأس */
header {
    background-color: #007BFF;
    padding: 10px 0;
    color: white;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

header nav ul li {
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

header nav ul li a:hover {
    text-decoration: underline;
}

/* الأبطال */
.hero {
    text-align: center;
    padding: 50px 0;
    background-color: #007BFF;
    color: white;
}

.hero h1 {
    margin-bottom: 10px;
}

.hero p {
    font-size: 1.2rem;
}

/* المحتوى */
main {
    padding: 20px;
}

form {
    max-width: 400px;
    margin: 0 auto;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

form label {
    display: block;
    margin: 10px 0 5px;
}

form input, form select, form button {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #007BFF;
    color: white;
    border: none;
    font-size: 1rem;
    cursor: pointer;
}

form button:hover {
    background-color: #0056b3;
}

/* الفوتر */
footer {
    text-align: center;
    padding: 10px 0;
    background-color: #333;
    color: white;
    font-size: 0.9rem;
}