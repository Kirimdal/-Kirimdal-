<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>À Ma Façon - Restaurant</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f5f2;
            color: #333;
            scroll-behavior: smooth;
        }
        .section-header {
            font-size: 2.5rem;
            font-weight: 700;
            color: #8B4513;
            border-bottom: 2px solid #8B4513;
            display: inline-block;
            padding-bottom: 0.5rem;
            margin-bottom: 2rem;
        }
        .hero-section {
            background-image: url('');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-position: center center;
        }
        .nav-link:hover {
            color: #8B4513;
        }
    </style>
</head>
<body class="bg-gray-100">

    <!-- Navbar -->
    <nav class="bg-white p-4 shadow-lg fixed w-full z-50">
        <div class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-800">À Ma Façon</a>
            <div class="flex space-x-4">
                <a href="#about" class="nav-link text-gray-600 transition duration-300 ease-in-out">À Propos</a>
                <a href="#menu" class="nav-link text-gray-600 transition duration-300 ease-in-out">Menu</a>
                <a href="#contact" class="nav-link text-gray-600 transition duration-300 ease-in-out">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="hero" class="hero-section h-screen flex items-center justify-center text-center text-white p-4">
        <div class="bg-black bg-opacity-75 p-8 rounded-lg max-w-2xl mx-auto shadow-xl">
            <h1 class="text-5xl md:text-7xl font-bold mb-4">À Ma Façon</h1>
            <p class="text-xl md:text-2xl italic font-light mb-6">"Le Kebab chez nous Veau DINDE ça fait toute la différence."</p>
            <div class="flex flex-col md:flex-row space-y-4 md:space-y-0 md:space-x-4">
                <a href="#menu" class="bg-white text-gray-800 font-bold py-3 px-6 rounded-full shadow-lg hover:bg-gray-200 transition duration-300">
                    Découvrez notre menu
                </a>
                <a href="#contact" class="bg-orange-600 text-white font-bold py-3 px-6 rounded-full shadow-lg hover:bg-orange-700 transition duration-300">
                    Réservez une table
                </a>
            </div>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="py-20 px-4">
        <div class="container mx-auto text-center">
            <h2 class="section-header">Notre Histoire</h2>
            <p class="mt-4 text-lg max-w-3xl mx-auto text-gray-700">
                Bienvenue chez À Ma Façon. C'est ici, au cœur d'une cuisine animée, que naissent nos créations. 
                Nous travaillons avec passion, pour vous offrir des plats sincères et généreux. Chaque saveur, chaque texture, est pensée pour vous surprendre et vous 
                faire vivre une expérience culinaire inoubliable.
            </p>
            <div class="mt-10 flex flex-col md:flex-row items-center justify-center gap-8">
                <img src="https://i.postimg.cc/Dy9MCY4w/475721170-1123825902691559-2194912259356897934-n.jpg" alt="la famille Serkan qui le resto A Ma Façon et à Monsieur Peluchon" class="rounded-lg shadow-lg">
                <img src="https://i.postimg.cc/zXgdRS2Z/unnamed.webp" alt="Exterieur du restaurant" class="rounded-lg shadow-lg">
            </div>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="py-20 px-4 bg-gray-50">
        <div class="container mx-auto text-center">
            <h2 class="section-header">Notre Carte, Nos Envies</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mt-10">
                <!-- Exemple d'un plat -->
                <div class="bg-white p-6 rounded-lg shadow-md transition-transform transform hover:scale-105">
                    <img src="https://i.postimg.cc/4NLyCVbM/kebab.png" alt="Les Tacos" class="rounded-lg mb-4 w-full">
                    <h3 class="text-xl font-bold text-gray-800">Tacos 1 viande / Tacos 2 viande / Tacos 3 viande a vous de faire votre choix</h3>
                    <p class="text-gray-600 mt-2">Un repas qui tient au ventre </p>
                    <span class="text-lg font-bold text-orange-600 mt-4 block">1 viande 7€ / 2 viande 9€ / 3 viande 12€ </span>
                </div>
                <!-- Répète le bloc ci-dessus pour d'autres plats -->
                <div class="bg-white p-6 rounded-lg shadow-md transition-transform transform hover:scale-105">
                    <img src="https://i.postimg.cc/9ftj2jHM/Salade.png" alt="Salade César class="rounded-lg mb-4 w-full">
                    <h3 class="text-xl font-bold text-gray-800"></h3>
                    <p class="text-gray-600 mt-2">Un classique la Salade César, avec une salade vert, parmesan, tomate cerise, poulet pané, emincé de poulet, oeuf au plat, ça donne faim .</p>
                    <span class="text-lg font-bold text-orange-600 mt-4 block">9.90€ pour une bonne Salade César</span>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md transition-transform transform hover:scale-105">
                    <img src="https://i.postimg.cc/Jn4SWDQ6/kab.png" alt="Kebab" class="rounded-lg mb-4 w-full">
                    <h3 class="text-xl font-bold text-gray-800">Le Kebab qui donne envie de le manger avec supplément fromage pour plus de gourmandise ou en Dürum qui et encore meilleur</h3>
                    <p class="text-gray-600 mt-2">Une version généreuse et fondante de ce grand classique, préparée à la minute.</p>
                    <span class="text-lg font-bold text-orange-600 mt-4 block">7€ pour le Kebab et vous savez quoi le meme prix pour le Dürum 7€</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-4">
        <div class="container mx-auto text-center">
            <h2 class="section-header">On Vous Attend !</h2>
            <div class="flex flex-col md:flex-row justify-center items-start gap-8 mt-10">
                <div class="bg-white p-8 rounded-lg shadow-md max-w-md w-full">
                    <h3 class="text-xl font-bold mb-4">Informations</h3>
                    <p class="text-gray-700 text-left">
                        <strong>Adresse :</strong> 21 Avenue Général de Gaulle, 54380 Dieulouard, France<br>
                        <strong>Téléphone :</strong> 03 83 23 75 11<br>
                        <strong>Horaires :</strong><br>
                        lundi	    Fermé<br>
                        mardi	    11:00–14:00, 18:00–21:30<br>
                        mercredi	11:00–14:00, 18:00–21:30<br>
                        jeudi	    11:00–14:00, 18:00–21:30<br>
                        vendredi	11:00–14:00, 18:00–21:30<br>
                        samedi	    18:00–21:30<br>
                        dimanche	18:00–21:30<br>
                        
                    </p>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-md max-w-md w-full">
                    <h3 class="text-xl font-bold mb-4">Réservez votre table</h3>
                    <form id="reservation-form" class="space-y-4">
                        <input type="text" placeholder="Nom Complet" required class="w-full p-3 border border-gray-300 rounded-md">
                        <input type="email" placeholder="Email" required class="w-full p-3 border border-gray-300 rounded-md">
                        <input type="tel" placeholder="Téléphone" required class="w-full p-3 border border-gray-300 rounded-md">
                        <input type="date" required class="w-full p-3 border border-gray-300 rounded-md">
                        <input type="time" required class="w-full p-3 border border-gray-300 rounded-md">
                        <input type="number" placeholder="Nombre de personnes" required class="w-full p-3 border border-gray-300 rounded-md">
                        <textarea placeholder="Message (allergies, demandes spéciales...)" rows="4" class="w-full p-3 border border-gray-300 rounded-md"></textarea>
                        <button type="submit" class="w-full bg-orange-600 text-white font-bold py-3 rounded-md hover:bg-orange-700 transition duration-300">
                            Confirmer la réservation
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center p-4 mt-10">
        <p>© 2025 À Ma Façon. Tous droits réservés.</p>
    </footer>
</body>
</html>
