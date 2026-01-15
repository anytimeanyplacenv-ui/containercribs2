<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Container Cribs | Modern Sustainable Living</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Oswald:wght@500&display=swap" rel="stylesheet">
    <style>
        :root {
            --slate: #2c3e50; /* Modern Container Blue/Grey */
            --wood: #d35400;  /* Industrial Orange/Rust */
            --bg: #ffffff;
            --text: #1a1a1a;
        }

        body { margin: 0; font-family: 'Montserrat', sans-serif; color: var(--text); }
        
        nav { 
            display: flex; justify-content: space-between; padding: 25px 5%; 
            background: var(--slate); color: white; 
        }

        .logo { font-family: 'Oswald', sans-serif; font-size: 1.8rem; letter-spacing: 2px; }

        header {
            display: grid; grid-template-columns: 1fr 1fr; gap: 50px;
            padding: 100px 5%; align-items: center; background: #f4f4f4;
        }

        .hero-img img { width: 100%; border-radius: 4px; border-left: 10px solid var(--slate); }

        h1 { font-family: 'Oswald', sans-serif; font-size: 4rem; margin: 0; text-transform: uppercase; }
        
        .accent-line { width: 60px; height: 5px; background: var(--wood); margin: 20px 0; }

        .price { font-size: 1.5rem; color: var(--wood); font-weight: bold; margin-bottom: 20px; }

        .cta-container { max-width: 350px; }

        .btn-amazon {
            background: #ff9900; background: linear-gradient(to bottom, #f7dfa5, #f0c14b);
            border: 1px solid #a88734; border-radius: 3px; color: #111;
            padding: 15px; text-align: center; text-decoration: none;
            display: flex; align-items: center; justify-content: center; font-weight: bold;
        }

        .fba-tag {
            margin-top: 10px; font-size: 0.8rem; color: #666; font-weight: bold;
            display: flex; align-items: center; gap: 5px;
        }

        @media (max-width: 768px) {
            header { grid-template-columns: 1fr; padding: 40px 5%; text-align: center; }
            h1 { font-size: 2.8rem; }
            .accent-line { margin: 20px auto; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">CONTAINER CRIBS</div>
        <div><small>MODERN • MODULAR • SUSTAINABLE</small></div>
    </nav>

    <header>
        <div class="hero-img">
            <img src="https://images.unsplash.com/photo-1493663276024-7a50d8a1ee17?auto=format&fit=crop&w=800&q=80" alt="Container Crib Interior">
        </div>
        <div class="hero-text">
            <h1>LIVING, <br>UNBOXED.</h1>
            <div class="accent-line"></div>
            <p class="price">$149.00 — $45,000.00</p>
            <p>Premium modular solutions for the modern minimalist. Designed for durability, built for style.</p>
            
            <div class="cta-container">
                <a href="YOUR_LINK_HERE" class="btn-amazon">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" height="15" style="margin-right:10px"> 
                    ORDER ON AMAZON
                </a>
                <div class="fba-tag">✓ FULFILLED BY AMAZON (FBA)</div>
            </div>
        </div>
    </header>

</body>
</html>


