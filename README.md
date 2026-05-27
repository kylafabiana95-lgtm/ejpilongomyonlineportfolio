<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EJ M. Plongo | Hardware Technician Portfolio</title>
    <!-- Tailwind CSS for modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-gray-50 text-gray-800 font-sans antialiased">

    <!-- Header / Navigation -->
    <header class="bg-slate-900 text-white sticky top-0 z-50 shadow-md">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold tracking-wider text-blue-400">EJ M. PLONGO</a>
            <nav class="space-x-6 hidden md:block">
                <a href="#about" class="hover:text-blue-400 transition">About</a>
                <a href="#approach" class="hover:text-blue-400 transition">My Approach</a>
                <a href="#services" class="hover:text-blue-400 transition">Services</a>
                <a href="#contact" class="bg-blue-600 hover:bg-blue-500 px-4 py-2 rounded-lg transition text-sm font-semibold">Contact Me</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-slate-900 text-white py-24 px-6 text-center border-t border-slate-800">
        <div class="max-w-3xl mx-auto">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 tracking-tight">EJ M. PLONGO</h1>
            <p class="text-blue-400 text-xl md:text-2xl font-semibold tracking-wide uppercase mb-6">Hardware Technician</p>
            <p class="text-gray-400 text-lg mb-8 leading-relaxed">
                Diagnosing technical problems and providing effective hardware solutions with precision and reliability.
            </p>
            <a href="#services" class="bg-blue-600 hover:bg-blue-500 text-white font-bold py-3 px-8 rounded-lg shadow-lg transition duration-300">
                View My Services
            </a>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="py-20 px-6 container mx-auto max-w-5xl">
        <div class="grid md:grid-cols-3 gap-12 items-center">
            <div class="md:col-span-1 text-center md:text-left">
                <h2 class="text-3xl font-bold border-b-4 border-blue-600 inline-block pb-2 mb-6">About Me</h2>
            </div>
            <div class="md:col-span-2">
                <p class="text-gray-600 text-lg leading-relaxed">
                    A dedicated and hardworking Hardware Technician with knowledge in computer troubleshooting, hardware installation, maintenance, and repair. Skilled in diagnosing technical problems and providing effective solutions. Willing to learn new technologies, work under pressure, and contribute positively to the team. Reliable, adaptable, and committed to delivering quality technical support and service.
                </p>
            </div>
        </div>
    </section>

    <hr class="border-gray-200 max-w-5xl mx-auto">

    <!-- My Approach Section -->
    <section id="approach" class="py-20 px-6 bg-white">
        <div class="container mx-auto max-w-5xl">
            <h2 class="text-3xl font-bold text-center mb-12">My Approach as a Technician</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-gray-50 p-6 rounded-xl border border-gray-100 shadow-sm">
                    <div class="text-blue-600 text-2xl mb-4"><i class="fas fa-tools"></i></div>
                    <h3 class="text-xl font-bold mb-2">Quality & Accuracy</h3>
                    <p class="text-gray-600 leading-relaxed">
                        I approach every repair and technical task with patience, accuracy, and professionalism. My goal is to provide fast and reliable solutions while making sure every device works properly before returning it to the client. I carefully diagnose problems and perform repairs using safe and efficient methods.
                    </p>
                </div>
                <div class="bg-gray-50 p-6 rounded-xl border border-gray-100 shadow-sm">
                    <div class="text-blue-600 text-2xl mb-4"><i class="fas fa-heart-handshake"></i></div>
                    <h3 class="text-xl font-bold mb-2">Honesty & Satisfaction</h3>
                    <p class="text-gray-600 leading-relaxed">
                        I value honesty, quality service, and customer satisfaction. Whether it is troubleshooting hardware issues, installing software, upgrading systems, or repairing mobile phones and computers, I always make sure the job is completed properly and tested thoroughly.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 px-6 bg-gray-50">
        <div class="container mx-auto max-w-5xl">
            <h2 class="text-3xl font-bold text-center mb-4">Service Offerings</h2>
            <p class="text-gray-500 text-center mb-12 max-w-2xl mx-auto">Professional technical solutions tailored to keep your devices running at peak performance.</p>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Service 1 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-mobile-alt"></i></div>
                    <h3 class="font-bold text-lg mb-1">Mobile Phone Repair</h3>
                    <p class="text-gray-500 text-sm">Expert repair and troubleshooting for smartphones and mobile devices.</p>
                </div>
                <!-- Service 2 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-laptop"></i></div>
                    <h3 class="font-bold text-lg mb-1">Computer & Laptop Repair</h3>
                    <p class="text-gray-500 text-sm">Full diagnostic and repair services for desktop computers and laptops.</p>
                </div>
                <!-- Service 3 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-microchip"></i></div>
                    <h3 class="font-bold text-lg mb-1">Hardware Installation</h3>
                    <p class="text-gray-500 text-sm">Safe component installation and replacement for all major systems.</p>
                </div>
                <!-- Service 4 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-hdd"></i></div>
                    <h3 class="font-bold text-lg mb-1">PC Upgrades</h3>
                    <p class="text-gray-500 text-sm">Boost speed and storage with RAM, SSD, and HDD upgrades.</p>
                </div>
                <!-- Service 5 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-compact-disc"></i></div>
                    <h3 class="font-bold text-lg mb-1">OS Reformatting</h3>
                    <p class="text-gray-500 text-sm">Operating system installation, updates, and complete system reformatting.</p>
                </div>
                <!-- Service 6 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-shield-virus"></i></div>
                    <h3 class="font-bold text-lg mb-1">Virus & Malware Removal</h3>
                    <p class="text-gray-500 text-sm">Thorough system cleanup to protect your data and improve device security.</p>
                </div>
                <!-- Service 7 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-tachometer-alt"></i></div>
                    <h3 class="font-bold text-lg mb-1">PC Optimization</h3>
                    <p class="text-gray-500 text-sm">Preventive maintenance and system tuning to speed up slow machines.</p>
                </div>
                <!-- Service 8 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-database"></i></div>
                    <h3 class="font-bold text-lg mb-1">Data Backup & Recovery</h3>
                    <p class="text-gray-500 text-sm">Assistance recovering lost files and creating secure backups.</p>
                </div>
                <!-- Service 9 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-wifi"></i></div>
                    <h3 class="font-bold text-lg mb-1">Network & Internet Setup</h3>
                    <p class="text-gray-500 text-sm">Configuring stable local networks, routers, and internet connections.</p>
                </div>
                <!-- Service 10 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-print"></i></div>
                    <h3 class="font-bold text-lg mb-1">Printer Troubleshooting</h3>
                    <p class="text-gray-500 text-sm">Installation, driver configuration, and hardware fixes for printers.</p>
                </div>
                <!-- Service 11 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-cogs"></i></div>
                    <h3 class="font-bold text-lg mb-1">Custom PC Assembly</h3>
                    <p class="text-gray-500 text-sm">Custom PC setup, hardware matching, and tailored build configuration.</p>
                </div>
                <!-- Service 12 -->
                <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition border border-gray-100">
                    <div class="text-blue-600 text-xl mb-3"><i class="fas fa-comments"></i></div>
                    <h3 class="font-bold text-lg mb-1">Consultation & Support</h3>
                    <p class="text-gray-500 text-sm">Basic technical support and hardware purchasing advice.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-slate-900 text-white py-16 px-6 text-center">
        <div class="max-w-xl mx-auto">
            <h2 class="text-3xl font-bold mb-4">Let's Work Together</h2>
            <p class="text-gray-400 mb-8">Need a device repaired, upgraded, or maintained? Get in touch today for reliable technical service.</p>
            
            <!-- Replace the href with your actual email/social links -->
            <div class="flex justify-center space-x-6 text-2xl">
                <a href="mailto:your.email@example.com" class="hover:text-blue-400 transition" title="Email Me"><i class="fas fa-envelope"></i></a>
                <a href="https://linkedin.com" target="_blank" class="hover:text-blue-400 transition" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="https://github.com" target="_blank" class="hover:text-blue-400 transition" title="GitHub"><i class="fab fa-github"></i></a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 text-gray-500 text-xs py-6 text-center border-t border-slate-900">
        &copy; 2026 EJ M. Plongo. All Rights Reserved.
    </footer>

</body>
</html>
