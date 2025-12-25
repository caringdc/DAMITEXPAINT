# DAMITEXPAINT
<!doctype html>
<html lang="en" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Paint Company Website</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <style>
    body {
      box-sizing: border-box;
    }
    
    .smooth-scroll {
      scroll-behavior: smooth;
    }
    
    .hero-pattern {
      background-image: 
        linear-gradient(135deg, rgba(255, 255, 255, 0.1) 25%, transparent 25%),
        linear-gradient(225deg, rgba(255, 255, 255, 0.1) 25%, transparent 25%),
        linear-gradient(45deg, rgba(255, 255, 255, 0.1) 25%, transparent 25%),
        linear-gradient(315deg, rgba(255, 255, 255, 0.1) 25%, transparent 25%);
      background-size: 60px 60px;
      background-position: 0 0, 30px 0, 30px -30px, 0 30px;
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full smooth-scroll">
  <div id="app-wrapper" class="w-full h-full overflow-auto"><!-- Navigation -->
   <nav id="navbar" class="fixed w-full top-0 z-50 transition-all duration-300">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
     <div>
      <h1 id="nav-company-name" class="text-2xl font-bold"></h1>
      <p id="nav-tagline" class="text-sm opacity-90"></p>
     </div>
     <div class="hidden md:flex gap-8"><a href="#services" class="hover:opacity-80 transition-opacity font-medium">Services</a> <a href="#about" class="hover:opacity-80 transition-opacity font-medium">About</a> <a href="#contact" class="hover:opacity-80 transition-opacity font-medium">Contact</a>
     </div><button id="mobile-menu-btn" class="md:hidden p-2">
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
      </svg></button>
    </div>
    <div id="mobile-menu" class="hidden md:hidden px-6 pb-4"><a href="#services" class="block py-2 hover:opacity-80 transition-opacity">Services</a> <a href="#about" class="block py-2 hover:opacity-80 transition-opacity">About</a> <a href="#contact" class="block py-2 hover:opacity-80 transition-opacity">Contact</a>
    </div>
   </nav><!-- Hero Section -->
   <section id="hero" class="min-h-screen flex items-center pt-20 hero-pattern">
    <div class="max-w-7xl mx-auto px-6 py-20 text-center">
     <h2 id="hero-headline" class="text-5xl md:text-7xl font-bold mb-6"></h2>
     <p id="hero-subheading" class="text-xl md:text-2xl mb-8 opacity-90 max-w-3xl mx-auto"></p><button id="cta-button" class="px-8 py-4 rounded-lg text-lg font-semibold shadow-lg hover:shadow-xl transform hover:scale-105 transition-all duration-300"></button>
    </div>
   </section><!-- Services Section -->
   <section id="services" class="py-20">
    <div class="max-w-7xl mx-auto px-6">
     <h2 id="services-title" class="text-4xl md:text-5xl font-bold text-center mb-16"></h2>
     <div class="grid md:grid-cols-3 gap-8">
      <div id="service-1" class="p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow"><img src="https://i.ibb.co/ynNwRw2c/21e769a79fce4bc1ae4c96d399e140f5.jpg" alt="Gravitex Acrylic Paint" class="w-full h-48 object-cover rounded-lg mb-4" onerror="this.style.display='none';">
       <h3 id="service-1-title" class="text-2xl font-bold mb-4"></h3>
       <p id="service-1-description" class="opacity-80"></p>
      </div>
      <div id="service-2" class="p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow"><img src="https://i.ibb.co/RGssRjYL/8a9717044a46a566f3ecd2acf18f5b5c.jpg" alt="Matt Paint" class="w-full h-48 object-cover rounded-lg mb-4" onerror="this.style.display='none';">
       <h3 id="service-2-title" class="text-2xl font-bold mb-4"></h3>
       <p id="service-2-description" class="opacity-80"></p>
      </div>
      <div id="service-3" class="p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow"><img src="https://i.ibb.co/vvZ2wL6B/0bb5fc13c81048ec69e2bd67de8ade82.jpg" alt="Emulsion Paint" class="w-full h-48 object-cover rounded-lg mb-4" onerror="this.style.display='none';">
       <h3 id="service-3-title" class="text-2xl font-bold mb-4"></h3>
       <p id="service-3-description" class="opacity-80"></p>
      </div>
      <div id="service-4" class="p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow"><img src="https://i.ibb.co/gLx4bV94/095a6806df5ba8ea9fb8ebce85506911.jpg" alt="Satin Paint" class="w-full h-48 object-cover rounded-lg mb-4" onerror="this.style.display='none';">
       <h3 id="service-4-title" class="text-2xl font-bold mb-4"></h3>
       <p id="service-4-description" class="opacity-80"></p>
      </div>
      <div id="service-5" class="p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow"><img src="https://i.ibb.co/Gq5SJGc/1ae537609d3584b79e94a40c1451b343.jpg" alt="Texcoat Paint" class="w-full h-48 object-cover rounded-lg mb-4" onerror="this.style.display='none';">
       <h3 id="service-5-title" class="text-2xl font-bold mb-4"></h3>
       <p id="service-5-description" class="opacity-80"></p>
      </div>
      <div id="service-6" class="p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow"><img src="https://i.ibb.co/ZRBtrVv2/5686e76aec8c4ebdf0079bd7e0d514f2.jpg" alt="Marble Paint" class="w-full h-48 object-cover rounded-lg mb-4" onerror="this.style.display='none';">
       <h3 id="service-6-title" class="text-2xl font-bold mb-4"></h3>
       <p id="service-6-description" class="opacity-80"></p>
      </div>
     </div>
    </div>
   </section><!-- About Section -->
   <section id="about" class="py-20">
    <div class="max-w-7xl mx-auto px-6">
     <div class="grid md:grid-cols-2 gap-12 items-center">
      <div>
       <h2 id="about-title" class="text-4xl md:text-5xl font-bold mb-6"></h2>
       <p id="about-description" class="text-lg opacity-80 leading-relaxed"></p>
      </div>
      <div class="rounded-xl p-12 flex items-center justify-center">
       <svg class="w-full h-64" viewbox="0 0 200 200" fill="none"><rect x="20" y="60" width="40" height="120" rx="4" fill="currentColor" opacity="0.8" /> <rect x="70" y="40" width="40" height="140" rx="4" fill="currentColor" opacity="0.6" /> <rect x="120" y="80" width="40" height="100" rx="4" fill="currentColor" opacity="0.9" /> <circle cx="40" cy="50" r="8" fill="currentColor" /> <circle cx="90" cy="30" r="8" fill="currentColor" /> <circle cx="140" cy="70" r="8" fill="currentColor" />
       </svg>
      </div>
     </div>
    </div>
   </section><!-- Contact Section -->
   <section id="contact" class="py-20">
    <div class="max-w-4xl mx-auto px-6 text-center">
     <h2 id="contact-title" class="text-4xl md:text-5xl font-bold mb-6"></h2>
     <p id="contact-description" class="text-lg opacity-80 mb-12"></p>
     <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6"><a href="https://wa.me/2348012345678" target="_blank" rel="noopener noreferrer" class="p-6 rounded-xl hover:shadow-lg transition-shadow cursor-pointer">
       <div class="text-4xl mb-3">
        💬
       </div><h3 class="font-semibold mb-2">WhatsApp</h3><p class="opacity-80 text-sm">Chat with us for quotes</p></a> <a href="tel:+2348012345678" class="p-6 rounded-xl hover:shadow-lg transition-shadow cursor-pointer">
       <div class="text-4xl mb-3">
        📞
       </div><h3 class="font-semibold mb-2">Phone</h3><p class="opacity-80 text-sm">+234 801 234 5678</p></a>
      <div class="p-6 rounded-xl">
       <div class="text-4xl mb-3">
        ✉️
       </div>
       <h3 class="font-semibold mb-2">Email</h3>
       <p class="opacity-80 text-sm">damitexpaints@gmail.com</p>
      </div>
      <div class="p-6 rounded-xl">
       <div class="text-4xl mb-3">
        📍
       </div>
       <h3 class="font-semibold mb-2">Locations</h3>
       <p class="opacity-80 text-sm">Dei-Dei, Abuja<br>
        Ikorodu, Lagos</p>
      </div>
     </div>
    </div>
   </section><!-- Footer -->
   <footer id="footer" class="py-8 border-t">
    <div class="max-w-7xl mx-auto px-6 text-center">
     <p id="footer-text" class="opacity-70"></p>
    </div>
   </footer>
  </div>
  <script>
    const defaultConfig = {
      background_color: "#1e3a8a",
      surface_color: "#ffffff",
      text_color: "#1f2937",
      primary_action_color: "#3b82f6",
      secondary_action_color: "#60a5fa",
      font_family: "Inter",
      font_size: 16,
      company_name: "DAMITEXPAINT",
      tagline: "Quality Paint Solutions for Nigeria",
      hero_headline: "Premium Paint Products for Every Surface",
      hero_subheading: "Specializing in Gravitex Acrylic, Matt, Emulsion, Satin, Texcoat, Marble and more quality paints",
      cta_button: "Get Free Quote",
      services_title: "Our Services",
      service_1_title: "Gravitex Acrylic Paint",
      service_1_description: "Premium acrylic paint with excellent coverage and durability for all surfaces.",
      service_2_title: "Matt Paint",
      service_2_description: "Smooth, non-reflective finish perfect for walls and ceilings in any room.",
      service_3_title: "Emulsion Paint",
      service_3_description: "Water-based paint ideal for interior walls with quick drying properties.",
      service_4_title: "Satin Paint",
      service_4_description: "Elegant semi-gloss finish that's easy to clean and maintain.",
      service_5_title: "Texcoat Paint",
      service_5_description: "Textured coating for beautiful exterior and interior decorative finishes.",
      service_6_title: "Marble Paint",
      service_6_description: "Luxurious marble-effect paint for stunning decorative finishes and elegant surfaces.",
      about_title: "About DAMITEXPAINT",
      about_description: "We are your trusted paint supplier in Nigeria, serving clients in Abuja and Lagos. We specialize in premium quality paints including Gravitex Acrylic, Matt Paint, Emulsion Paint, Satin Paint, Texcoat Paint, Marble Paint and many more. Contact us for competitive quotes and professional service.",
      contact_title: "Get Your Quote Today",
      contact_description: "Contact us via WhatsApp, phone call, or email for competitive quotations on all our paint products.",
      footer_text: "© 2024 DAMITEXPAINT. Serving Dei-Dei Abuja & Ikorodu Lagos, Nigeria"
    };

    async function onConfigChange(config) {
      const fontFamily = config.font_family || defaultConfig.font_family;
      const fontSize = config.font_size || defaultConfig.font_size;
      const baseFontStack = 'system-ui, -apple-system, sans-serif';

      // Apply colors
      const navbar = document.getElementById('navbar');
      navbar.style.background = config.background_color || defaultConfig.background_color;
      navbar.style.color = config.surface_color || defaultConfig.surface_color;

      const hero = document.getElementById('hero');
      hero.style.background = config.background_color || defaultConfig.background_color;
      hero.style.color = config.surface_color || defaultConfig.surface_color;

      const appWrapper = document.getElementById('app-wrapper');
      appWrapper.style.background = config.surface_color || defaultConfig.surface_color;
      appWrapper.style.color = config.text_color || defaultConfig.text_color;

      const ctaButton = document.getElementById('cta-button');
      ctaButton.style.background = config.primary_action_color || defaultConfig.primary_action_color;
      ctaButton.style.color = config.surface_color || defaultConfig.surface_color;

      const services = document.querySelectorAll('[id^="service-"]');
      services.forEach(service => {
        if (service.id.includes('title') || service.id.includes('description')) return;
        service.style.background = config.surface_color || defaultConfig.surface_color;
        service.style.borderColor = config.secondary_action_color || defaultConfig.secondary_action_color;
        service.style.borderWidth = '2px';
      });

      const footer = document.getElementById('footer');
      footer.style.borderColor = config.secondary_action_color || defaultConfig.secondary_action_color;

      // Apply fonts
      document.body.style.fontFamily = `${fontFamily}, ${baseFontStack}`;

      // Apply font sizes
      document.getElementById('nav-company-name').style.fontSize = `${fontSize * 1.5}px`;
      document.getElementById('nav-tagline').style.fontSize = `${fontSize * 0.875}px`;
      document.getElementById('hero-headline').style.fontSize = `${fontSize * 3.5}px`;
      document.getElementById('hero-subheading').style.fontSize = `${fontSize * 1.25}px`;
      document.getElementById('cta-button').style.fontSize = `${fontSize * 1.125}px`;
      document.getElementById('services-title').style.fontSize = `${fontSize * 2.5}px`;
      document.getElementById('about-title').style.fontSize = `${fontSize * 2.5}px`;
      document.getElementById('contact-title').style.fontSize = `${fontSize * 2.5}px`;
      
      const serviceTitles = document.querySelectorAll('[id$="-title"]');
      serviceTitles.forEach(title => {
        if (title.id.includes('service-')) {
          title.style.fontSize = `${fontSize * 1.5}px`;
        }
      });

      const serviceDescriptions = document.querySelectorAll('[id$="-description"]');
      serviceDescriptions.forEach(desc => {
        if (desc.id.includes('service-')) {
          desc.style.fontSize = `${fontSize}px`;
        }
      });

      // Update text content
      document.getElementById('nav-company-name').textContent = config.company_name || defaultConfig.company_name;
      document.getElementById('nav-tagline').textContent = config.tagline || defaultConfig.tagline;
      document.getElementById('hero-headline').textContent = config.hero_headline || defaultConfig.hero_headline;
      document.getElementById('hero-subheading').textContent = config.hero_subheading || defaultConfig.hero_subheading;
      document.getElementById('cta-button').textContent = config.cta_button || defaultConfig.cta_button;
      document.getElementById('services-title').textContent = config.services_title || defaultConfig.services_title;
      document.getElementById('service-1-title').textContent = config.service_1_title || defaultConfig.service_1_title;
      document.getElementById('service-1-description').textContent = config.service_1_description || defaultConfig.service_1_description;
      document.getElementById('service-2-title').textContent = config.service_2_title || defaultConfig.service_2_title;
      document.getElementById('service-2-description').textContent = config.service_2_description || defaultConfig.service_2_description;
      document.getElementById('service-3-title').textContent = config.service_3_title || defaultConfig.service_3_title;
      document.getElementById('service-3-description').textContent = config.service_3_description || defaultConfig.service_3_description;
      document.getElementById('service-4-title').textContent = config.service_4_title || defaultConfig.service_4_title;
      document.getElementById('service-4-description').textContent = config.service_4_description || defaultConfig.service_4_description;
      document.getElementById('service-5-title').textContent = config.service_5_title || defaultConfig.service_5_title;
      document.getElementById('service-5-description').textContent = config.service_5_description || defaultConfig.service_5_description;
      document.getElementById('service-6-title').textContent = config.service_6_title || defaultConfig.service_6_title;
      document.getElementById('service-6-description').textContent = config.service_6_description || defaultConfig.service_6_description;
      document.getElementById('about-title').textContent = config.about_title || defaultConfig.about_title;
      document.getElementById('about-description').textContent = config.about_description || defaultConfig.about_description;
      document.getElementById('contact-title').textContent = config.contact_title || defaultConfig.contact_title;
      document.getElementById('contact-description').textContent = config.contact_description || defaultConfig.contact_description;
      document.getElementById('footer-text').textContent = config.footer_text || defaultConfig.footer_text;
    }

    function mapToCapabilities(config) {
      return {
        recolorables: [
          {
            get: () => config.background_color || defaultConfig.background_color,
            set: (value) => {
              config.background_color = value;
              window.elementSdk.setConfig({ background_color: value });
            }
          },
          {
            get: () => config.surface_color || defaultConfig.surface_color,
            set: (value) => {
              config.surface_color = value;
              window.elementSdk.setConfig({ surface_color: value });
            }
          },
          {
            get: () => config.text_color || defaultConfig.text_color,
            set: (value) => {
              config.text_color = value;
              window.elementSdk.setConfig({ text_color: value });
            }
          },
          {
            get: () => config.primary_action_color || defaultConfig.primary_action_color,
            set: (value) => {
              config.primary_action_color = value;
              window.elementSdk.setConfig({ primary_action_color: value });
            }
          },
          {
            get: () => config.secondary_action_color || defaultConfig.secondary_action_color,
            set: (value) => {
              config.secondary_action_color = value;
              window.elementSdk.setConfig({ secondary_action_color: value });
            }
          }
        ],
        borderables: [],
        fontEditable: {
          get: () => config.font_family || defaultConfig.font_family,
          set: (value) => {
            config.font_family = value;
            window.elementSdk.setConfig({ font_family: value });
          }
        },
        fontSizeable: {
          get: () => config.font_size || defaultConfig.font_size,
          set: (value) => {
            config.font_size = value;
            window.elementSdk.setConfig({ font_size: value });
          }
        }
      };
    }

    function mapToEditPanelValues(config) {
      return new Map([
        ["company_name", config.company_name || defaultConfig.company_name],
        ["tagline", config.tagline || defaultConfig.tagline],
        ["hero_headline", config.hero_headline || defaultConfig.hero_headline],
        ["hero_subheading", config.hero_subheading || defaultConfig.hero_subheading],
        ["cta_button", config.cta_button || defaultConfig.cta_button],
        ["services_title", config.services_title || defaultConfig.services_title],
        ["service_1_title", config.service_1_title || defaultConfig.service_1_title],
        ["service_1_description", config.service_1_description || defaultConfig.service_1_description],
        ["service_2_title", config.service_2_title || defaultConfig.service_2_title],
        ["service_2_description", config.service_2_description || defaultConfig.service_2_description],
        ["service_3_title", config.service_3_title || defaultConfig.service_3_title],
        ["service_3_description", config.service_3_description || defaultConfig.service_3_description],
        ["service_4_title", config.service_4_title || defaultConfig.service_4_title],
        ["service_4_description", config.service_4_description || defaultConfig.service_4_description],
        ["service_5_title", config.service_5_title || defaultConfig.service_5_title],
        ["service_5_description", config.service_5_description || defaultConfig.service_5_description],
        ["service_6_title", config.service_6_title || defaultConfig.service_6_title],
        ["service_6_description", config.service_6_description || defaultConfig.service_6_description],
        ["about_title", config.about_title || defaultConfig.about_title],
        ["about_description", config.about_description || defaultConfig.about_description],
        ["contact_title", config.contact_title || defaultConfig.contact_title],
        ["contact_description", config.contact_description || defaultConfig.contact_description],
        ["footer_text", config.footer_text || defaultConfig.footer_text]
      ]);
    }

    // Mobile menu functionality
    document.getElementById('mobile-menu-btn').addEventListener('click', () => {
      const menu = document.getElementById('mobile-menu');
      menu.classList.toggle('hidden');
    });

    // Smooth scroll for navigation links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({ behavior: 'smooth' });
          document.getElementById('mobile-menu').classList.add('hidden');
        }
      });
    });

    // CTA button action
    document.getElementById('cta-button').addEventListener('click', () => {
      document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
    });

    // Initialize SDK
    window.elementSdk.init({
      defaultConfig,
      onConfigChange,
      mapToCapabilities,
      mapToEditPanelValues
    });
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9b39024d04ea8560',t:'MTc2NjY3MjczOS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
