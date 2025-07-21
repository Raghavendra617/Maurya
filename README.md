<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maurya Real Estate</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5; /* Lighter background for a modern feel */
        }
    </style>
</head>
<body class="antialiased">
    <!-- Header Section -->
    <header class="bg-white text-gray-800 shadow-md py-4 px-6 md:px-10 rounded-b-lg">
        <div class="container mx-auto flex flex-col md:flex-row justify-between items-center">
            <div class="flex items-center mb-2 md:mb-0">
                <!-- Simple Logo/Icon Placeholder -->
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-600 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m0 0l-7 7m7-7v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
                </svg>
                <h1 class="text-3xl md:text-4xl font-extrabold text-blue-800">Maurya Real Estate</h1>
            </div>
            <div class="text-sm md:text-base text-center md:text-right flex items-center space-x-4">
                <p class="font-medium text-gray-700">Contact: Raghavendra</p>
                <a href="tel:+919535655665" class="text-blue-600 hover:text-blue-800 font-semibold flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                    </svg>
                    9535655665
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section with Search Bar -->
    <section class="relative bg-gradient-to-r from-blue-600 to-blue-800 h-80 md:h-112 flex items-center justify-center text-white rounded-lg mx-4 mt-6 shadow-xl">
        <div class="absolute inset-0 opacity-80 rounded-lg"></div>
        <div class="relative z-10 text-center p-4 w-full max-w-4xl">
            <h2 class="text-4xl md:text-6xl font-extrabold mb-4 leading-tight">Your Journey to the Perfect Home Starts Here</h2>
            <p class="text-lg md:text-xl mb-8 opacity-90">Discover prime properties, expert advice, and seamless transactions.</p>
            <!-- Placeholder Search Bar -->
            <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-4">
                <input type="text" placeholder="Search by location, property type..." class="w-full md:w-3/5 p-4 rounded-lg shadow-lg focus:outline-none focus:ring-2 focus:ring-blue-400 text-gray-800">
                <button class="w-full md:w-auto bg-green-500 text-white py-4 px-8 rounded-lg shadow-lg hover:bg-green-600 transition duration-300 font-bold text-lg">
                    Search Properties
                </button>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section class="container mx-auto my-12 p-8 bg-white rounded-lg shadow-lg">
        <h2 class="text-3xl font-bold text-gray-800 mb-6 text-center">About Maurya Real Estate</h2>
        <p class="text-gray-700 leading-relaxed text-center max-w-4xl mx-auto">
            At Maurya Real Estate, we are committed to transforming your property dreams into reality. With a client-centric approach and an in-depth understanding of the dynamic real estate market, we offer unparalleled services for buying, selling, and renting residential and commercial properties. Our expertise ensures a seamless, transparent, and rewarding experience for every client.
        </p>
    </section>

    <!-- Featured Properties Section -->
    <section class="container mx-auto my-12 p-8 bg-white rounded-lg shadow-lg">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Exclusive Listings</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Property Card 1 -->
            <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden transform transition duration-300 hover:scale-105 hover:shadow-xl border border-gray-100">
                <img src="https://placehold.co/600x400/FF5733/ffffff?text=Modern+Villa" alt="Modern Villa" class="w-full h-52 object-cover">
                <div class="p-6">
                    <h3 class="text-2xl font-bold text-blue-800 mb-2">Contemporary Family Home</h3>
                    <p class="text-gray-600 text-sm mb-3">Spacious and elegant, perfect for modern living.</p>
                    <div class="flex items-center text-gray-700 mb-4 text-lg">
                        <span class="mr-4">🛏️ 4 Beds</span>
                        <span class="mr-4">🛁 3 Baths</span>
                        <span>📏 2500 sqft</span>
                    </div>
                    <p class="text-3xl font-extrabold text-green-700 mb-4"></p>
                    <button class="w-full bg-blue-600 text-white py-3 px-4 rounded-lg hover:bg-blue-700 transition duration-200 font-semibold shadow-md">Explore Home</button>
                </div>
            </div>

            <!-- Property Card 2 -->
            <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden transform transition duration-300 hover:scale-105 hover:shadow-xl border border-gray-100">
                <img src="https://placehold.co/600x400/33FF57/ffffff?text=Spacious+Apartment" alt="Spacious Apartment" class="w-full h-52 object-cover">
                <div class="p-6">
                    <h3 class="text-2xl font-bold text-blue-800 mb-2">Urban Apartment with Skyline Views</h3>
                    <p class="text-gray-600 text-sm mb-3">Luxurious living in the heart of the city.</p>
                    <div class="flex items-center text-gray-700 mb-4 text-lg">
                        <span class="mr-4">🛏️ 3 Beds</span>
                        <span class="mr-4">🛁 2 Baths</span>
                        <span>� 1800 sqft</span>
                    </div>
                    <p class="text-3xl font-extrabold text-green-700 mb-4"></p>
                    <button class="w-full bg-blue-600 text-white py-3 px-4 rounded-lg hover:bg-blue-700 transition duration-200 font-semibold shadow-md">Explore Apartment</button>
                </div>
            </div>

            <!-- Property Card 3 -->
            <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden transform transition duration-300 hover:scale-105 hover:shadow-xl border border-gray-100">
                <img src="https://placehold.co/600x400/3357FF/ffffff?text=Commercial+Space" alt="Commercial Space" class="w-full h-52 object-cover">
                <div class="p-6">
                    <h3 class="text-2xl font-bold text-blue-800 mb-2">Premium Commercial Office Space</h3>
                    <p class="text-gray-600 text-sm mb-3">Strategic location, ideal for growing businesses.</p>
                    <div class="flex items-center text-gray-700 mb-4 text-lg">
                        <span class="mr-4">🏢 Office</span>
                        <span>📏 1200 sqft</span>
                    </div>
                    <p class="text-3xl font-extrabold text-green-700 mb-4"></p>
                    <button class="w-full bg-blue-600 text-white py-3 px-4 rounded-lg hover:bg-blue-700 transition duration-200 font-semibold shadow-md">Explore Space</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action / Contact Section -->
    <section class="bg-blue-700 text-white py-12 px-6 md:px-10 my-12 rounded-lg mx-4 shadow-xl text-center">
        <h2 class="text-3xl md:text-4xl font-bold mb-4">Ready to Find Your Next Property?</h2>
        <p class="text-lg md:text-xl mb-8 max-w-3xl mx-auto opacity-90">
            Whether you're looking to buy, sell, or invest, Maurya Real Estate is your trusted partner. Reach out to us today for personalized assistance.
        </p>
        <div class="flex flex-col items-center justify-center space-y-4 md:space-y-0 md:flex-row md:space-x-6">
            <a href="tel:+919535655665" class="bg-green-500 text-white py-3 px-8 rounded-lg text-xl font-semibold hover:bg-green-600 transition duration-200 flex items-center space-x-2 shadow-lg">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                </svg>
                <span>Call Raghavendra Now</span>
            </a>
            <a href="mailto:info@mauryarealestate.com" class="bg-indigo-500 text-white py-3 px-8 rounded-lg text-xl font-semibold hover:bg-indigo-600 transition duration-200 flex items-center space-x-2 shadow-lg">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8m-2 2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v4m6 4l3 3m0 0l3-3m-3 3v-6" />
                </svg>
                <span>Send Us an Email</span>
            </a>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-900 text-white py-8 px-4 md:px-10 mt-10 rounded-t-lg">
        <div class="container mx-auto text-center text-sm">
            <p>&copy; 2023 Maurya Real Estate. All rights reserved.</p>
            <p class="mt-2">Connecting you to your future home with <span class="text-red-500">&hearts;</span>.</p>
        </div>
    </footer>
</body>
</html>
�
