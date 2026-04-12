<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StriveX Sportswear | Premium Custom Club Uniforms</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;400;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'strive-green': '#a3e635',
                        'strive-dark': '#0a0a0a',
                        'strive-gray': '#1a1a1a',
                        'strive-accent': '#84cc16'
                    },
                    fontFamily: {
                        'display': ['Orbitron', 'sans-serif'],
                        'body': ['Rajdhani', 'sans-serif']
                    },
                    animation: {
                        'pulse-slow': 'pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                        'float': 'float 6s ease-in-out infinite',
                        'glow': 'glow 2s ease-in-out infinite alternate'
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0)' },
                            '50%': { transform: 'translateY(-20px)' },
                        },
                        glow: {
                            'from': { boxShadow: '0 0 10px #a3e635, 0 0 20px #a3e635' },
                            'to': { boxShadow: '0 0 20px #84cc16, 0 0 30px #84cc16' }
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .neon-text {
            text-shadow: 0 0 10px rgba(163, 230, 53, 0.5), 0 0 20px rgba(163, 230, 53, 0.3);
        }
        .neon-border {
            box-shadow: 0 0 10px rgba(163, 230, 53, 0.3), inset 0 0 10px rgba(163, 230, 53, 0.1);
        }
        .glass-panel {
            background: rgba(26, 26, 26, 0.8);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(163, 230, 53, 0.2);
        }
        .hero-bg {
            background: radial-gradient(circle at center, rgba(163, 230, 53, 0.1) 0%, transparent 70%);
        }
        .clip-slant {
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
        }
    </style>
</head>
<body class="bg-strive-dark text-white font-body overflow-x-hidden">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 glass-panel border-b border-strive-green/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex-shrink-0 flex items-center gap-3 cursor-pointer" onclick="window.scrollTo(0,0)">
                    <div class="w-12 h-12 rounded-full bg-gradient-to-br from-strive-green to-strive-accent flex items-center justify-center shadow-lg shadow-strive-green/50">
                        <span class="font-display font-black text-strive-dark text-xl">SX</span>
                    </div>
                    <span class="font-display font-bold text-2xl tracking-wider text-white">STRIVE<span class="text-strive-green">X</span></span>
                </div>
                
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-gray-300 hover:text-strive-green transition-colors duration-300 font-semibold tracking-wide text-lg">HOME</a>
                    <a href="#about" class="text-gray-300 hover:text-strive-green transition-colors duration-300 font-semibold tracking-wide text-lg">ABOUT</a>
                    <a href="#products" class="text-gray-300 hover:text-strive-green transition-colors duration-300 font-semibold tracking-wide text-lg">PRODUCTS</a>
                    <a href="#reviews" class="text-gray-300 hover:text-strive-green transition-colors duration-300 font-semibold tracking-wide text-lg">REVIEWS</a>
                    <a href="#quote" class="text-gray-300 hover:text-strive-green transition-colors duration-300 font-semibold tracking-wide text-lg">GET A QUOTE</a>
                    <a href="#contact" class="px-6 py-2 bg-strive-green text-strive-dark font-bold rounded-full hover:bg-strive-accent transition-all duration-300 transform hover:scale-105 shadow-lg shadow-strive-green/30">CONTACT</a>
                </div>

                <button id="mobile-menu-btn" class="md:hidden text-strive-green focus:outline-none">
                    <svg class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
        </div>

        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-strive-gray border-t border-strive-green/20">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#home" class="block px-3 py-2 text-strive-green font-semibold">HOME</a>
                <a href="#about" class="block px-3 py-2 text-gray-300 hover:text-strive-green">ABOUT</a>
                <a href="#products" class="block px-3 py-2 text-gray-300 hover:text-strive-green">PRODUCTS</a>
                <a href="#reviews" class="block px-3 py-2 text-gray-300 hover:text-strive-green">REVIEWS</a>
                <a href="#quote" class="block px-3 py-2 text-gray-300 hover:text-strive-green">GET A QUOTE</a>
                <a href="#contact" class="block px-3 py-2 text-strive-green font-bold">CONTACT</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative min-h-screen flex items-center justify-center pt-20 overflow-hidden">
        <div class="absolute inset-0 hero-bg"></div>
        <div class="absolute inset-0 bg-[url('data:image/svg+xml,%3Csvg width=\'60\' height=\'60\' viewBox=\'0 0 60 60\' xmlns=\'http://www.w3.org/2000/svg\'%3E%3Cg fill=\'none\' fill-rule=\'evenodd\'%3E%3Cg fill=\'%23a3e635\' fill-opacity=\'0.05\'%3E%3Cpath d=\'M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z\'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E')] opacity-20"></div>
        
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-2 gap-12 items-center">
            <div class="space-y-8 animate-float">
                <div class="inline-block px-4 py-1 rounded-full border border-strive-green/30 bg-strive-green/10 text-strive-green text-sm font-bold tracking-widest uppercase">
                    Premium Sportswear
                </div>
                <h1 class="font-display font-black text-5xl md:text-7xl leading-tight">
                    ELEVATE YOUR <span class="text-strive-green neon-text">GAME</span>
                </h1>
                <p class="text-xl md:text-2xl text-gray-400 font-light max-w-lg">
                    Custom club uniforms designed for champions. Premium quality, bold designs, unbeatable team spirit.
                </p>
                <div class="flex flex-wrap gap-4">
                    <a href="#quote" class="px-8 py-4 bg-strive-green text-strive-dark font-bold text-lg rounded-full hover:bg-strive-accent transition-all duration-300 transform hover:scale-105 shadow-lg shadow-strive-green/50 flex items-center gap-2">
                        GET STARTED
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                    </a>
                    <a href="#products" class="px-8 py-4 border-2 border-strive-green text-strive-green font-bold text-lg rounded-full hover:bg-strive-green hover:text-strive-dark transition-all duration-300">
                        VIEW PRODUCTS
                    </a>
                </div>
            </div>
            
            <div class="relative">
                <div class="absolute inset-0 bg-strive-green/20 rounded-full blur-3xl animate-pulse-slow"></div>
                <div class="relative glass-panel rounded-3xl p-8 transform rotate-3 hover:rotate-0 transition-transform duration-500">
                    <div class="aspect-square rounded-2xl bg-gradient-to-br from-strive-gray to-strive-dark flex items-center justify-center border border-strive-green/20">
                        <div class="text-center">
                            <div class="w-32 h-32 mx-auto mb-4 rounded-full bg-gradient-to-br from-strive-green to-strive-accent flex items-center justify-center shadow-2xl shadow-strive-green/50 animate-glow">
                                <span class="font-display font-black text-strive-dark text-6xl">SX</span>
                            </div>
                            <p class="text-strive-green font-display font-bold text-xl tracking-widest">STRIVEX</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2 animate-bounce">
            <svg class="w-6 h-6 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path></svg>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-24 bg-strive-gray relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="font-display font-bold text-4xl md:text-5xl mb-4">WHO WE <span class="text-strive-green">ARE</span></h2>
                <div class="w-24 h-1 bg-strive-green mx-auto rounded-full"></div>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="glass-panel rounded-2xl p-8 hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 rounded-full bg-strive-green/10 flex items-center justify-center mb-6 border border-strive-green/30">
                        <svg class="w-8 h-8 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <h3 class="font-display font-bold text-2xl mb-4 text-white">Our Mission</h3>
                    <p class="text-gray-400 leading-relaxed">To empower athletes and teams with premium custom sportswear that combines cutting-edge design with ultimate comfort and durability.</p>
                </div>

                <div class="glass-panel rounded-2xl p-8 hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 rounded-full bg-strive-green/10 flex items-center justify-center mb-6 border border-strive-green/30">
                        <svg class="w-8 h-8 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h3 class="font-display font-bold text-2xl mb-4 text-white">Quality First</h3>
                    <p class="text-gray-400 leading-relaxed">We use only the highest-grade fabrics and advanced printing techniques to ensure your uniforms withstand the toughest competitions.</p>
                </div>

                <div class="glass-panel rounded-2xl p-8 hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 rounded-full bg-strive-green/10 flex items-center justify-center mb-6 border border-strive-green/30">
                        <svg class="w-8 h-8 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                    </div>
                    <h3 class="font-display font-bold text-2xl mb-4 text-white">Team Focus</h3>
                    <p class="text-gray-400 leading-relaxed">From local clubs to professional teams, we understand the importance of unity and pride that comes with wearing your colors.</p>
                </div>
            </div>

            <div class="mt-16 glass-panel rounded-3xl p-8 md:p-12 border border-strive-green/20">
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <h3 class="font-display font-bold text-3xl mb-6">Why Choose <span class="text-strive-green">StriveX?</span></h3>
                        <ul class="space-y-4">
                            <li class="flex items-start gap-3">
                                <svg class="w-6 h-6 text-strive-green flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                <span class="text-gray-300">Fully customizable designs tailored to your club identity</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <svg class="w-6 h-6 text-strive-green flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                <span class="text-gray-300">Moisture-wicking, breathable performance fabrics</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <svg class="w-6 h-6 text-strive-green flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                <span class="text-gray-300">Competitive pricing with bulk order discounts</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <svg class="w-6 h-6 text-strive-green flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                <span class="text-gray-300">Fast turnaround times without compromising quality</span>
                            </li>
                        </ul>
                    </div>
                    <div class="relative">
                        <div class="absolute inset-0 bg-strive-green/20 rounded-2xl blur-2xl"></div>
                        <div class="relative bg-strive-dark rounded-2xl p-6 border border-strive-green/30">
                            <div class="grid grid-cols-2 gap-4 text-center">
                                <div class="p-4">
                                    <div class="text-4xl font-display font-bold text-strive-green mb-2">500+</div>
                                    <div class="text-gray-400 text-sm uppercase tracking-wide">Teams Served</div>
                                </div>
                                <div class="p-4 border-l border-strive-green/20">
                                    <div class="text-4xl font-display font-bold text-strive-green mb-2">50k+</div>
                                    <div class="text-gray-400 text-sm uppercase tracking-wide">Uniforms Made</div>
                                </div>
                                <div class="p-4 border-t border-strive-green/20">
                                    <div class="text-4xl font-display font-bold text-strive-green mb-2">98%</div>
                                    <div class="text-gray-400 text-sm uppercase tracking-wide">Satisfaction</div>
                                </div>
                                <div class="p-4 border-t border-l border-strive-green/20">
                                    <div class="text-4xl font-display font-bold text-strive-green mb-2">24h</div>
                                    <div class="text-gray-400 text-sm uppercase tracking-wide">Quote Response</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-24 bg-strive-dark relative overflow-hidden">
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_30%_50%,rgba(163,230,53,0.1),transparent_50%)]"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-16">
                <h2 class="font-display font-bold text-4xl md:text-5xl mb-4">OUR <span class="text-strive-green">PRODUCTS</span></h2>
                <p class="text-gray-400 text-lg max-w-2xl mx-auto">From jerseys to full kits, we craft premium sportswear for every discipline</p>
                <div class="w-24 h-1 bg-strive-green mx-auto rounded-full mt-4"></div>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Product 1 -->
                <div class="group relative glass-panel rounded-2xl overflow-hidden hover:border-strive-green/50 transition-all duration-500">
                    <div class="aspect-[4/5] bg-gradient-to-b from-strive-gray to-strive-dark flex items-center justify-center relative overflow-hidden">
                        <div class="absolute inset-0 bg-strive-green/5 group-hover:bg-strive-green/10 transition-colors duration-300"></div>
                        <div class="text-center z-10 p-6">
                            <div class="w-20 h-20 mx-auto mb-4 rounded-full bg-strive-green/20 flex items-center justify-center border-2 border-strive-green/50 group-hover:scale-110 transition-transform duration-300">
                                <svg class="w-10 h-10 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                            </div>
                            <h3 class="font-display font-bold text-xl text-white mb-2">Match Jerseys</h3>
                            <p class="text-gray-400 text-sm">Professional grade game day uniforms</p>
                        </div>
                    </div>
                    <div class="p-4 border-t border-strive-green/20">
                        <div class="flex justify-between items-center">
                            <span class="text-strive-green font-bold">Custom Design</span>
                            <span class="text-gray-500 text-sm">From $45</span>
                        </div>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="group relative glass-panel rounded-2xl overflow-hidden hover:border-strive-green/50 transition-all duration-500">
                    <div class="aspect-[4/5] bg-gradient-to-b from-strive-gray to-strive-dark flex items-center justify-center relative overflow-hidden">
                        <div class="absolute inset-0 bg-strive-green/5 group-hover:bg-strive-green/10 transition-colors duration-300"></div>
                        <div class="text-center z-10 p-6">
                            <div class="w-20 h-20 mx-auto mb-4 rounded-full bg-strive-green/20 flex items-center justify-center border-2 border-strive-green/50 group-hover:scale-110 transition-transform duration-300">
                                <svg class="w-10 h-10 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg>
                            </div>
                            <h3 class="font-display font-bold text-xl text-white mb-2">Training Kits</h3>
                            <p class="text-gray-400 text-sm">Practice wear that performs</p>
                        </div>
                    </div>
                    <div class="p-4 border-t border-strive-green/20">
                        <div class="flex justify-between items-center">
                            <span class="text-strive-green font-bold">Breathable</span>
                            <span class="text-gray-500 text-sm">From $35</span>
                        </div>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="group relative glass-panel rounded-2xl overflow-hidden hover:border-strive-green/50 transition-all duration-500">
                    <div class="aspect-[4/5] bg-gradient-to-b from-strive-gray to-strive-dark flex items-center justify-center relative overflow-hidden">
                        <div class="absolute inset-0 bg-strive-green/5 group-hover:bg-strive-green/10 transition-colors duration-300"></div>
                        <div class="text-center z-10 p-6">
                            <div class="w-20 h-20 mx-auto mb-4 rounded-full bg-strive-green/20 flex items-center justify-center border-2 border-strive-green/50 group-hover:scale-110 transition-transform duration-300">
                                <svg class="w-10 h-10 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path></svg>
                            </div>
                            <h3 class="font-display font-bold text-xl text-white mb-2">Team Hoodies</h3>
                            <p class="text-gray-400 text-sm">Warm-up and casual wear</p>
                        </div>
                    </div>
                    <div class="p-4 border-t border-strive-green/20">
                        <div class="flex justify-between items-center">
                            <span class="text-strive-green font-bold">Premium Fleece</span>
                            <span class="text-gray-500 text-sm">From $55</span>
                        </div>
                    </div>
                </div>

                <!-- Product 4 -->
                <div class="group relative glass-panel rounded-2xl overflow-hidden hover:border-strive-green/50 transition-all duration-500">
                    <div class="aspect-[4/5] bg-gradient-to-b from-strive-gray to-strive-dark flex items-center justify-center relative overflow-hidden">
                        <div class="absolute inset-0 bg-strive-green/5 group-hover:bg-strive-green/10 transition-colors duration-300"></div>
                        <div class="text-center z-10 p-6">
                            <div class="w-20 h-20 mx-auto mb-4 rounded-full bg-strive-green/20 flex items-center justify-center border-2 border-strive-green/50 group-hover:scale-110 transition-transform duration-300">
                                <svg class="w-10 h-10 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"></path></svg>
                            </div>
                            <h3 class="font-display font-bold text-xl text-white mb-2">Full Club Kits</h3>
                            <p class="text-gray-400 text-sm">Complete team packages</p>
                        </div>
                    </div>
                    <div class="p-4 border-t border-strive-green/20">
                        <div class="flex justify-between items-center">
                            <span class="text-strive-green font-bold">Bundle & Save</span>
                            <span class="text-gray-500 text-sm">Custom</span>
                        </div>
                    </div>
                </div>
            </div>

            <div class="mt-12 text-center">
                <p class="text-gray-400 mb-6">All products include free design consultation and sizing samples for bulk orders</p>
                <a href="#quote" class="inline-flex items-center gap-2 text-strive-green font-bold text-lg hover:gap-4 transition-all duration-300">
                    REQUEST CUSTOM DESIGN 
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                </a>
            </div>
        </div>
    </section>

    <!-- Reviews Section -->
    <section id="reviews" class="py-24 bg-strive-gray relative overflow-hidden">
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_70%_50%,rgba(163,230,53,0.05),transparent_50%)]"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-16">
                <h2 class="font-display font-bold text-4xl md:text-5xl mb-4">COACHES <span class="text-strive-green">REVIEWS</span></h2>
                <p class="text-gray-400 text-lg max-w-2xl mx-auto">See what team leaders say about their StriveX experience</p>
                <div class="w-24 h-1 bg-strive-green mx-auto rounded-full mt-4"></div>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Review 1 -->
                <div class="glass-panel rounded-2xl p-8 relative hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="absolute -top-4 left-8">
                        <div class="w-8 h-8 bg-strive-green rounded-full flex items-center justify-center">
                            <svg class="w-5 h-5 text-strive-dark" fill="currentColor" viewBox="0 0 24 24"><path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/></svg>
                        </div>
                    </div>
                    <div class="flex text-strive-green mb-4 mt-2">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 mb-6 italic">"StriveX transformed our team's appearance completely. The quality of the fabric is exceptional - breathable, durable, and the colors haven't faded after a full season of washing. Our players feel like professionals."</p>
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-strive-green to-strive-accent flex items-center justify-center text-strive-dark font-bold text-lg">MR</div>
                        <div>
                            <h4 class="font-bold text-white">Coach Michael Rodriguez</h4>
                            <p class="text-strive-green text-sm">Thunder FC Soccer Club</p>
                        </div>
                    </div>
                </div>

                <!-- Review 2 -->
                <div class="glass-panel rounded-2xl p-8 relative hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="absolute -top-4 left-8">
                        <div class="w-8 h-8 bg-strive-green rounded-full flex items-center justify-center">
                            <svg class="w-5 h-5 text-strive-dark" fill="currentColor" viewBox="0 0 24 24"><path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/></svg>
                        </div>
                    </div>
                    <div class="flex text-strive-green mb-4 mt-2">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 mb-6 italic">"The customization process was seamless. StriveX worked with our existing logo and color scheme to create something that truly represents our club's identity. Delivery was faster than promised and the pricing was very competitive."</p>
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-strive-green to-strive-accent flex items-center justify-center text-strive-dark font-bold text-lg">SJ</div>
                        <div>
                            <h4 class="font-bold text-white">Coach Sarah Johnson</h4>
                            <p class="text-strive-green text-sm">Elite Basketball Academy</p>
                        </div>
                    </div>
                </div>

                <!-- Review 3 -->
                <div class="glass-panel rounded-2xl p-8 relative hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="absolute -top-4 left-8">
                        <div class="w-8 h-8 bg-strive-green rounded-full flex items-center justify-center">
                            <svg class="w-5 h-5 text-strive-dark" fill="currentColor" viewBox="0 0 24 24"><path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h3.983v10h-9.983z"/></svg>
                        </div>
                    </div>
                    <div class="flex text-strive-green mb-4 mt-2">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 mb-6 italic">"We've ordered from several suppliers over the years, but StriveX is now our permanent choice. The attention to detail in stitching, the comfort of the fit, and the vibrant colors make our rugby team stand out. Highly recommend!"</p>
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-strive-green to-strive-accent flex items-center justify-center text-strive-dark font-bold text-lg">DW</div>
                        <div>
                            <h4 class="font-bold text-white">Coach David Williams</h4>
                            <p class="text-strive-green text-sm">Rugby Warriors United</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="mt-12 text-center">
                <div class="inline-flex items-center gap-2 glass-panel px-6 py-3 rounded-full border border-strive-green/30">
                    <span class="text-strive-green font-bold">Trusted by 500+ Teams Worldwide</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Quote Section -->
    <section id="quote" class="py-24 bg-strive-gray relative">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="glass-panel rounded-3xl p-8 md:p-12 border border-strive-green/30 shadow-2xl shadow-strive-green/10">
                <div class="text-center mb-10">
                    <h2 class="font-display font-bold text-4xl md:text-5xl mb-4">GET A <span class="text-strive-green">QUOTE</span></h2>
                    <p class="text-gray-400">Tell us about your team and we'll get back to you within 24 hours</p>
                </div>

                <form class="space-y-6" onsubmit="event.preventDefault(); alert('Quote request submitted! We will contact you shortly.');">
                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-sm font-bold text-gray-300 mb-2 uppercase tracking-wide">Club/Team Name</label>
                            <input type="text" required class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green focus:ring-1 focus:ring-strive-green transition-colors" placeholder="Enter team name">
                        </div>
                        <div>
                            <label class="block text-sm font-bold text-gray-300 mb-2 uppercase tracking-wide">Sport</label>
                            <select class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green focus:ring-1 focus:ring-strive-green transition-colors">
                                <option>Soccer/Football</option>
                                <option>Basketball</option>
                                <option>Rugby</option>
                                <option>Cricket</option>
                                <option>Netball</option>
                                <option>Other</option>
                            </select>
                        </div>
                    </div>

                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-sm font-bold text-gray-300 mb-2 uppercase tracking-wide">Contact Name</label>
                            <input type="text" required class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green focus:ring-1 focus:ring-strive-green transition-colors" placeholder="Your name">
                        </div>
                        <div>
                            <label class="block text-sm font-bold text-gray-300 mb-2 uppercase tracking-wide">Email</label>
                            <input type="email" required class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green focus:ring-1 focus:ring-strive-green transition-colors" placeholder="email@example.com">
                        </div>
                    </div>

                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-sm font-bold text-gray-300 mb-2 uppercase tracking-wide">Quantity Needed</label>
                            <input type="number" required class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green focus:ring-1 focus:ring-strive-green transition-colors" placeholder="Number of pieces">
                        </div>
                        <div>
                            <label class="block text-sm font-bold text-gray-300 mb-2 uppercase tracking-wide">Needed By</label>
                            <input type="date" class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green focus:ring-1 focus:ring-strive-green transition-colors">
                        </div>
                    </div>

                    <div>
                        <label class="block text-sm font-bold text-gray-300 mb-2 uppercase tracking-wide">Design Details</label>
                        <textarea rows="4" class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green focus:ring-1 focus:ring-strive-green transition-colors" placeholder="Describe your design preferences, colors, logos, or any special requirements..."></textarea>
                    </div>

                    <button type="submit" class="w-full bg-strive-green text-strive-dark font-bold text-lg py-4 rounded-lg hover:bg-strive-accent transition-all duration-300 transform hover:scale-[1.02] shadow-lg shadow-strive-green/30 uppercase tracking-widest">
                        Submit Quote Request
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-24 bg-strive-dark relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="font-display font-bold text-4xl md:text-5xl mb-4">CONTACT <span class="text-strive-green">US</span></h2>
                <p class="text-gray-400 text-lg">Ready to elevate your team's look? Reach out today</p>
                <div class="w-24 h-1 bg-strive-green mx-auto rounded-full mt-4"></div>
            </div>

            <div class="grid md:grid-cols-3 gap-8 mb-16">
                <!-- Email -->
                <a href="mailto:strivexsportswear@gmail.com" class="group glass-panel rounded-2xl p-8 text-center hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 mx-auto mb-4 rounded-full bg-strive-green/10 flex items-center justify-center border border-strive-green/30 group-hover:bg-strive-green/20 transition-colors">
                        <svg class="w-8 h-8 text-strive-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    </div>
                    <h3 class="font-display font-bold text-xl mb-2 text-white">Email Us</h3>
                    <p class="text-strive-green font-semibold break-all">strivexsportswear@gmail.com</p>
                    <p class="text-gray-500 text-sm mt-2">Click to send email</p>
                </a>

                <!-- Instagram -->
                <a href="https://www.instagram.com/strivex_sports?igsh=ejh6Mm5mamM2ZDBl&utm_source=qr" target="_blank" class="group glass-panel rounded-2xl p-8 text-center hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 mx-auto mb-4 rounded-full bg-strive-green/10 flex items-center justify-center border border-strive-green/30 group-hover:bg-strive-green/20 transition-colors">
                        <svg class="w-8 h-8 text-strive-green" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
                    </div>
                    <h3 class="font-display font-bold text-xl mb-2 text-white">Instagram</h3>
                    <p class="text-strive-green font-semibold">@strivex_sports</p>
                    <p class="text-gray-500 text-sm mt-2">Follow our latest designs</p>
                </a>

                <!-- Facebook -->
                <a href="https://www.facebook.com/profile.php?id=61575376886165" target="_blank" class="group glass-panel rounded-2xl p-8 text-center hover:border-strive-green/50 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 mx-auto mb-4 rounded-full bg-strive-green/10 flex items-center justify-center border border-strive-green/30 group-hover:bg-strive-green/20 transition-colors">
                        <svg class="w-8 h-8 text-strive-green" fill="currentColor" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
                    </div>
                    <h3 class="font-display font-bold text-xl mb-2 text-white">Facebook</h3>
                    <p class="text-strive-green font-semibold">StriveX Sports</p>
                    <p class="text-gray-500 text-sm mt-2">Join our community</p>
                </a>
            </div>

            <!-- Quick Contact Form -->
            <div class="glass-panel rounded-2xl p-8 max-w-2xl mx-auto border border-strive-green/20">
                <h3 class="font-display font-bold text-2xl text-center mb-6">Send us a <span class="text-strive-green">Message</span></h3>
                <form class="space-y-4" onsubmit="event.preventDefault(); alert('Message sent! We will contact you soon.');">
                    <div class="grid md:grid-cols-2 gap-4">
                        <input type="text" placeholder="Your Name" required class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green transition-colors">
                        <input type="email" placeholder="Your Email" required class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green transition-colors">
                    </div>
                    <textarea placeholder="Your Message" rows="4" required class="w-full bg-strive-dark border border-strive-green/30 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-strive-green transition-colors"></textarea>
                    <button type="submit" class="w-full bg-strive-green text-strive-dark font-bold py-3 rounded-lg hover:bg-strive-accent transition-colors uppercase tracking-widest">
                        Send Message
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-strive-gray border-t border-strive-green/20 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-center gap-6">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-gradient-to-br from-strive-green to-strive-accent flex items-center justify-center">
                        <span class="font-display font-black text-strive-dark text-sm">SX</span>
                    </div>
                    <span class="font-display font-bold text-xl text-white">STRIVE<span class="text-strive-green">X</span></span>
                </div>
                
                <div class="flex gap-6 text-sm text-gray-400">
                    <a href="#home" class="hover:text-strive-green transition-colors">Home</a>
                    <a href="#about" class="hover:text-strive-green transition-colors">About</a>
                    <a href="#products" class="hover:text-strive-green transition-colors">Products</a>
                    <a href="#reviews" class="hover:text-strive-green transition-colors">Reviews</a>
                    <a href="#quote" class="hover:text-strive-green transition-colors">Quote</a>
                    <a href="#contact" class="hover:text-strive-green transition-colors">Contact</a>
                </div>

                <div class="flex gap-4">
                    <a href="https://www.instagram.com/strivex_sports?igsh=ejh6Mm5mamM2ZDBl&utm_source=qr" target="_blank" class="w-10 h-10 rounded-full bg-strive-dark border border-strive-green/30 flex items-center justify-center text-strive-green hover:bg-strive-green hover:text-strive-dark transition-all">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
                    </a>
                    <a href="https://www.facebook.com/profile.php?id=61575376886165" target="_blank" class="w-10 h-10 rounded-full bg-strive-dark border border-strive-green/30 flex items-center justify-center text-strive-green hover:bg-strive-green hover:text-strive-dark transition-all">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
                    </a>
                    <a href="mailto:strivexsportswear@gmail.com" class="w-10 h-10 rounded-full bg-strive-dark border border-strive-green/30 flex items-center justify-center text-strive-green hover:bg-strive-green hover:text-strive-dark transition-all">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    </a>
                </div>
            </div>
            <div class="mt-8 pt-8 border-t border-strive-green/10 text-center text-gray-500 text-sm">
                <p>&copy; 2026 StriveX Sportswear. All rights reserved. | Custom Club Uniforms</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');
        
        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking a link
        menu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                menu.classList.add('hidden');
            });
        });

        // Smooth scroll for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add shadow to navbar on scroll
        window.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 50) {
                nav.classList.add('shadow-lg', 'shadow-strive-green/10');
            } else {
                nav.classList.remove('shadow-lg', 'shadow-strive-green/10');
            }
        });
    </script>
</body>
</html>
