<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy 19th Birthday Princess LeighAnne! 🎉</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Playfair+Display:wght@400;500;600;700&display=swap');
        
        :root {
            --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            --accent-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            --whatsapp-gradient: linear-gradient(135deg, #25d366 0%, #128c7e 100%);
            --snapchat-gradient: linear-gradient(135deg, #fffc00 0%, #fffc00 50%, #ffa500 100%);
            --phone-gradient: linear-gradient(135deg, #4285f4 0%, #34a853 100%);
            --glass-bg: rgba(255, 255, 255, 0.1);
            --glass-border: rgba(255, 255, 255, 0.2);
        }
        
        * {
            scroll-behavior: smooth;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #0c0c0c 0%, #1a1a2e 50%, #16213e 100%);
            min-height: 100vh;
        }
        
        .font-playfair { font-family: 'Playfair Display', serif; }
        
        .glass-morphism {
            background: var(--glass-bg);
            backdrop-filter: blur(20px);
            border: 1px solid var(--glass-border);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
        }
        
        .gradient-text {
            background: var(--primary-gradient);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .accent-gradient-text {
            background: var(--accent-gradient);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .floating {
            animation: float 6s ease-in-out infinite;
        }
        
        .floating-delayed {
            animation: float 6s ease-in-out infinite 3s;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-15px) rotate(2deg); }
        }
        
        .fade-in-up {
            animation: fadeInUp 0.8s ease-out forwards;
            opacity: 0;
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .stagger-1 { animation-delay: 0.1s; }
        .stagger-2 { animation-delay: 0.2s; }
        .stagger-3 { animation-delay: 0.3s; }
        .stagger-4 { animation-delay: 0.4s; }
        
        .hover-lift {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .hover-lift:hover {
            transform: translateY(-8px);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.2);
        }
        
        .modern-button {
            background: var(--primary-gradient);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
        }
        
        .modern-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: left 0.5s;
        }
        
        .modern-button:hover::before {
            left: 100%;
        }
        
        .modern-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.4);
        }
        
        .contact-button {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
            text-decoration: none;
            display: block;
        }
        
        .contact-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: left 0.5s;
        }
        
        .contact-button:hover::before {
            left: 100%;
        }
        
        .contact-button:hover {
            transform: translateY(-4px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }
        
        .whatsapp-button {
            background: var(--whatsapp-gradient);
        }
        
        .whatsapp-button:hover {
            box-shadow: 0 15px 35px rgba(37, 211, 102, 0.4);
        }
        
        .snapchat-button {
            background: var(--snapchat-gradient);
            color: #000 !important;
        }
        
        .snapchat-button:hover {
            box-shadow: 0 15px 35px rgba(255, 252, 0, 0.4);
        }
        
        .phone-button {
            background: var(--phone-gradient);
        }
        
        .phone-button:hover {
            box-shadow: 0 15px 35px rgba(66, 133, 244, 0.4);
        }
        
        .particle {
            position: absolute;
            width: 4px;
            height: 4px;
            background: #f093fb;
            border-radius: 50%;
            pointer-events: none;
            animation: particle 4s linear infinite;
        }
        
        @keyframes particle {
            0% {
                transform: translateY(100vh) scale(0);
                opacity: 1;
            }
            100% {
                transform: translateY(-100px) scale(1);
                opacity: 0;
            }
        }
        
        .timeline-item {
            opacity: 0;
            transform: translateX(-50px);
            transition: all 0.6s ease-out;
        }
        
        .timeline-item.visible {
            opacity: 1;
            transform: translateX(0);
        }
        
        .section-padding {
            padding: 4rem 1rem;
        }
        
        /* Full-width Slideshow Styles */
        .slideshow-section {
            padding: 0;
        }
        
        .slideshow-container {
            position: relative;
            width: 100vw;
            height: 90vh;
            min-height: 500px;
            overflow: hidden;
            margin: 0;
        }
        
        .slide {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            transition: all 0.8s ease-in-out;
        }
        
        .slide img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
        }
        
        .slide.active {
            opacity: 1;
        }
        
        .slide.next {
            transform: translateX(100%);
        }
        
        .slide.prev {
            transform: translateX(-100%);
        }
        
        .slideshow-nav {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background: rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.3);
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.3s ease;
            z-index: 10;
            font-size: 24px;
            font-weight: bold;
        }
        
        .slideshow-nav:hover {
            background: rgba(0, 0, 0, 0.7);
            transform: translateY(-50%) scale(1.1);
        }
        
        .slideshow-nav.prev {
            left: 30px;
        }
        
        .slideshow-nav.next {
            right: 30px;
        }
        
        .slideshow-dots {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 15px;
            z-index: 10;
        }
        
        .dot {
            width: 15px;
            height: 15px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.5);
            cursor: pointer;
            transition: all 0.3s ease;
            border: 2px solid rgba(255, 255, 255, 0.3);
        }
        
        .dot.active {
            background: white;
            transform: scale(1.3);
            border-color: white;
        }
        
        .slide-overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(transparent, rgba(0, 0, 0, 0.8));
            color: white;
            padding: 50px 40px 30px;
            text-align: center;
        }
        
        .slide-overlay h3 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        .slide-overlay p {
            font-size: 1.2rem;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }
        
        .scroll-indicator {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: var(--primary-gradient);
            transform-origin: left;
            transform: scaleX(0);
            z-index: 1000;
        }
        
        .pulse-effect {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% {
                box-shadow: 0 0 0 0 rgba(37, 211, 102, 0.7);
            }
            70% {
                box-shadow: 0 0 0 10px rgba(37, 211, 102, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(37, 211, 102, 0);
            }
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .section-padding {
                padding: 2rem 1rem;
            }
            
            .slideshow-container {
                height: 90vh;
                min-height: 400px;
            }
            
            .slideshow-nav {
                width: 50px;
                height: 50px;
                font-size: 20px;
            }
            
            .slideshow-nav.prev {
                left: 20px;
            }
            
            .slideshow-nav.next {
                right: 20px;
            }
            
            .slide-overlay {
                padding: 30px 20px 20px;
            }
            
            .slide-overlay h3 {
                font-size: 1.8rem;
            }
            
            .slide-overlay p {
                font-size: 1rem;
            }
            
            .floating, .floating-delayed {
                font-size: 2rem !important;
            }
        }
        
        @media (max-width: 480px) {
            .section-padding {
                padding: 1.5rem 0.5rem;
            }
            
            .slideshow-container {
                height: 80vh;
                min-height: 300px;
            }
            
            .slideshow-nav {
                width: 45px;
                height: 45px;
                font-size: 18px;
            }
            
            .slideshow-nav.prev {
                left: 15px;
            }
            
            .slideshow-nav.next {
                right: 15px;
            }
        }
    </style>
</head>
<body class="overflow-x-hidden">
    <!-- Scroll Progress Indicator -->
    <div class="scroll-indicator" id="scrollIndicator"></div>
    
    <!-- Floating Particles -->
    <div id="particles-container" class="fixed inset-0 pointer-events-none z-0"></div>
    
    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center relative overflow-hidden section-padding">
        <div class="absolute inset-0 bg-gradient-to-br from-purple-900/20 to-blue-900/20"></div>
        
        <div class="relative z-10 text-center max-w-5xl mx-auto px-4">
            <!-- Floating Icons -->
            <div class="absolute -top-10 -left-10 md:-top-20 md:-left-20 floating text-4xl md:text-6xl opacity-20">✨</div>
            <div class="absolute -top-5 -right-10 md:-top-10 md:-right-20 floating-delayed text-3xl md:text-5xl opacity-20">🎂</div>
            <div class="absolute -bottom-10 left-5 md:-bottom-20 md:left-10 floating text-3xl md:text-4xl opacity-20">🎈</div>
            <div class="absolute -bottom-5 -right-5 md:-bottom-10 md:-right-10 floating-delayed text-3xl md:text-5xl opacity-20">💖</div>
            
            <div class="fade-in-up stagger-1">
                <h1 class="font-playfair text-4xl md:text-7xl lg:text-9xl font-bold gradient-text mb-4 md:mb-6 leading-tight">
                    Princess
                </h1>
                <h2 class="font-playfair text-3xl md:text-5xl lg:text-7xl font-semibold accent-gradient-text mb-6 md:mb-8">
                    LeighAnne
                </h2>
            </div>
            
            <div class="glass-morphism rounded-3xl p-6 md:p-8 lg:p-12 max-w-3xl mx-auto fade-in-up stagger-2">
                <div class="text-xl md:text-2xl lg:text-3xl text-white/90 font-light mb-4">
                    Celebrating 19 Years of Amazing
                </div>
                <div class="text-base md:text-lg text-white/70 mb-6">
                    September 11, 2006 → September 11, 2025
                </div>
                <div class="flex justify-center space-x-2 text-2xl md:text-3xl">
                    <span class="animate-bounce">🎉</span>
                    <span class="animate-bounce" style="animation-delay: 0.1s">🎂</span>
                    <span class="animate-bounce" style="animation-delay: 0.2s">✨</span>
                    <span class="animate-bounce" style="animation-delay: 0.3s">💕</span>
                    <span class="animate-bounce" style="animation-delay: 0.4s">🌟</span>
                </div>
            </div>
            
            <div class="mt-8 md:mt-12 fade-in-up stagger-3">
                <button onclick="scrollToSection('gallery')" class="modern-button text-white font-semibold py-3 md:py-4 px-6 md:px-8 rounded-full text-base md:text-lg">
                    View Photo Memories
                </button>
            </div>
        </div>
    </section>
    
    <!-- Full-width Photo Gallery Slideshow Section -->
    <section id="gallery" class="slideshow-section">
        <div class="text-center py-16 bg-black/30">
            <h2 class="font-playfair text-3xl md:text-5xl lg:text-6xl font-bold gradient-text mb-8">
                Beautiful Memories
            </h2>
        </div>
        
        <div class="slideshow-container">
            <!-- Sample slides with placeholder images - replace with actual photos -->
           

            <div class="slide active">
                <img src="IMG_202509102010240.JPG" alt="Princess LeighAnne Birthday Memory 1" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess LeighAnne</h3>
                    <p>Add your beautiful birthday photos here!</p>
                </div>
            </div>
            
            <div class="slide">
                <img src="IMG_202509101902362.JPG" alt="Princess LeighAnne Birthday Memory 2" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Special Moments</h3>
                    <p>Celebrating 19 amazing years!</p>
                </div>
            </div>

            <div class="slide">
               <video src="IMG_202509102156330.MP4" controls autoplay loop muted width="100%"></video>
            </div>
            
            <div class="slide">
                <img src="IMG_1010.JPG" alt="Princess LeighAnne Birthday Memory 3" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Birthday Memories</h3>
                    <p>Creating beautiful memories together</p>
                </div>
            </div>
            
            <div class="slide">
                <img src="IMG_202509101902361.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>

            <div class="slide">
                <img src="IMG_202509102144530.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>
            <div class="slide">
                <img src="IMG_202509102144531.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>
            
            <div class="slide">
                <img src="IMG_202509102144535.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>
               <div class="slide">
                <img src="IMG_202509102144536.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>
             <div class="slide">
                <img src="IMG_202509102144537.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>

             <div class="slide">
                <img src="IMG_202509102144538.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>

            <div class="slide">
                <img src="IMG_202509102144539.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>
            <div class="slide">
               <video src="IMG_202509102156330.MP4" controls autoplay loop muted width="100%"></video>
            </div>

             <div class="slide">
                <img src="IMG_202509102154050.JPG" alt="Princess LeighAnne Birthday Memory 4" loading="lazy">
                <div class="slide-overlay">
                    <h3 class="font-playfair font-bold">Princess Moments</h3>
                    <p>Every moment is special with you</p>
                </div>
            </div>

            
            <!-- Navi
            <!-- Navigation buttons -->
            <button class="slideshow-nav prev" onclick="changeSlide(-1)">‹</button>
            <button class="slideshow-nav next" onclick="changeSlide(1)">›</button>
            
            <!-- Dots indicator -->
            <div class="slideshow-dots">
                <span class="dot active" onclick="currentSlide(1)"></span>
                <span class="dot" onclick="currentSlide(2)"></span>
                <span class="dot" onclick="currentSlide(3)"></span>
                <span class="dot" onclick="currentSlide(4)"></span>
            </div>
        </div>
        
        <div class="text-center py-16 px-4 bg-black/20">
            <div class="max-w-2xl mx-auto">
                <p class="text-white/70 text-base md:text-lg mb-6">
                    💡 Upload your favorite photos of Princess LeighAnne to create a personalized slideshow!
                </p>
                <button class="modern-button text-white px-6 md:px-8 py-3 md:py-4 rounded-2xl font-medium text-base md:text-lg">
                    Upload Photos 📸
                </button>
            </div>
        </div>
    </section>
    
    <!-- Journey Section -->
    <section id="journey" class="section-padding bg-black/20">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="font-playfair text-3xl md:text-5xl lg:text-6xl font-bold text-center mb-8 md:mb-16 gradient-text">
                Our Journey Together
            </h2>
            
            <div class="grid lg:grid-cols-2 gap-8 md:gap-12 items-center">
                <div class="space-y-6 md:space-y-8">
                    <div class="timeline-item glass-morphism rounded-2xl p-6 md:p-8 hover-lift">
                        <div class="flex items-center mb-4 md:mb-6">
                            <div class="w-12 h-12 md:w-16 md:h-16 bg-gradient-to-r from-purple-500 to-pink-500 rounded-2xl flex items-center justify-center text-xl md:text-2xl mr-4">
                                🏫
                            </div>
                            <div>
                                <h3 class="font-playfair text-xl md:text-2xl font-semibold text-white mb-1">Achimota Beginnings</h3>
                                <p class="text-white/60 text-xs md:text-sm">Where it all started</p>
                            </div>
                        </div>
                        <p class="text-white/80 leading-relaxed text-sm md:text-base">
                            From those early days at Achimota School when we were just getting to know each other. 
                            Little did we know this would blossom into such a beautiful friendship.
                        </p>
                    </div>
                    
                    <div class="timeline-item glass-morphism rounded-2xl p-6 md:p-8 hover-lift">
                        <div class="flex items-center mb-4 md:mb-6">
                            <div class="w-12 h-12 md:w-16 md:h-16 bg-gradient-to-r from-pink-500 to-red-500 rounded-2xl flex items-center justify-center text-xl md:text-2xl mr-4">
                                💝
                            </div>
                            <div>
                                <h3 class="font-playfair text-xl md:text-2xl font-semibold text-white mb-1">Growing Connection</h3>
                                <p class="text-white/60 text-xs md:text-sm">Building trust & love</p>
                            </div>
                        </div>
                        <p class="text-white/80 leading-relaxed text-sm md:text-base">
                            Princess, I never imagined writing birthday codes for you back then! But here we are - 
                            calling each other during tough times, celebrating together, proving what real friendship means.
                        </p>
                        <div class="mt-4 text-white/60 italic text-xs md:text-sm">
                            ~ With love, Afia 💕
                        </div>
                    </div>
                    
                    <div class="timeline-item glass-morphism rounded-2xl p-6 md:p-8 hover-lift">
                        <div class="flex items-center mb-4 md:mb-6">
                            <div class="w-12 h-12 md:w-16 md:h-16 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl flex items-center justify-center text-xl md:text-2xl mr-4">
                                👑
                            </div>
                            <div>
                                <h3 class="font-playfair text-xl md:text-2xl font-semibold text-white mb-1">Unbreakable Bond</h3>
                                <p class="text-white/60 text-xs md:text-sm">Forever friends</p>
                            </div>
                        </div>
                        <p class="text-white/80 leading-relaxed text-sm md:text-base">
                            My fish! Now we're truly inseparable. You've become such an important part of my life, 
                            and I'm grateful for every memory we've shared. You're genuinely one of a kind, Princess.
                        </p>
                    </div>
                </div>
                
                <div class="space-y-6 md:space-y-8">
                    <div class="glass-morphism rounded-3xl p-6 md:p-8 text-center hover-lift">
                        <div class="text-4xl md:text-6xl mb-4 md:mb-6">🎂</div>
                        <h3 class="font-playfair text-2xl md:text-3xl font-semibold accent-gradient-text mb-3 md:mb-4">Send Birthday Wishes</h3>
                        <p class="text-white/70 mb-4 md:mb-6 text-sm md:text-base">Choose your preferred way to wish Princess LeighAnne a happy birthday!</p>
                        <button onclick="scrollToSection('contact')" class="modern-button text-white px-4 md:px-6 py-2 md:py-3 rounded-2xl font-medium text-sm md:text-base">
                            Send Wishes Now
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Appreciation Section -->
    <section class="section-padding">
        <div class="max-w-4xl mx-auto text-center px-4">
            <h2 class="font-playfair text-3xl md:text-5xl lg:text-6xl font-bold mb-8 md:mb-16 accent-gradient-text">
                Why You're Amazing
            </h2>
            
            <div class="glass-morphism rounded-3xl p-6 md:p-8 lg:p-12 mb-8 md:mb-12 hover-lift">
                <p class="text-lg md:text-xl lg:text-2xl text-white/90 leading-relaxed mb-6 md:mb-8">
                    Princess LeighAnne, your loving heart, genuine care, and the incredible person you've 
                    become inspires everyone around you. Your presence lights up every room you enter.
                </p>
                
                <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6 md:gap-8 mt-8 md:mt-12">
                    <div class="text-center fade-in-up stagger-1">
                        <div class="w-16 h-16 md:w-20 md:h-20 bg-gradient-to-r from-purple-500 to-pink-500 rounded-3xl flex items-center justify-center text-2xl md:text-3xl mx-auto mb-4">
                            💝
                        </div>
                        <h3 class="font-playfair text-lg md:text-xl font-semibold text-white mb-2">Caring Heart</h3>
                        <p class="text-white/70 text-sm md:text-base">Always there for friends</p>
                    </div>
                    
                    <div class="text-center fade-in-up stagger-2">
                        <div class="w-16 h-16 md:w-20 md:h-20 bg-gradient-to-r from-pink-500 to-red-500 rounded-3xl flex items-center justify-center text-2xl md:text-3xl mx-auto mb-4">
                            ✨
                        </div>
                        <h3 class="font-playfair text-lg md:text-xl font-semibold text-white mb-2">Bright Spirit</h3>
                        <p class="text-white/70 text-sm md:text-base">Brings joy to everyone</p>
                    </div>
                    
                    <div class="text-center fade-in-up stagger-3">
                        <div class="w-16 h-16 md:w-20 md:h-20 bg-gradient-to-r from-blue-500 to-purple-500 rounded-3xl flex items-center justify-center text-2xl md:text-3xl mx-auto mb-4">
                            👑
                        </div>
                        <h3 class="font-playfair text-lg md:text-xl font-semibold text-white mb-2">True Princess</h3>
                        <p class="text-white/70 text-sm md:text-base">Royal in every way</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Contact Section -->
    <section id="contact" class="section-padding">
        <div class="max-w-4xl mx-auto px-4">
            <h2 class="font-playfair text-3xl md:text-5xl lg:text-6xl font-bold text-center mb-8 md:mb-16 gradient-text">
                Send Your Birthday Wishes
            </h2>
            
            <div class="glass-morphism rounded-3xl p-6 md:p-8 lg:p-12">
                <p class="text-center text-white/80 text-lg md:text-xl mb-8 md:mb-12">
                    Choose your preferred way to send Princess LeighAnne your birthday message!
                </p>
                
                <div class="grid md:grid-cols-3 gap-6 md:gap-8">
                    <!-- WhatsApp -->
                    <a href="https://wa.me/233244680061?text=Happy%2019th%20Birthday%20Princess%20LeighAnne!%20🎉🎂%20Wishing%20you%20all%20the%20best%20on%20your%20special%20day!" 
                       target="_blank" 
                       class="contact-button whatsapp-button whatsapp-button glass-morphism rounded-2xl p-6 md:p-8 text-center hover-lift">
                        <div class="text-4xl md:text-5xl mb-4">💬</div>
                        <h3 class="font-playfair text-xl md:text-2xl font-semibold text-white mb-2">WhatsApp Message</h3>
                        <p class="text-white/70 mb-4 text-sm md:text-base">Send wishes via WhatsApp</p>
                        <div class="text-white/60 text-xs">Tap to message</div>
                    </a>
                    
                    <!-- Snapchat -->
                    <a href="https://snapchat.com/add/Far_eeda11" 
                       target="_blank" 
                       class="contact-button snapchat-button glass-morphism rounded-2xl p-6 md:p-8 text-center hover-lift">
                        <div class="text-4xl md:text-5xl mb-4">👻</div>
                        <h3 class="font-playfair text-xl md:text-2xl font-semibold text-black mb-2">Snapchat</h3>
                        <p class="text-black/70 mb-4 text-sm md:text-base font-medium">@Far_eeda11</p>
                        <div class="text-black/60 text-xs">Tap to add & message</div>
                    </a>
                    
                    <!-- Phone Call -->
                    <a href="tel:+233244680061" 
                       class="contact-button phone-button glass-morphism rounded-2xl p-6 md:p-8 text-center hover-lift">
                        <div class="text-4xl md:text-5xl mb-4">📱</div>
                        <h3 class="font-playfair text-xl md:text-2xl font-semibold text-white mb-2">Call / SMS</h3>
                        <p class="text-white/70 mb-4 text-sm md:text-base">+233 24 468 0041</p>
                        <div class="text-white/60 text-xs">Tap to call or text</div>
                    </a>
                </div>
                
                <div class="text-center mt-8 md:mt-12">
                    <p class="text-white/60 text-sm md:text-base mb-4">
                        Choose your favorite way to send Princess LeighAnne your birthday wishes!
                    </p>
                    <div class="flex justify-center space-x-2 text-xl">
                        <span class="pulse-effect">💝</span>
                        <span class="pulse-effect" style="animation-delay: 0.5s">🎉</span>
                        <span class="pulse-effect" style="animation-delay: 1s">✨</span>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="section-padding border-t border-white/10">
        <div class="max-w-4xl mx-auto text-center px-4">
            <div class="glass-morphism rounded-3xl p-6 md:p-8 mb-8">
                <h3 class="font-playfair text-2xl md:text-3xl font-bold gradient-text mb-4">
                    Happy 19th Birthday, Princess! 🎉
                </h3>
                <p class="text-white/70 mb-6 text-sm md:text-base">
                    May this special day bring you endless joy, wonderful surprises, and all the happiness your heart can hold.
                </p>
                <div class="flex justify-center space-x-2 text-xl md:text-2xl">
                    <span class="animate-pulse">🎂</span>
                    <span class="animate-pulse" style="animation-delay: 0.5s">🎈</span>
                    <span class="animate-pulse" style="animation-delay: 1s">🎁</span>
                    <span class="animate-pulse" style="animation-delay: 1.5s">✨</span>
                    <span class="animate-pulse" style="animation-delay: 2s">💕</span>
                </div>
            </div>
            
            <p class="text-white/40 text-xs md:text-sm">
                Made with 💖 for Princess LeighAnne's 19th Birthday
            </p>
            <p class="text-white/40 text-xs md:text-sm mt-2">
                Website created by Phenyl - <a href="tel:+233537872807" class="hover:text-purple-400 transition-colors">0537872807</a>
            </p>
        </div>
    </footer>
    
    <script>
        // Slideshow functionality
        let currentSlideIndex = 0;
        const slides = document.querySelectorAll('.slide');
        const dots = document.querySelectorAll('.dot');
        
        function showSlide(index) {
            slides.forEach((slide, i) => {
                slide.classList.remove('active', 'next', 'prev');
                if (i === index) {
                    slide.classList.add('active');
                } else if (i === (index + 1) % slides.length) {
                    slide.classList.add('next');
                } else if (i === (index - 1 + slides.length) % slides.length) {
                    slide.classList.add('prev');
                }
            });
            
            dots.forEach((dot, i) => {
                dot.classList.toggle('active', i === index);
            });
        }
        
        function changeSlide(direction) {
            currentSlideIndex = (currentSlideIndex + direction + slides.length) % slides.length;
            showSlide(currentSlideIndex);
        }
        
        function currentSlide(index) {
            currentSlideIndex = index - 1;
            showSlide(currentSlideIndex);
        }
        
        // Auto-advance slideshow
        setInterval(() => {
            changeSlide(1);
        }, 5000);
        
        // Scroll progress indicator
        function updateScrollIndicator() {
            const scrolled = (window.pageYOffset / (document.documentElement.scrollHeight - window.innerHeight)) * 100;
            document.getElementById('scrollIndicator').style.transform = `scaleX(${scrolled / 100})`;
        }
        
        window.addEventListener('scroll', updateScrollIndicator);
        
        // Smooth scrolling
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({
                behavior: 'smooth'
            });
        }
        
        // Timeline animation
        function checkTimelineItems() {
            const timelineItems = document.querySelectorAll('.timeline-item');
            timelineItems.forEach(item => {
                const itemTop = item.getBoundingClientRect().top;
                const windowHeight = window.innerHeight;
                
                if (itemTop < windowHeight * 0.8) {
                    item.classList.add('visible');
                }
            });
        }
        
        window.addEventListener('scroll', checkTimelineItems);
        checkTimelineItems(); // Check on load
        
        // Floating particles
        function createParticles() {
            const container = document.getElementById('particles-container');
            
            setInterval(() => {
                const particle = document.createElement('div');
                particle.className = 'particle';
                particle.style.left = Math.random() * 100 + '%';
                particle.style.animationDuration = (Math.random() * 2 + 3) + 's';
                
                container.appendChild(particle);
                
                setTimeout(() => {
                    if (particle.parentNode) {
                        particle.parentNode.removeChild(particle);
                    }
                }, 4000);
            }, 2000);
        }
        
        // Initialize particles
        createParticles();
        
        // Initialize animations on load
        window.addEventListener('load', function() {
            // Trigger initial animations
            setTimeout(() => {
                document.querySelectorAll('.fade-in-up').forEach(element => {
                    element.style.opacity = '1';
                    element.style.transform = 'translateY(0)';
                });
            }, 500);
        });
        
        // Keyboard navigation for slideshow
        document.addEventListener('keydown', function(e) {
            if (e.key === 'ArrowLeft') {
                changeSlide(-1);
            } else if (e.key === 'ArrowRight') {
                changeSlide(1);
            }
        });
        
        // Touch/swipe support for slideshow
        let touchStartX = 0;
        let touchEndX = 0;
        
        document.querySelector('.slideshow-container').addEventListener('touchstart', function(e) {
            touchStartX = e.changedTouches[0].screenX;
        });
        
        document.querySelector('.slideshow-container').addEventListener('touchend', function(e) {
            touchEndX = e.changedTouches[0].screenX;
            handleSwipe();
        });
        
        function handleSwipe() {
            if (touchEndX < touchStartX - 50) {
                changeSlide(1); // Swipe left, go to next slide
            }
            if (touchEndX > touchStartX + 50) {
                changeSlide(-1); // Swipe right, go to previous slide
            }
        }
        
        // Add click feedback for contact buttons
        document.querySelectorAll('.contact-button').forEach(button => {
            button.addEventListener('click', function() {
                // Add ripple effect
                const ripple = document.createElement('div');
                ripple.style.position = 'absolute';
                ripple.style.borderRadius = '50%';
                ripple.style.background = 'rgba(255, 255, 255, 0.3)';
                ripple.style.transform = 'scale(0)';
                ripple.style.animation = 'ripple 0.6s linear';
                ripple.style.left = '50%';
                ripple.style.top = '50%';
                ripple.style.marginLeft = '-25px';
                ripple.style.marginTop = '-25px';
                ripple.style.width = '50px';
                ripple.style.height = '50px';
                ripple.style.pointerEvents = 'none';
                
                this.style.position = 'relative';
                this.appendChild(ripple);
                
                setTimeout(() => {
                    if (ripple.parentNode) {
                        ripple.parentNode.removeChild(ripple);
                    }
                }, 600);
            });
        });
        
        // Lazy loading for images
        if ('IntersectionObserver' in window) {
            const imageObserver = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        const img = entry.target;
                        if (img.dataset.src) {
                            img.src = img.dataset.src;
                            img.classList.remove('lazy');
                            imageObserver.unobserve(img);
                        }
                    }
                });
            });
            
            document.querySelectorAll('img[data-src]').forEach(img => {
                imageObserver.observe(img);
            });
        }
        
        // Add entrance animations for contact buttons
        function animateContactButtons() {
            const contactButtons = document.querySelectorAll('.contact-button');
            contactButtons.forEach((button, index) => {
                button.style.opacity = '0';
                button.style.transform = 'translateY(30px)';
                
                setTimeout(() => {
                    button.style.transition = 'all 0.6s ease-out';
                    button.style.opacity = '1';
                    button.style.transform = 'translateY(0)';
                }, index * 200);
            });
        }
        
        // Trigger contact button animations when section comes into view
        const contactSection = document.getElementById('contact');
        if (contactSection) {
            const contactObserver = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        animateContactButtons();
                        contactObserver.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.3 });
            
            contactObserver.observe(contactSection);
        }
    </script>
</body>
</html>    h2{margin:6px 0 18px;color:var(--accent);font-weight:600}
    .hero{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:22px;border-radius:16px;box-shadow:0 6px 30px rgba(2,6,23,0.6)}
    .dates{color:var(--muted);margin-bottom:14px}
    .btn{display:inline-block;padding:10px 16px;border-radius:10px;background:#111827;color:#fff;text-decoration:none;font-weight:600;box-shadow:0 6px 18px rgba(0,0,0,0.4)}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:18px}
    .card{background:rgba(255,255,255,0.03);padding:12px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .card img{width:100%;height:160px;object-fit:cover;border-radius:8px}
    .section{margin-top:22px}
    .muted{color:var(--muted)}
    footer{margin-top:28px;color:var(--muted);font-size:14px}
    .contact a{display:inline-block;margin-right:8px;padding:8px 12px;border-radius:10px;background:rgba(255,255,255,0.02);text-decoration:none;color:#fff}
    .upload{display:inline-flex;align-items:center;gap:10px}
    @media (max-width:520px){h1{font-size:28px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="sparkle">✨</div>
      <div>
        <h1>Princess</h1>
        <h2>LeighAnne</h2>
      </div>
    </header><main class="hero">
  <p><strong>Celebrating 19 Years of Amazing</strong></p>
  <p class="dates">September 11, 2006 → September 11, 2025</p>
  <a class="btn" href="#gallery">View Photo Memories</a>

  <div class="section" id="gallery">
    <h3>Beautiful Memories</h3>
    <div class="grid">
      <!-- placeholder images; replace src with real pictures -->
      <div class="card"><img src="https://picsum.photos/seed/leigh1/800/600" alt="Birthday memory 1"><h4>Princess LeighAnne</h4><p class="muted">Add your beautiful birthday photos here!</p></div>
      <div class="card"><img src="https://picsum.photos/seed/leigh2/800/600" alt="Birthday memory 2"><h4>Special Moments</h4><p class="muted">Celebrating 19 amazing years!</p></div>
      <div class="card"><img src="https://picsum.photos/seed/leigh3/800/600" alt="Birthday memory 3"><h4>Princess Moments</h4><p class="muted">Every moment is special with you</p></div>
      <div class="card"><img src="https://picsum.photos/seed/leigh4/800/600" alt="Birthday memory 4"><h4>Princess Moments</h4><p class="muted">Every moment is special with you</p></div>
    </div>

    <p class="muted" style="margin-top:12px">Upload your favorite photos of Princess LeighAnne to create a personalized slideshow!</p>
    <form class="upload" onsubmit="event.preventDefault();alert('Upload feature is a placeholder in this demo. Replace with a server endpoint or storage provider.');">
      <input type="file" accept="image/*" />
      <button class="btn">Upload Photos</button>
    </form>
  </div>

  <div class="section">
    <h3>Our Journey Together</h3>
    <p class="muted"><strong>Achimota Beginnings</strong><br>Where it all started — from those early days at Achimota School when we were just getting to know each other. Little did we know this would blossom into such a beautiful friendship.</p>

    <h4>Growing Connection</h4>
    <p>Building trust & love — Princess, I never imagined writing birthday codes for you back then! But here we are — calling each other during tough times, celebrating together, proving what real friendship means.<br><em>~ With love, Afia</em></p>

    <h4>Unbreakable Bond</h4>
    <p>Forever friends — My fish! You're genuinely one of a kind.</p>
  </div>

  <div class="section">
    <h3>Send Birthday Wishes</h3>
    <p class="muted">Choose your preferred way to wish Princess LeighAnne a happy birthday!</p>
    <div class="contact">
      <a href="https://wa.me/233244680041" target="_blank" rel="noopener">WhatsApp Message</a>
      <a href="https://snapchat.com/add/Far_eeda11" target="_blank" rel="noopener">Snapchat</a>
      <a href="tel:+233244680041">Call / SMS</a>
    </div>
  </div>

  <div class="section">
    <h3>Why You're Amazing</h3>
    <p class="muted">Princess LeighAnne, your loving heart, genuine care, and the incredible person you've become inspires everyone around you. Your presence lights up every room you enter.</p>
    <div class="grid" style="margin-top:10px">
      <div class="card"><h4>Caring Heart</h4><p class="muted">Always there for friends</p></div>
      <div class="card"><h4>Bright Spirit</h4><p class="muted">Brings joy to everyone</p></div>
      <div class="card"><h4>True Princess</h4><p class="muted">Royal in every way</p></div>
    </div>
  </div>

  <footer>
    <h3>Happy 19th Birthday, Princess!</h3>
    <p class="muted">May this special day bring you endless joy, wonderful surprises, and all the happiness your heart can hold. ✨</p>
    <p class="muted">Made with ❤️ for Princess LeighAnne's 19th Birthday
  </footer>

</main>

  </div>  <script>
    // small JS: simple lightbox for gallery images
    document.querySelectorAll('.card img').forEach(img => {
      img.style.cursor = 'pointer';
      img.addEventListener('click', ()=>{
        const overlay = document.createElement('div');
        overlay.style.position='fixed';overlay.style.left=0;overlay.style.top=0;overlay.style.width='100%';overlay.style.height='100%';overlay.style.background='rgba(0,0,0,0.8)';overlay.style.display='flex';overlay.style.alignItems='center';overlay.style.justifyContent='center';overlay.style.zIndex=9999
        const big = document.createElement('img');big.src=img.src;big.style.maxWidth='92%';big.style.maxHeight='92%';big.style.borderRadius='10px'
        overlay.appendChild(big);
        overlay.addEventListener('click', ()=>overlay.remove());
        document.body.appendChild(overlay);
      })
    })
  </script></body>
</html>
