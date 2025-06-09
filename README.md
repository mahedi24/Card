<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Md Mahedi Hasan – Animated Contact Card</title>
  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- 🔧 Tailwind custom keyframes & animations -->
  <script>
    tailwind.config = {
      theme: {
        extend: {
          keyframes: {
            slideInLeft: {
              '0%': { transform: 'translateX(-80px)', opacity: '0' },
              '100%': { transform: 'translateX(0)', opacity: '1' }
            },
            slideInRight: {
              '0%': { transform: 'translateX(80px)', opacity: '0' },
              '100%': { transform: 'translateX(0)', opacity: '1' }
            },
            slideInUp: {
              '0%': { transform: 'translateY(80px)', opacity: '0' },
              '100%': { transform: 'translateY(0)', opacity: '1' }
            }
          },
          animation: {
            'slide-in-left': 'slideInLeft 0.8s ease-out forwards',
            'slide-in-right': 'slideInRight 0.8s ease-out forwards',
            'slide-in-up': 'slideInUp 0.8s ease-out forwards'
          }
        }
      }
    }
  </script>
</head>
<body class="bg-[#0D1117] text-[#129CFF] min-h-screen flex items-center justify-center px-4 pb-24">
  <div class="bg-[#0D1117] p-6 rounded-2xl max-w-md w-full shadow-lg space-y-6">
    <!-- 🌟 Profile Section -->
    <div class="flex flex-col items-center space-y-4 opacity-0 animate-slide-in-left" style="animation-delay:0.2s">
      <img src="Phone/Pictures/Photoroom/Photoroom-20250608_205903.png" alt="Profile" class="w-24 h-24 rounded-full object-cover border-4 border-[#129CFF] shadow" />
      <div class="text-center">
        <h2 class="text-xl font-bold text-white">Md Mahedi Hasan</h2>
        <p class="text-sm text-[#129CFF]">Web Developer</p>
      </div>
    </div><!-- 🌟 About Me Heading -->
<h3 class="text-xl font-bold text-[#2dd4bf] text-center tracking-widest uppercase opacity-0 animate-slide-in-right" style="animation-delay:0.5s">About Me</h3>
<!-- 🌟 About Me Description -->
<div class="bg-[#101b26] rounded-xl px-4 py-3 text-sm text-[#CBD5E1] opacity-0 animate-slide-in-left" style="animation-delay:0.7s">
  I'm a passionate Web Developer with expertise in front-end and back-end development. I specialize in building responsive, user‑friendly websites using modern technologies. With a strong eye for detail and a problem‑solving mindset, I aim to create clean and efficient digital experiences.
</div>
<!-- 🌟 Web Development Block -->
<div class="flex flex-col items-center opacity-0 animate-slide-in-right" style="animation-delay:0.9s">
  <img src="codevaly_logo_big.png" alt="Codevaly Logo" class="w-32 md:w-40 lg:w-48 object-contain select-none" />
  <p class="mt-2 text-base md:text-lg font-semibold text-white tracking-wide">WEB DEVELOPMENT</p>
</div>
<!-- 🌟 UI/UX Design Block -->
<div class="flex flex-col items-center opacity-0 animate-slide-in-left" style="animation-delay:1.1s">
  <img src="uiux_design_image.png" alt="UI/UX Design" class="w-44 md:w-56 lg:w-64 object-contain rounded-xl shadow-lg select-none" />
  <p class="mt-2 text-base md:text-lg font-semibold text-[#38bdf8] tracking-wide">UI/UX DESIGN</p>
</div>
<!-- 🌟 Contact Info Cards -->
<div class="space-y-4">
  <div class="flex items-center space-x-3 bg-[#101b26] px-4 py-3 rounded-xl opacity-0 animate-slide-in-left" style="animation-delay:1.3s">
    <img src="phone_icon.png" class="w-5 h-5" alt="Phone" />
    <p class="text-sm">+880 1849402692</p>
  </div>
  <div class="flex items-center space-x-3 bg-[#101b26] px-4 py-3 rounded-xl opacity-0 animate-slide-in-right" style="animation-delay:1.5s">
    <img src="email_icon.png" class="w-5 h-5" alt="Email" />
    <p class="text-sm">hmmahedi550@gmail.com</p>
  </div>
  <div class="flex items-center space-x-3 bg-[#101b26] px-4 py-3 rounded-xl opacity-0 animate-slide-in-left" style="animation-delay:1.7s">
    <img src="facebook_icon.png" class="w-5 h-5" alt="Facebook" />
    <p class="text-sm">facebook.com/share/1LWomy2hmY</p>
  </div>
</div>
  </div>  <!-- 🌟 Bottom Contact Bar (fixed) -->  <div class="fixed bottom-4 left-4 right-4 mx-auto max-w-md bg-white/5 border border-white/10 backdrop-blur-lg rounded-2xl px-6 py-3 flex items-center justify-between z-50 shadow-xl opacity-0 animate-slide-in-up" style="animation-delay:2s">
    <!-- WhatsApp -->
    <a href="https://wa.me/8801927210678" target="_blank" class="flex items-center space-x-2 text-white hover:text-[#25D366] transition">
      <img src="whatsapp_icon.png" alt="WhatsApp" class="w-5 h-5" />
      <span class="font-semibold text-sm">CHAT</span>
    </a><!-- Center Logo -->
<img src="your_new_logo.png" alt="Logo" class="w-8 h-8 select-none" />
<!-- Email -->
<a href="mailto:hmmahedi550@gmail.com" class="flex items-center space-x-2 text-white hover:text-[#129CFF] transition">
  <span class="font-semibold text-sm">MAIL</span>
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
    <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25H4.5a2.25 2.25 0 01-2.25-2.25V6.75M21.75 6.75L12 13.5 2.25 6.75M21.75 6.75H2.25" />
  </svg>
</a>
  </div>
</body>
</html>
