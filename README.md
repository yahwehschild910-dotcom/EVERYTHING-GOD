<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your PDF Store</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f5f5;
    color:#333;
}

header{
    background:#111827;
    color:white;
    padding:20px;
    text-align:center;
}

.hero{
    padding:60px 20px;
    text-align:center;
    background:white;
}

.hero h1{
    font-size:3rem;
    margin-bottom:15px;
}

.hero p{
    max-width:600px;
    margin:auto;
    color:#666;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
    padding:40px;
}

.card{
    background:white;
    padding:20px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.card h3{
    margin-bottom:10px;
}

.card p{
    color:#666;
    margin-bottom:15px;
}

.price{
    font-size:1.4rem;
    font-weight:bold;
    margin-bottom:15px;
}

.btn{
    display:inline-block;
    padding:12px 20px;
    background:#2563eb;
    color:white;
    text-decoration:none;
    border-radius:8px;
}

footer{
    text-align:center;
    padding:20px;
    background:#111827;
    color:white;
}
</style>
</head>

<body>

<header>
    <h2>Banele PDF Store</h2>
</header>

<section class="hero">
    <h1>Premium PDF Resources</h1>
    <p>Download high-quality guides, eBooks, templates, and educational PDFs created to help you learn and grow.</p>
</section>

<section class="products">

    <div class="card">
        <h3>Business Guide PDF</h3>
        <p>Learn how to start and grow your business.</p>
        <div class="price">R99</div>
        <a href="your-pdf-link.pdf" class="btn">Download</a>
    </div>

    <div class="card">
        <h3>Study Notes PDF</h3>
        <p>Well-organized notes to help students succeed.</p>
        <div class="price">R49</div>
        <a href="your-pdf-link.pdf" class="btn">Download</a>
    </div>

    <div class="card">
        <h3>Motivation eBook</h3>
        <p>Powerful lessons for discipline and success.</p>
        <div class="price">R79</div>
        <a href="your-pdf-link.pdf" class="btn">Download</a>
    </div>

</section>

<footer>
    © 2026 Banele PDF Store. All Rights Reserved.
</footer>

</body>
</html>