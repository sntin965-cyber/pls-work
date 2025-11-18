# pls-work
1st code     (19/11/25)
<!DOCTYPE html>
<html>
<head>
<title>Yes!</title>
<style>

    @import url('https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap');

    body {
      background-image: url('https://www.transparenttextures.com/patterns/paper.png');
      background-size: cover;
      font-family: 'Rock Salt', sans-serif;
      color: #333;
      text-align: center;
      padding: 20px;
      animation: fadeInBody 1.5s ease-in-out;
    }

    @keyframes fadeInBody {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h1 {
      color: #111;
      background-color: rgba(255, 255, 255, 0.8);
      padding: 15px;
      font-size: 35px;
      text-align: center;
      margin-bottom: 40px;
      text-transform: uppercase;
      letter-spacing: 2px;
      border-radius: 10px;
      width: 80%;
      margin-left: auto;
      margin-right: auto;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      animation: fadeIn 1s ease-in-out;
    }

    table {
      width: 100%;
      max-width: 1200px;
      margin: auto;
      border-collapse: separate;
      border-spacing: 20px;
      table-layout: auto;
    }

    td {
      padding: 15px;
      text-align: center;
      vertical-align: top;
      width: 33%;
      background-size: cover;
      color: #f4f4f4;
      position: relative;
      background-color: rgba(0, 0, 0, 0.6);
      border-radius: 10px;
      background-image: url('https://www.transparenttextures.com/patterns/brushed-alum.png');
      background-blend-mode: multiply;
      transition: transform 0.3s ease, background-color 0.3s ease;
      height: 450px;
      overflow: hidden;
      animation: fadeIn 1.2s ease-in-out;
    }

    td:hover {
      transform: scale(1.05);
      background-color: rgba(0, 0, 0, 0.8);
    }

    img {
      width: 100%;
      height: auto;
      margin-bottom: 10px;
      border: 3px solid #000000;
      border-radius: 8px;
      transition: transform 0.3s ease;
    }

    img:hover {
      transform: scale(1.08);
    }

    h3 {
      font-size: 2em;
      color: #000;
      margin: 0;
      text-transform: uppercase;
    }

    p {
      font-size: 1.1em;
      line-height: 1.6;
      padding: 10px;
      background-color: rgba(0, 0, 0, 0.7);
      color: #f4f4f4;
      margin-top: 10px;
      border-radius: 5px;
    }

    .manga-info {
      font-size: 1em;
      margin-top: 10px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <h1> Manga Manga Manga</h1>
  <table>
    <tr>
      <td style="background-image: https://comicvine.gamespot.com/a/uploads/scale_small/6/67663/5971811-34.jpg;">
        <a href="https://theberserk.online/">
          <img src="https://comicvine.gamespot.com/a/uploads/scale_small/6/67663/5971811-34.jpg" alt="Berserk">
        </a>
        <h3>Berserk</h3>
        <p>A dark fantasy series following Guts, a lone mercenary with a tragic past, as he battles demonic forces and seeks revenge in a brutal world.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Kentaro Miura</p>
          <p><strong>Year:</strong> 1989</p>
        </div>
      </td>
      <td style="background-image: https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1573988886i/453706.jpg;">
        <a href="https://readvagabond-manga.online/">
          <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1573988886i/453706.jpg" alt="Vagabond">
        </a>
        <h3>Vagabond</h3>
        <p>A reimagining of swordsman Miyamoto Musashi's life, following his journey from an aimless youth to a revered samurai.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Takehiko Inoue</p>
          <p><strong>Year:</strong> 1998</p>
        </div>
      </td>
      <td style="background-image: https://i0.wp.com/halcyonrealms.com/blogpics/slamdunknew07.jpg?resize=500%2C780&ssl=1;">
        <a href="https://www.viz.com/slam-dunk">
          <img src="https://i0.wp.com/halcyonrealms.com/blogpics/slamdunknew07.jpg?resize=500%2C780&ssl=1">
        </a>
        <h3>Slam Dunk</h3>
        <p>Hanamichi Sakuragi, a high school delinquent, discovers a passion for basketball, transforming himself into an unstoppable force on the court.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Takehiko Inoue</p>
          <p><strong>Year:</strong> 1990</p>
        </div>
      </td>
    </tr>
    <tr>
      <td style="background-image: https://static1.srcdn.com/wordpress/wp-content/uploads/2024/02/81n5iu4ehal-_sl1500_.jpg;">
        <a href="https://www.viz.com/shonenjump/one-piece-chapter-1/chapter/5090">
          <img src="https://static1.srcdn.com/wordpress/wp-content/uploads/2024/02/81n5iu4ehal-_sl1500_.jpg" alt="One Piece">
        </a>
        <h3>One Piece</h3>
        <p>The adventure of Monkey D. Luffy and his pirate crew as they search for the ultimate treasure, the One Piece, across strange islands and fierce enemies.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Eiichiro Oda</p>
          <p><strong>Year:</strong> 1997</p>
        </div>
      </td>
      <td style="background-image:https://acdn.mitiendanube.com/stores/227/495/products/deathnote121-e29f39a32cb2a67e3816124654671555-640-0.jpg;">
        <a href="https://deathnote-manga.online/">
          <img src="https://acdn.mitiendanube.com/stores/227/495/products/deathnote121-e29f39a32cb2a67e3816124654671555-640-0.jpg">
        </a>
        <h3>Death Note</h3>
        <p>After finding a notebook with the power to kill, Light Yagami tries to rid the world of criminals, only to be challenged by the detective L.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Tsugumi Ohba & Takeshi Obata</p>
          <p><strong>Year:</strong> 2003</p>
        </div>
      </td>
      <td style="background-image: https://1.bp.blogspot.com/-Bg5z3r-HTs4/XcyIBguS1DI/AAAAAAAAAtU/K5UgxBUjbW88l6dDOSW5zjGWHSzbjponQCLcBGAsYHQ/s1600/001.jpg;">
        <a href="https://read-kengan-ashura.com/">
          <img src="https://1.bp.blogspot.com/-Bg5z3r-HTs4/XcyIBguS1DI/AAAAAAAAAtU/K5UgxBUjbW88l6dDOSW5zjGWHSzbjponQCLcBGAsYHQ/s1600/001.jpg" alt="Kengan Ashura">
        </a>
        <h3>Kengan Ashura</h3>
        <p>In a world where business deals are settled through gladiator fights, Tokita Ohma enters brutal matches to prove his strength.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Yabako Sandrovich & Daromeon</p>
          <p><strong>Year:</strong> 2012</p>
        </div>
      </td>
    </tr>
    <tr>
      <td style="background-image: https://jpbookstore.com/cdn/shop/products/A1yjFdq4LKL_580x.jpg?v=1615372256;">
        <a href="https://manga-baki.com/">
          <img src="https://jpbookstore.com/cdn/shop/products/A1yjFdq4LKL_580x.jpg?v=1615372256" alt="Baki Hanma">
        </a>
        <h3>Baki Hanma</h3>
        <p>Baki trains to surpass his father, the strongest man alive, pushing himself in battles against the world’s fiercest fighters.</p>
        <div class="manga-info">
          <p><strong>Author:</strong>Keisuke Itagaki</p>
          <p><strong>Year:</strong>1991</p>
        </div>
      </td>
      <td style="background-image: https://preview.redd.it/o6l789ztztw41.png?auto=webp&s=82ffe726083b845056caa9072fedc3a861a376ae;">
        <a href="https://neon-genesis-evangelion-online.com/">
          <img src="https://preview.redd.it/o6l789ztztw41.png?auto=webp&s=82ffe726083b845056caa9072fedc3a861a376ae" alt="Neon Genesis Evangelion">
        </a>
        <h3>Neon Genesis Evangelion</h3>
        <p>Teen Shinji Ikari pilots a giant mech to defend humanity from Angels, while struggling with internal battles.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Yoshiyuki Sadamoto</p>
          <p><strong>Year:</strong> 1994</p>
        </div>
      </td>
      <td style="background-image: https://comicvine.gamespot.com/a/uploads/scale_small/11133/111331711/6453585-volume_62.jpg;">
        <a href="https://jojosba.com/">
          <img src="https://comicvine.gamespot.com/a/uploads/scale_small/11133/111331711/6453585-volume_62.jpg" alt="JoJo's Bizarre Adventure">
        </a>
        <h3>JoJo's Bizarre Adventure</h3>
        <p>An epic tale of the Joestar family across generations, each with unique powers and battling supernatural foes.</p>
          <div class="manga-info">
          <p><strong>Author:</strong> Hirohiko Araki</p>
          <p><strong>Year:</strong> 1987</p>
        </div>
      </td>
    </tr>
    <tr>
      <td style="background-image: https://preview.redd.it/i-made-this-page-into-a-volume-cover-v0-d2kxhtnwzbhd1.png?width=640&crop=smart&auto=webp&s=469244549cdfdc23a5e469b92e3d18b94c99057a;">
        <a href="https://www.viz.com/chainsaw-man">
          <img src="https://preview.redd.it/i-made-this-page-into-a-volume-cover-v0-d2kxhtnwzbhd1.png?width=640&crop=smart&auto=webp&s=469244549cdfdc23a5e469b92e3d18b94c99057a" alt="Chainsaw Man">
        </a>
        <h3>Chainsaw Man</h3>
        <p>Denji, a young devil hunter, merges with his chainsaw devil companion to fight devils in a dangerous world.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Tatsuki Fujimoto</p>
          <p><strong>Year:</strong> 2018</p>
        </div>
      </td>

      <td style="background-image: https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781974747245/kagurabachi-vol-1-9781974747245_hr.jpg;">
        <a href="https://readkagura.com/">
          <img src="https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781974747245/kagurabachi-vol-1-9781974747245_hr.jpg" alt="Kagurabachi">
        </a>
        <h3>Kagurabachi</h3>
        <p>A swordsmith's journey for vengeance and redemption in a magical world.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Takeru Hokazono</p>
          <p><strong>Year:</strong> 2023</p>
        </div>
      </td>
      <td style="background-image: https://preview.redd.it/96pu86uw88y71.png?width=640&crop=smart&auto=webp&s=46dd52de67b8f276df32389928ef30ce9ea89af0;">
        <a href="https://www.viz.com/hunter-x-hunter">
          <img src="https://preview.redd.it/96pu86uw88y71.png?width=640&crop=smart&auto=webp&s=46dd52de67b8f276df32389928ef30ce9ea89af0" alt="Hunter x Hunter">
        </a>
        <h3>Hunter x Hunter</h3>
        <p>The adventures of Gon Freecss and his journey to find his father in a world of Hunters.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Yoshihiro Togashi</p>
          <p><strong>Year:</strong> 1998</p>
        </div>
      </td>
    </tr>
    <tr>
      <td style="background-image: https://i.ebayimg.com/images/g/kKoAAOSwXl9llqbh/s-l1200.jpg;">
        <a href="https://mangaplus.shueisha.co.jp/titles/100209">
          <img src="https://i.ebayimg.com/images/g/kKoAAOSwXl9llqbh/s-l1200.jpg" alt="Tokyo Underworld">
        </a>
        <h3>Tokyo Underworld</h3>
        <p>A thrilling tale of gangs and supernatural elements in Tokyo's dark alleys.</p>
        <div class="manga-info">
          <p><strong>Author:</strong> Kenji Sakaki</p>
          <p><strong>Year:</strong> 2022</p>
        </div>
      </td>
      <td style="background-image: https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781421569116/monster-vol-6-9781421569116_hr.jpg;">
        <a href="https://medibang.com/mpc/episodes/x22305180432321150024295173/?locale=en">
          <img src="https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781421569116/monster-vol-6-9781421569116_hr.jpg" alt="Dandadan">
        </a>
        <h3>Monster</h3>
        <p>The story follows Kenzo Tenma, a Japanese surgeon in Düsseldorf, Germany, whose life spirals into chaos after saving Johan Liebert, a former patient who turns out to be a psychopathic serial killer.</p>
        <div class="manga-info">
          <p><strong>Author:</strong>Naoki Urasawa</p>
          <p><strong>Year:</strong>1994</p>
        </div>
      </td>
      <td style="background-image: https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1728620747i/63847293.jpg;">
        <a href="https://housekinokunimanga.com/manga/houseki-no-kuni-chapter-105/">
          <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1728620747i/63847293.jpg" alt="Kaiju No. 8">
        </a>
        <h3>Land of the lustrous</h3>
        <p>Phos, a gemstone-like being, in their quest to find purpose and strength in a world where gem-like creatures battle mysterious moon dwellers.</p>
        <div class="manga-info">
          <p><strong>Author:</strong>Haruko Ichikawa</p>
          <p><strong>Year:</strong>2012</p>
        </div>
      </td>
    </tr>
    <tr>
<td style="background-image: https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1668020448i/63264669.jpg;">
  <a href="https://www.vinlandsagamanga.net/manga/vinland-saga-chapter-27/">
    <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1668020448i/63264669.jpg" alt="Vinland Saga">
  </a>
  <h3>Vinland Saga</h3>
  <p>The story follows Thorfinn, the son of a former Viking warrior, on a journey of revenge and self-discovery during the Viking Age.</p>
  <div class="manga-info">
    <p><strong>Author:</strong> Makoto Yukimura</p>
    <p><strong>Year:</strong> 2005</p>
  </div>
  <span class="status">📖 Reading (pain every chapter)</span>
</td>
<td style="background-image:https://www.syfy.com/sites/syfy/files/hellsing-impure-souls-via-amazon.jpg;">
  <a href="https://mangakakalot.com/chapter/jzde76471556853820/chapter_1">
    <img src="https://www.syfy.com/sites/syfy/files/hellsing-impure-souls-via-amazon.jpg" alt="Hellsing">
  </a>
  <h3>Hellsing</h3>
  <p>The story follows the Hellsing Organization as they combat supernatural threats, including vampires and ghouls, with the help of their ultimate weapon, Alucard.</p>
  <div class="manga-info">
    <p><strong>Author:</strong> Kouta Hirano</p>
    <p><strong>Year:</strong> 1997</p>
  </div>
</td>
<td style="background-image: https://howlongtobeat.com/games/1574_Castlevania_Judgment.jpg;">
  <a href="https://mangakakalot.com/chapter/castlevania_curse_of_darkness/chapter_1">
    <img src="https://howlongtobeat.com/games/1574_Castlevania_Judgment.jpg" alt="Castlevania">
  </a>
  <h3>Castlevania</h3>
  <p>The story follows Trevor Belmont and his companions as they battle Dracula and his army of creatures of the night to save humanity.</p>
  <div class="manga-info">
    <p><strong>Author:</strong>Kō Sasakura</p>
    <p><strong>Year:</strong>1986</p>
   </div>
 </td>
</tr
</table>
</body>
</html>
