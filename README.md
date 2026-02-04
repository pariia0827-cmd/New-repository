# New-repository 
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background: linear-gradient(135deg, #ffafbd, #ffc3a0);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

.container {
    background: white;
    border-radius: 20px;
    padding: 40px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.2);
    text-align: center;
    max-width: 500px;
    width: 100%;
    position: relative; /* Important for the moving button */
}

h1 {
    color: #e91e63;
    margin-bottom: 20px;
    font-size: 2.5em;
}

p {
    color: #666;
    margin-bottom: 30px;
    font-size: 1.2em;
}

.btn {
    display: flex;
    gap: 20px;
    justify-content: center;
    margin-top: 30px;
}

.btn a {
    text-decoration: none;
    padding: 15px 30px;
    border-radius: 50px;
    font-size: 1.2em;
    font-weight: bold;
    transition: all 0.3s ease;
}

.btn a:first-child {
    background: #e91e63;
    color: white;
}

.btn a:last-child {
    background: #f8f9fa;
    color: #333;
    border: 2px solid #ddd;
}

.btn a:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.tenor-gif-embed {
    margin: 20px 0;
}

