# pls-work
1st code     (19/11/25)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Manga Recommendation Gallery</title>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap');

    :root {
        --card-bg-texture: url('https://www.transparenttextures.com/patterns/brushed-alum.png');
        --page-bg-texture: url('https://www.transparenttextures.com/patterns/paper.png');
    }

    body {
        background-image: var(--page-bg-texture);
        background-size: cover;
        font-family: 'Rock Salt', cursive;
        color: #333;
        text-align: center;
        padding: 20px;
        margin: 0;
        animation: fadeInBody 1.5s ease-in-out;
    }

    /* Keyframes */
    @keyframes fadeInBody {
        from { opacity: 0; }
        to { opacity: 1; }
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }

    /* Header Styling */
    h1 {
        color: #111;
        background-color: rgba(255, 255, 255, 0.8);
        padding: 20px;
        font-size: clamp(24px, 5vw, 40px); /* Responsive font size */
        text-align: center;
        margin: 0 auto 40px auto;
        text-transform: uppercase;
        letter-spacing: 2px;
        border-radius: 10px;
        max-width: 800px;
        width: 90%;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        animation: fadeIn 1s ease-in-out;
    }

    /* Grid Layout (Replaces Table) */
    .gallery-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 30px;
        max-width: 1400px;
        margin: 0 auto;
        padding: 10px;
    }

    /* Card Styling */
    .manga-card {
        padding: 20px;
        text-align: center;
        color: #f4f4f4;
        background-color: rgba(0, 0, 0, 0.6);
        border-radius: 10px;
        background-image: var(--card-bg-texture);
        background-blend-mode: multiply;
        background-size: cover;
        transition: transform 0.3s ease, background-color 0.3s ease, box-shadow 0.3s ease;
        display: flex;
        flex-direction: column;
        align-items: center;
        animation: fadeIn 1.2s ease-in-out;
        /* Ensure the background image covers the card logic */
        background-position: center; 
        background-repeat: no-repeat;
        border: 1px solid rgba(0,0,0,0.3);
    }

    .manga-card:hover {
        transform: translateY(-5px) scale(1.02);
        background-color: rgba(0, 0, 0, 0.8);
        box-shadow: 0 10px 20px rgba(0,0,0,0.5);
        z-index: 10;
    }

    /* Image Styling */
    .manga-card img {
        width: 100%;
        max-width: 250px;
        height: 350px; /* Fixed height for consistency */
        object-fit: cover; /* Prevents stretching */
        margin-bottom: 15px;
        border: 3px solid #000;
        border-radius: 8px;
        transition: transform 0.3s ease;
    }

    .manga-card img:hover {
        transform: scale(1.05);
    }

    /* Typography */
    h3 {
        font-size: 1.5em;
        color: #fff; /* Changed to white for better contrast on dark card */
        text-shadow: 2px 2px 0 #000;
        margin: 10px 0;
        text-transform: uppercase;
    }

    p.description {
        font-size: 1em;
        line-height: 1.5;
        padding: 10px;
        background-color: rgba(0, 0, 0, 0.7);
        color: #f4f4f4;
        margin-top: auto; /* Pushes content down if flex container */
        border-radius: 5px;
        width: 100%;
        box-sizing: border-box;
        font-family: sans-serif; /* readable font for body text */
    }

    .manga-info {
        font-size: 0.9em;
        margin-top: 10px;
        font-style: italic;
        background: rgba(255,255,255,0.1);
        padding: 5px;
        border-radius: 4px;
        width: 100%;
    }
    
    .manga-info p {
        margin: 5px 0;
        font-family: sans-serif;
    }

</style>
</head>
<body>

  <h1>Manga that I like</h1>

  <div class="gallery-grid">
    
    <!-- Berserk -->
    <div class="manga-card" style="background-image: url('https://comicvine.gamespot.com/a/uploads/scale_small/6/67663/5971811-34.jpg');">
        <a href="https://theberserk.online/">
            <img src="https://comicvine.gamespot.com/a/uploads/scale_small/6/67663/5971811-34.jpg" alt="Berserk">
        </a>
        <h3>Berserk</h3>
        <p class="description">A dark fantasy series following Guts, a lone mercenary with a tragic past, as he battles demonic forces.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Kentaro Miura</p>
            <p><strong>Year:</strong> 1989</p>
        </div>
    </div>

    <!-- Vagabond -->
    <div class="manga-card" style="background-image: url('https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1573988886i/453706.jpg');">
        <a href="https://readvagabond-manga.online/">
            <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1573988886i/453706.jpg" alt="Vagabond">
        </a>
        <h3>Vagabond</h3>
        <p class="description">A reimagining of swordsman Miyamoto Musashi's life, following his journey from an aimless youth to a revered samurai.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Takehiko Inoue</p>
            <p><strong>Year:</strong> 1998</p>
        </div>
    </div>

    <!-- Slam Dunk -->
    <div class="manga-card" style="background-image: url('https://i0.wp.com/halcyonrealms.com/blogpics/slamdunknew07.jpg?resize=500%2C780&ssl=1');">
        <a href="https://www.viz.com/slam-dunk">
            <img src="https://i0.wp.com/halcyonrealms.com/blogpics/slamdunknew07.jpg?resize=500%2C780&ssl=1" alt="Slam Dunk">
        </a>
        <h3>Slam Dunk</h3>
        <p class="description">Hanamichi Sakuragi, a high school delinquent, discovers a passion for basketball.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Takehiko Inoue</p>
            <p><strong>Year:</strong> 1990</p>
        </div>
    </div>

    <!-- One Piece -->
    <div class="manga-card" style="background-image: url('https://static1.srcdn.com/wordpress/wp-content/uploads/2024/02/81n5iu4ehal-_sl1500_.jpg');">
        <a href="https://www.viz.com/shonenjump/one-piece-chapter-1/chapter/5090">
            <img src="https://static1.srcdn.com/wordpress/wp-content/uploads/2024/02/81n5iu4ehal-_sl1500_.jpg" alt="One Piece">
        </a>
        <h3>One Piece</h3>
        <p class="description">The adventure of Monkey D. Luffy and his pirate crew as they search for the ultimate treasure.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Eiichiro Oda</p>
            <p><strong>Year:</strong> 1997</p>
        </div>
    </div>

    <!-- Death Note -->
    <div class="manga-card" style="background-image: url('https://acdn.mitiendanube.com/stores/227/495/products/deathnote121-e29f39a32cb2a67e3816124654671555-640-0.jpg');">
        <a href="https://deathnote-manga.online/">
            <img src="https://acdn.mitiendanube.com/stores/227/495/products/deathnote121-e29f39a32cb2a67e3816124654671555-640-0.jpg" alt="Death Note">
        </a>
        <h3>Death Note</h3>
        <p class="description">Light Yagami tries to rid the world of criminals with a notebook that kills, challenged by the detective L.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Tsugumi Ohba</p>
            <p><strong>Year:</strong> 2003</p>
        </div>
    </div>

    <!-- Kengan Ashura -->
    <div class="manga-card" style="background-image: url('https://1.bp.blogspot.com/-Bg5z3r-HTs4/XcyIBguS1DI/AAAAAAAAAtU/K5UgxBUjbW88l6dDOSW5zjGWHSzbjponQCLcBGAsYHQ/s1600/001.jpg');">
        <a href="https://read-kengan-ashura.com/">
            <img src="https://1.bp.blogspot.com/-Bg5z3r-HTs4/XcyIBguS1DI/AAAAAAAAAtU/K5UgxBUjbW88l6dDOSW5zjGWHSzbjponQCLcBGAsYHQ/s1600/001.jpg" alt="Kengan Ashura">
        </a>
        <h3>Kengan Ashura</h3>
        <p class="description">In a world where business deals are settled through gladiator fights, Tokita Ohma enters brutal matches.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Yabako Sandrovich</p>
            <p><strong>Year:</strong> 2012</p>
        </div>
    </div>

     <!-- Baki -->
     <div class="manga-card" style="background-image: url('https://jpbookstore.com/cdn/shop/products/A1yjFdq4LKL_580x.jpg?v=1615372256');">
        <a href="https://manga-baki.com/">
            <img src="https://jpbookstore.com/cdn/shop/products/A1yjFdq4LKL_580x.jpg?v=1615372256" alt="Baki">
        </a>
        <h3>Baki Hanma</h3>
        <p class="description">Baki trains to surpass his father, the strongest man alive, pushing himself in battles against the world’s fiercest fighters.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Keisuke Itagaki</p>
            <p><strong>Year:</strong> 1991</p>
        </div>
    </div>

    <!-- Evangelion -->
    <div class="manga-card" style="background-image: url('https://preview.redd.it/o6l789ztztw41.png?auto=webp&s=82ffe726083b845056caa9072fedc3a861a376ae');">
        <a href="https://neon-genesis-evangelion-online.com/">
            <img src="https://preview.redd.it/o6l789ztztw41.png?auto=webp&s=82ffe726083b845056caa9072fedc3a861a376ae" alt="Eva">
        </a>
        <h3>Evangelion</h3>
        <p class="description">Teen Shinji Ikari pilots a giant mech to defend humanity from Angels, while struggling with internal battles.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Yoshiyuki Sadamoto</p>
            <p><strong>Year:</strong> 1994</p>
        </div>
    </div>

    <!-- Jojo -->
    <div class="manga-card" style="background-image: url('https://comicvine.gamespot.com/a/uploads/scale_small/11133/111331711/6453585-volume_62.jpg');">
        <a href="https://jojosba.com/">
            <img src="https://comicvine.gamespot.com/a/uploads/scale_small/11133/111331711/6453585-volume_62.jpg" alt="Jojo">
        </a>
        <h3>JoJo's Bizarre Adventure</h3>
        <p class="description">An epic tale of the Joestar family across generations, each with unique powers and battling supernatural foes.</p>
        <div class="manga-info">
            <p><strong>Author:</strong> Hirohiko Araki</p>
            <p><strong>Year:</strong> 1987</p>
        </div>
    </div>

  </div>

</body>
</html>
