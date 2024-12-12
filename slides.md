---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
css: unocss
---

# Summer 2024
<div class="pt-12 text-xl text-gray-400">
Internship
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://www.olivet.edu/benner-library" target="_blank" 
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white transition duration-300 ease-in-out transform hover:scale-110">
    Benner Library
  </a>
</div>

---
layout: two-cols
---

# Benner Library Informatics

<div class="text-lg mt-4">
  Completed internship as a Web Application Developer Intern under the supervision of:

  <div class="mt-4 grid grid-cols-2 gap-4">
    <div v-click class="p-4 border rounded-lg shadow-lg hover:shadow-2xl transition-shadow duration-300">
      <div class="font-bold">Direct Supervisors</div>
      <ul class="mt-2">
        <li>David Hathaway</li>
        <li>Brian Bowen</li>
      </ul>
    </div>
    <div v-click class="p-4 border rounded-lg shadow-lg hover:shadow-2xl transition-shadow duration-300">
      <div class="font-bold">Senior Supervisors</div>
      <ul class="mt-2">
        <li>Matt Marcukaitis</li>
        <li>Ann Johnston</li>
      </ul>
    </div>
  </div>
</div>

::right::

<div class="ml-4">
  <div v-click class="mt-4 p-6 bg-blue-50 dark:bg-blue-900 rounded-lg shadow-lg hover:shadow-2xl transition-shadow duration-300">
    <div class="flex flex-col items-center">
      <h3 class="text-lg font-bold mb-2">About Benner Library</h3>
      <p class="text-sm opacity-90">
        Benner Library is the library on Olivet Nazarene Universities campus serving students as well as faculty and staff. The library strives to offer inclusive and accessible resources that provide easy access to knowledge.
      </p>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2PmRpIdLzcwlrgyOin-1qTwqsIgGm2yl-LA&s" alt="Benner Library" class="mt-4 rounded-lg shadow-lg">
    </div>
  </div>
</div>

---
layout: default
---

# Project Achievements 🚀

<v-clicks>

<div class="mt-6 grid grid-cols-2 gap-4">
  <div class="p-4 border rounded-lg shadow-lg hover:shadow-2xl transition-shadow duration-300">
    <h3 class="font-bold text-blue-500">Bulletins Application Redesign</h3>
    <p class="text-sm mt-2">Completely revamped search functionality and UI with new filtering, sorting, and view options</p>
    <img src="https://utfs.io/f/LF1QrFGZgDsb0iqr1XSOokM2sUqGjyagDWSpfQL4O6nhmX9P" alt="Bulletins Application" class="mt-4 rounded-lg shadow-lg">
  </div>

  <div class="p-4 border rounded-lg shadow-lg hover:shadow-2xl transition-shadow duration-300">
    <h3 class="font-bold text-green-500">Software Releases</h3>
    <p class="text-sm mt-2">Led successfull releases of Tally, Checkout Management, and Bulletins as well as completing significant changes to the library website</p>
  </div>

  <div class="p-4 border rounded-lg shadow-lg hover:shadow-2xl transition-shadow duration-300">
    <h3 class="font-bold text-purple-500">Database Architecture</h3>
    <p class="text-sm mt-2">Implemented gc_users migration, last edited tracking, and restructured relationships</p>
  </div>

  <div class="p-4 border rounded-lg shadow-lg hover:shadow-2xl transition-shadow duration-300">
    <h3 class="font-bold text-orange-500">Mobile Responsiveness</h3>
    <p class="text-sm mt-2">Enhanced CSS and interface scaling across applications for better mobile experience while keeping functionality intact on desktop</p>
  </div>
</div>

</v-clicks>

---
layout: center
class: text-center
---

# Key Takeaways 🎯

<div class="grid grid-cols-2 gap-8 mt-8">
  <div v-click class="flex flex-col items-center">
    <div class="text-3xl mb-4 animate-bounce">🗄️</div>
    <h3 class="font-bold mb-2">Database Design</h3>
    <p class="text-sm opacity-75">
      I gained insight into database design and administration specifically how to implement proper foreign key relationships and database migrations.
    </p>
  </div>
  <div v-click class="flex flex-col items-center">
    <div class="text-3xl mb-4 animate-bounce">📱</div>
    <h3 class="font-bold mb-2">Responsive Design</h3>
    <p class="text-sm opacity-75">
        Responsive design principles through CSS improvements across multiple applications and device types.    </p>
  </div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}

a {
  transition: color 0.3s ease, transform 0.3s ease;
}

a:hover {
  color: white;
  transform: scale(1.1);
}

.shadow-lg {
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
}

.shadow-2xl {
  box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
}

.animate-bounce {
  animation: bounce 1s infinite;
}

@keyframes bounce {
  0%, 100% {
    transform: translateY(-25%);
    animation-timing-function: cubic-bezier(0.8, 0, 1, 1);
  }
  50% {
    transform: translateY(0);
    animation-timing-function: cubic-bezier(0, 0, 0.2, 1);
  }
}
</style>