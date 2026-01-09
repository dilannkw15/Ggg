
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cinta untuk Akila ❤️</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        love: '#E63946',
                        soft: '#F1FAEE',
                        sky: '#A8DADC',
                        deep: '#1D3557',
                        light: '#F8FAFC'
                    },
                    fontFamily: {
                        poppins: ['Poppins', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
            .heart-beat {
                animation: heartbeat 1.5s infinite;
            }
            @keyframes heartbeat {
                0% { transform: scale(1); }
                14% { transform: scale(1.1); }
                28% { transform: scale(1); }
                42% { transform: scale(1.1); }
                70% { transform: scale(1); }
            }
            .float {
                animation: float 3s ease-in-out infinite;
            }
            @keyframes float {
                0% { transform: translateY(0px); }
                50% { transform: translateY(-10px); }
                100% { transform: translateY(0px); }
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
</head>
<body class="bg-soft font-poppins text-deep overflow-x-hidden">
    <!-- Navbar -->
    <nav class="fixed w-full z-50 bg-soft/90 backdrop-blur-sm shadow-sm">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center space-x-2">
                <i class="fa fa-heart text-love heart-beat"></i>
                <span class="text-xl font-bold">Untuk Akila</span>
            </a>
            <div class="flex items-center space-x-4">
                <span class="text-sm text-gray-600">Cinta Abadi ❤️</span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center pt-16 px-4">
        <div class="text-center max-w-4xl mx-auto">
            <div class="float mb-8">
                <img src="https://picsum.photos/300/300?random=52" alt="Bunga untuk Akila" class="w-48 h-48 md:w-64 md:h-64 rounded-full mx-auto border-8 border-love/20 shadow-lg">
            </div>
            <h1 class="text-[clamp(2rem,5vw,3.5rem)] font-bold leading-tight mb-4">
                Hai <span class="text-love heart-beat">Akila</span> Sayangku ❤️
            </h1>
            <p class="text-lg md:text-xl text-gray-700 mb-8">
                Website ini dibuat khusus untukmu, sebagai bukti cinta dan kasih sayang yang tak pernah pudar
            </p>
            <div class="flex justify-center space-x-4 mb-12">
                <a href="#cinta" class="bg-love text-white px-6 py-3 rounded-full hover:bg-love/90 transition-colors shadow-md">
                    <i class="fa fa-heart mr-2"></i> Cerita Cinta Kita
                </a>
                <a href="#kenangan" class="border border-love text-love px-6 py-3 rounded-full hover:bg-love/10 transition-colors">
                    <i class="fa fa-book mr-2"></i> Kenangan Kita
                </a>
            </div>
            <div class="flex justify-center space-x-2">
                <i class="fa fa-heart text-love heart-beat text-sm"></i>
                <i class="fa fa-heart text-love heart-beat text-sm" style="animation-delay: 0.2s"></i>
                <i class="fa fa-heart text-love heart-beat text-sm" style="animation-delay: 0.4s"></i>
                <i class="fa fa-heart text-love heart-beat text-sm" style="animation-delay: 0.6s"></i>
                <i class="fa fa-heart text-love heart-beat text-sm" style="animation-delay: 0.8s"></i>
            </div>
        </div>
    </section>

    <!-- Cinta Section -->
    <section id="cinta" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-bold">Mengapa <span class="text-love">Akila</span> Sangat Spesial?</h2>
                <div class="w-24 h-1 bg-love mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-soft p-8 rounded-xl shadow-md hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 bg-love/10 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fa fa-star text-2xl text-love"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Kamu Sangat Cantik</h3>
                    <p class="text-gray-600 text-center">
                        Tidak hanya wajahmu yang cantik, tapi juga hati dan karaktermu yang membuatmu semakin berharga di mataku. Setiap senyummu membuat hari ku menjadi lebih indah.
                    </p>
                </div>

                <div class="bg-soft p-8 rounded-xl shadow-md hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 bg-love/10 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fa fa-heart text-2xl text-love"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Hati yang Baik</h3>
                    <p class="text-gray-600 text-center">
                        Kamu selalu peduli dengan orang lain, suka menolong, dan punya kesabaran yang luar biasa. Itu yang membuat aku semakin mencintaimu setiap hari.
                    </p>
                </div>

                <div class="bg-soft p-8 rounded-xl shadow-md hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 bg-love/10 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fa fa-smile-o text-2xl text-love"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center">Pencipta Kebahagiaan</h3>
                    <p class="text-gray-600 text-center">
                        Di sampingmu aku selalu merasa bahagia dan tenang. Kamu tahu cara membuatku tersenyum bahkan di hari yang paling sulit sekalipun.
                    </p>
                </div>
            </div>

            <div class="mt-16 bg-gradient-to-r from-love/5 to-sky/5 rounded-2xl p-8 md:p-12">
                <div class="text-center max-w-3xl mx-auto">
                    <i class="fa fa-quote-left text-love text-3xl mb-6"></i>
                    <p class="text-xl md:text-2xl italic mb-6">
                        "Aku tidak bisa menjelaskan dengan kata-kata seberapa dalam cintaku untukmu, Akila. Kamu adalah segalanya bagiku, tempat berteduh hatiku, dan alasan aku bisa tersenyum setiap pagi."
                    </p>
                    <p class="font-bold text-love">Untukmu yang tersayang, Akila ❤️</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Kenangan Section -->
    <section id="kenangan" class="py-20 bg-soft">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-bold">Kenangan Indah Bersama <span class="text-love">Akila</span></h2>
                <div class="w-24 h-1 bg-love mx-auto mt-4 rounded-full"></div>
                <p class="mt-4 text-gray-600 max-w-2xl mx-auto">
                    Setiap momen bersamamu adalah kenangan berharga yang selalu kubawa dalam hati
                </p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://picsum.photos/400/300?random=1" alt="Kenangan 1" class="w-full h-48 object-cover">
                    <div class="p-6 bg-white">
                        <h3 class="font-bold text-lg mb-2">Pertemuan Pertama</h3>
                        <p class="text-gray-600 text-sm">
                            Saat pertama kali bertemu denganmu, aku langsung merasa ada yang spesial darimu. Senyummu yang hangat membuat hatiku berdebar kencang.
                        </p>
                    </div>
                </div>

                <div class="rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://picsum.photos/400/300?random=2" alt="Kenangan 2" class="w-full h-48 object-cover">
                    <div class="p-6 bg-white">
                        <h3 class="font-bold text-lg mb-2">Pertama Kali Jalan-jalan</h3>
                        <p class="text-gray-600 text-sm">
                            Hari itu kita jalan-jalan ke taman, makan es krim, dan banyak tertawa bersama. Itu adalah hari paling bahagia dalam hidupku.
                        </p>
                    </div>
                </div>

                <div class="rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://picsum.photos/400/300?random=3" alt="Kenangan 3" class="w-full h-48 object-cover">
                    <div class="p-6 bg-white">
                        <h3 class="font-bold text-lg mb-2">Ulang Tahunmu yang Spesial</h3>
                        <p class="text-gray-600 text-sm">
                            Saat kamu membuka kado yang kuberi, senyum bahagia di wajahmu adalah hadiah terbaik yang bisa kudapatkan. Semoga setiap ulang tahunmu selalu bahagia.
                        </p>
                    </div>
                </div>

                <div class="rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://picsum.photos/400/300?random=4" alt="Kenangan 4" class="w-full h-48 object-cover">
                    <div class="p-6 bg-white">
                        <h3 class="font-bold text-lg mb-2">Liburan Bersama</h3>
                        <p class="text-gray-600 text-sm">
                            Melihatmu senang saat menikmati pemandangan indah membuat aku merasa sangat bersyukur bisa bersama kamu menjalani setiap momen indah.
                        </p>
                    </div>
                </div>

                <div class="rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://picsum.photos/400/300?random=5" alt="Kenangan 5" class="w-full h-48 object-cover">
                    <div class="p-6 bg-white">
                        <h3 class="font-bold text-lg mb-2">Makan Malam Romantis</h3>
                        <p class="text-gray-600 text-sm">
                            Saat kita makan malam bersama di tempat yang indah, aku merasa sangat beruntung memiliki seseorang seperti kamu di hidupku.
                        </p>
                    </div>
                </div>

                <div class="rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow">
                    <img src="https://picsum.photos/400/300?random=6" alt="Kenangan 6" class="w-full h-48 object-cover">
                    <div class="p-6 bg-white">
                        <h3 class="font-bold text-lg mb-2">Momen Sederhana</h3>
                        <p class="text-gray-600 text-sm">
                            Bahkan momen sederhana seperti ngobrol hingga larut malam atau sekadar berdampingan pun menjadi kenangan yang sangat berharga bagiku.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pesan Cinta Section -->
    <section class="py-20 bg-deep text-white">
        <div class="container mx-auto px-4">
            <div class="max-w-3xl mx-auto text-center">
                <h2 class="text-[clamp(1.8rem,3vw,2.5rem)] font-bold mb-8">Pesan Cinta untuk <span class="text-love">Akila</span></h2>
                <div class="bg-white/10 backdrop-blur-sm p-8 md:p-10 rounded-2xl shadow-lg">
                    <p class="text-lg leading-relaxed mb-6">
                        Hai sayang Akila...
                    </p>
                    <p class="text-lg leading-relaxed mb-6">
                        Aku tahu kadang aku tidak sempurna, mungkin sering membuatmu kesal atau tidak bisa selalu ada di sisimu. Tapi satu hal yang pasti, cintaku untukmu adalah nyata dan akan selalu ada selama aku bernafas.
                    </p>
                    <p class="text-lg leading-relaxed mb-6">
                        Kamu adalah wanita terbaik yang pernah kudapatkan di hidupku. Kamu membuatku menjadi orang yang lebih baik setiap harinya. Aku berjanji akan selalu mencintaimu, merawatmu, dan melindungimu dengan segenap kekuatanku.
                    </p>
                    <p class="text-xl font-bold mt-8 text-love">
                        Aku Cinta Kamu Selamanya, Akila Sayangku ❤️
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-soft py-8">
        <div class="container mx-auto px-4 text-center">
            <div class="mb-4">
                <i class="fa fa-heart text-love heart-beat text-2xl"></i>
            </div>
            <p class="text-gray-600 mb-2">Buat dengan cinta untuk Akila yang tersayang</p>
            <p class="text-sm text-gray-500">© Cinta Abadi untuk Akila ❤️</p>
            <div class="mt-6 flex justify-center space-x-4">
                <a href="#" class="w-10 h-10 rounded-full bg-love/10 flex items-center justify-center text-love hover:bg-love/20 transition-colors">
                    <i class="fa fa-heart"></i>
                </a>
                <a href="#" class="w-10 h-10 rounded-full bg-love/10 flex items-center justify-center text-love hover:bg-love/20 transition-colors">
                    <i class="fa fa-gift"></i>
                </a
