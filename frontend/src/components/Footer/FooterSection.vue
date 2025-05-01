<template>
  <footer
    class="relative bg-cover bg-center pt-60 pb-[1650px] text-black"
    :style="{ backgroundImage: `url(${footerBg})` }">
    <div
      class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-transparent w-full z-10">
      <div class="text-center max-w-3xl mx-auto px-4 mt-100">
        <h2 class="text-4xl md:text-5xl font-bold leading-tight">
          Turn your growth<br />ideas into reality today
        </h2>
        <p class="text-lg mb-8">Start your 14-day Pro trial today. No credit card required.</p>
        <div class="flex justify-center gap-4 flex-wrap">
          <button
            class="bg-black hover:bg-gray-900 text-white font-bold py-3 px-6 rounded transition cursor-pointer">
            Start building for free
          </button>
          <button
            class="border border-black hover:bg-white hover:text-black text-black font-semibold py-3 px-6 rounded transition cursor-pointer">
            Get a demo
          </button>
        </div>
      </div>
    </div>

    <div
      class="absolute left-1/2 transform -translate-x-1/2 bg-neutral-50 text-black rounded-[60px] shadow-lg w-[90%] max-w-[1150px] p-10 mt-89">
      <div class="w-full flex flex-col md:flex-row justify-between items-center gap-8 mb-10">
        <div class="max-w-[280px]">
          <h2 class="text-md font-bold leading-snug mb-3">
            Go to market with unique data <br />
            and br the ability to act on it
          </h2>
          <button
            class="bg-black text-white px-4 py-2 rounded-full font-medium flex items-center gap-2">
            Start building for free
            <span class="text-xl leading-none">→</span>
          </button>
        </div>

        <div class="flex flex-col items-end gap-4">
          <img :src="clayLogo" alt="clay" class="h-10" />
          <div class="flex items-center gap-3">
            <a
              href="https://linkedin.com"
              target="_blank"
              class="w-12 h-12 bg-white rounded-full flex items-center justify-center shadow">
              <img :src="linkedin" alt="LinkedIn" class="w-6 h-6" />
            </a>
            <a
              href="https://youtube.com"
              target="_blank"
              class="w-12 h-12 bg-white rounded-full flex items-center justify-center shadow">
              <img :src="youtube" alt="YouTube" class="w-6 h-6" />
            </a>
            <a
              href="https://slack.com"
              target="_blank"
              class="w-12 h-12 bg-white rounded-full flex items-center justify-center shadow">
              <img :src="slack" alt="Slack" class="w-6 h-6" />
            </a>
            <a
              href="https://x.com"
              target="_blank"
              class="w-12 h-12 bg-white rounded-full flex items-center justify-center shadow">
              <img :src="x" alt="X" class="w-6 h-6" />
            </a>
          </div>
        </div>
      </div>

      <div class="flex justify-between flex-wrap gap-10">
        <div class="grid grid-cols-2 md:grid-cols-5 gap-8 text-sm flex-grow">
          <div>
            <h3 class="font-bold mb-3">Product</h3>
            <div class="flex flex-col space-y-3 text-gray-800">
              <button class="text-left cursor-pointer">Login</button>
              <button class="text-left cursor-pointer">Integrations</button>
              <button class="text-left cursor-pointer">Multi-provider data enrichment</button>
              <button class="text-left cursor-pointer">AI formula generator</button>
              <button class="text-left cursor-pointer">AI Research agent</button>
              <button class="text-left cursor-pointer">Personalized copywriting</button>
              <button class="text-left cursor-pointer">Pricing</button>
              <button class="text-left cursor-pointer">Changelog</button>
            </div>
          </div>
          <div>
            <h3 class="font-bold mb-3">Tools</h3>
            <div class="flex flex-col space-y-3 text-gray-800">
              <button class="text-left cursor-pointer">Email finder</button>
              <button class="text-left cursor-pointer">Headcount finder</button>
              <button class="text-left cursor-pointer">Credits calculator</button>
              <button class="text-left cursor-pointer">Chrome extension</button>
              <button class="text-left cursor-pointer">Lookup WHOIS info</button>
              <button class="text-left cursor-pointer">CPM calculator</button>
              <button class="text-left cursor-pointer">Margin calculator</button>
              <button class="text-left cursor-pointer">Headcount directory</button>
              <button class="text-left cursor-pointer">Glossary</button>
              <button class="text-left cursor-pointer">Dossier</button>
              <button class="text-left cursor-pointer">Job board</button>
            </div>
          </div>
          <div>
            <h3 class="font-bold mb-3">Blog</h3>
            <div class="flex flex-col space-y-3 text-gray-800">
              <button class="text-left cursor-pointer">
                Why we built the first GTM engineering team
              </button>
              <button class="text-left cursor-pointer">AI for sales prospecting</button>
              <button class="text-left cursor-pointer">Why good CRM data matters</button>
              <button class="text-left cursor-pointer">
                Google maps lead generation in 5 easy steps
              </button>
              <button class="text-left cursor-pointer">Outbound sales automation</button>
              <button class="text-left cursor-pointer">Scraping data from Websites</button>
            </div>
          </div>
          <div>
            <h3 class="font-bold mb-3">Resources</h3>
            <div class="flex flex-col space-y-3 text-gray-800">
              <button class="text-left cursor-pointer">Get started lesson</button>
              <button class="text-left cursor-pointer">University</button>
              <button class="text-left cursor-pointer">Playbooks</button>
              <button class="text-left cursor-pointer">Templates</button>
              <button class="text-left cursor-pointer">Experts</button>
              <button class="text-left cursor-pointer">Join Slack</button>
              <button class="text-left cursor-pointer">Community</button>
              <button class="text-left cursor-pointer">FAQ</button>
            </div>
          </div>
          <div>
            <h3 class="font-bold mb-3">Company</h3>
            <div class="flex flex-col space-y-3 text-gray-800">
              <button class="text-left cursor-pointer">Customer stories</button>
              <button class="text-left cursor-pointer">Wall of love</button>
              <button class="text-left cursor-pointer">About</button>
              <button class="text-left cursor-pointer">Careers</button>
              <button class="text-left cursor-pointer">
                Jobs <span class="bg-yellow-300 text-xs px-1 rounded">We are hiring!</span>
              </button>
              <button class="text-left cursor-pointer">Creators program</button>
              <button class="text-left cursor-pointer">Integrate with Clay</button>
              <button class="text-left cursor-pointer">Status</button>
            </div>
          </div>
        </div>

        <div class="w-full mt-8 grid grid-cols-2 md:grid-cols-6 text-sm gap-6">
          <div>
            <h3 class="font-bold mb-2">Customers</h3>
            <div class="flex flex-col space-y-3 text-gray-800">
              <button class="text-left cursor-pointer">OpenAI</button>
              <button class="text-left cursor-pointer">Vanta</button>
              <button class="text-left cursor-pointer">Verkada</button>
              <button class="text-left cursor-pointer">Sendoso</button>
              <button class="text-left cursor-pointer">Anthropic</button>
              <button class="text-left cursor-pointer">Coverflex</button>
              <button class="text-left cursor-pointer">Rippling</button>
            </div>
          </div>
          <div>
            <h3 class="font-bold mb-2">Legal</h3>
            <div class="flex flex-col space-y-3 text-gray-800">
              <button class="text-left cursor-pointer">Privacy policy</button>
              <button class="text-left cursor-pointer">Terms of service</button>
              <button class="text-left cursor-pointer">Do not sell my data</button>
            </div>
          </div>
        </div>
      </div>

      <div class="mt-10 text-sm text-gray-500">
        <p>&copy; Clay 2025 – Go to market with unique data and the ability to act on it.</p>
      </div>
    </div>
  </footer>
</template>

<script setup>
  import footerBg from '@/assets/png/footer.png';
  import clayLogo from '@/assets/logo/claylogoblack.png';
  import linkedin from '@/assets/footer/linkedin.avif';
  import youtube from '@/assets/footer/youtube.avif';
  import slack from '@/assets/footer/rainbow.avif';
  import x from '@/assets/footer/x.avif';
</script>

<style scoped>
  footer {
    background-size: cover;
    background-position: center;
  }
</style>
