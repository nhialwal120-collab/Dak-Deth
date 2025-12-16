<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dak Dey Tut - Legacy Website</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .timeline-dot { width: 1rem; height: 1rem; border-radius: 50%; background-color: #16a34a; display: inline-block; }
    .map-location { cursor: pointer; transition: transform 0.2s; }
    .map-location:hover { transform: scale(1.2); }
  </style>
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

  <!-- Hero Section -->
  <section class="bg-green-800 text-white py-24 px-6 text-center">
    <h1 class="text-5xl font-bold mb-4">Dak Dey Tut</h1>
    <p class="text-xl mb-8">Father of Education, Governance, and Freedom in South Sudan</p>
    <p class="max-w-2xl mx-auto">The first South Sudanese to receive formal education in Khartoum, visionary leader, anti-colonial hero, and founder of modern governance in South Sudan.</p>
  </section>

  <!-- Quick Facts -->
  <section class="py-12 px-6 max-w-6xl mx-auto grid md:grid-cols-3 gap-8">
    <div class="bg-white p-6 rounded-xl shadow-lg text-center">
      <h3 class="text-xl font-semibold mb-2">Born</h3>
      <p>Early 1900s</p>
    </div>
    <div class="bg-white p-6 rounded-xl shadow-lg text-center">
      <h3 class="text-xl font-semibold mb-2">Clan</h3>
      <p>Lou Nuer</p>
    </div>
    <div class="bg-white p-6 rounded-xl shadow-lg text-center">
      <h3 class="text-xl font-semibold mb-2">Key Roles</h3>
      <p>Educator, Translator, Politician, Anti-Colonial Leader, Environmental Advocate</p>
    </div>
  </section>

  <!-- Early Life -->
  <section class="py-12 px-6 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold mb-6">Early Life</h2>
    <p>Dak Dey Tut was born to <strong>Otong Tut</strong> and <strong>Joy Tiap</strong>. After his father’s death, he was raised by his uncle <strong>Dey Tut</strong> according to Nuer cultural traditions and became known as <strong>Dak Deth</strong>. His siblings include Gai Otoang, Reath Otoang, Puot Otoang, Nyadualdaap Otoang, Nyatuoruok Otoang, among others.</p>
    <p class="mt-4">He was the first South Sudanese to attend formal schooling in <strong>Khartoum</strong> in the early 1900s, laying the foundation for his lifelong advocacy for education and independence.</p>
  </section>

  <!-- Education & Governance -->
  <section class="py-12 px-6 bg-gray-100">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold mb-6">Education & Governance</h2>
      <ul class="list-disc list-inside space-y-2">
        <li>Opened the first school in South Sudan.</li>
        <li>Introduced the first governmental forms.</li>
        <li>Created a money exchange system called <strong>Yiow</strong>.</li>
        <li>Served as a translator and advisor bridging communities.</li>
        <li>Advocated that education must lead to independence.</li>
      </ul>
    </div>
  </section>

  <!-- Interactive Timeline -->
  <section class="py-12 px-6 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold mb-6">Timeline</h2>
    <div class="space-y-8">
      <div class="flex items-center space-x-4">
        <div class="timeline-dot"></div>
        <div>
          <h3 class="font-semibold">Early 1900s</h3>
          <p>Born in Lou Nuer clan, South Sudan.</p>
        </div>
      </div>
      <div class="flex items-center space-x-4">
        <div class="timeline-dot"></div>
        <div>
          <h3 class="font-semibold">1910s–1920s</h3>
          <p>Attended formal schooling in Khartoum.</p>
        </div>
      </div>
      <div class="flex items-center space-x-4">
        <div class="timeline-dot"></div>
        <div>
          <h3 class="font-semibold">1930s</h3>
          <p>Opened the first school in South Sudan.</p>
        </div>
      </div>
      <div class="flex items-center space-x-4">
        <div class="timeline-dot"></div>
        <div>
          <h3 class="font-semibold">1940s–1950s</h3>
          <p>Introduced governance forms, money system, and anti-colonial leadership.</p>
        </div>
      </div>
      <div class="flex items-center space-x-4">
        <div class="timeline-dot"></div>
        <div>
          <h3 class="font-semibold">1950s–1960s</h3>
          <p>Environmental advocacy: Neem plantations and anti-deforestation campaigns.</p>
        </div>
      </div>
      <div class="flex items-center space-x-4">
        <div class="timeline-dot"></div>
        <div>
          <h3 class="font-semibold">1960s–1970s</h3>
          <p>Peace initiatives and Parliament appearances.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Map of Key Locations -->
  <section class="py-12 px-6 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold mb-6">Key Locations</h2>
    <div class="relative w-full h-96 bg-gray-200 rounded-lg">
      <div class="absolute top-1/4 left-1/4 map-location bg-red-600 w-6 h-6 rounded-full" title="Khartoum - Schooling"></div>
      <div class="absolute top-1/2 left-2/3 map-location bg-blue-600 w-6 h-6 rounded-full" title="Akobo - Neem Plantations"></div>
      <div class="absolute top-3/4 left-1/2 map-location bg-green-600 w-6 h-6 rounded-full" title="Fadoi - Burial"></div>
      <div class="absolute top-1/2 left-1/4 map-location bg-yellow-600 w-6 h-6 rounded-full" title="Wanglei / Jonglei - Governance"></div>
    </div>
    <p class="mt-4 text-center text-gray-700">Hover over the dots to learn key locations in Dak Dey Tut’s life.</p>
  </section>

  <!-- Family Tree -->
  <section class="py-12 px-6 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold mb-6">Family Tree</h2>
    <ul class="list-disc list-inside space-y-2">
      <li>Otong Tut + Joy Tiap
        <ul class="list-disc list-inside ml-6">
          <li>Dak Dey Tut (Dak Deth)</li>
          <li>Gai Otoang</li>
          <li>Reath Otoang</li>
          <li>Puot Otoang</li>
          <li>Nyadualdaap Otoang</li>
          <li>Nyatuoruok Otoang</li>
        </ul>
      </li>
      <li>Children of Dak Dey Tut:
        <ul class="list-disc list-inside ml-6">
          <li>Gatluak</li>
          <li>Hoth</li>
          <li>Nyang</li>
          <li>Jany</li>
          <li>Nyathak</li>
          <li>Nyakek</li>
          <li>Koryom</li>
        </ul>
      </li>
    </ul>
  </section>

  <!-- References -->
  <section class="py-12 px-6 bg-gray-100">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold mb-6">References & Documents</h2>
      <ul class="list-disc list-inside space-y-2">
        <li>Sudanese government reports mentioning Dak Dey Tut</li>
        <li>Newspaper articles from early to mid-20th century</li>
        <li>Historical notes and oral histories from Nuer elders</li>
        <li>Documents consulted during South Sudan’s independence process</li>
      </ul>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-green-800 text-white text-center py-6 mt-12">
    <p>&copy; 2025 Dak Dey Tut Legacy Project. All Rights Reserved.</p>
  </footer>

</body>
</html>
<!-- Add this script before closing </body> -->
<script>
  // Scroll-triggered timeline animation
  const timelineDots = document.querySelectorAll('.timeline-dot');

  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('scale-125', 'bg-red-600');
        entry.target.classList.remove('bg-green-500');
      }
    });
  }, { threshold: 0.5 });

  timelineDots.forEach(dot => {
    dot.classList.add('bg-green-500', 'transition', 'duration-500', 'transform');
    observer.observe(dot);
  });
</script>
