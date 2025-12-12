<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Mail your film",
      desc: "Send us your film with our prepaid mailers or drop it off at our Burlington store.",
      img: "/generated/image-close-up-of-hands-holding-developed-film-1765566736334-1.webp"
    },
    {
      num: "02",
      title: "Expert processing",
      desc: "Our experienced technicians carefully develop your film using professional-grade equipment.",
      img: "/generated/image-person-carefully-examining-film-negative-1765566749740-7.webp"
    },
    {
      num: "03",
      title: "Quality control",
      desc: "Every negative is inspected and scanned at high resolution to ensure perfect results.",
      img: "/generated/image-professional-photo-printer-producing-hig-1765566745092-5.webp"
    },
    {
      num: "04",
      title: "Receive your photos",
      desc: "Get your developed film, scans, and prints delivered to your door or pick up in store.",
      img: "/generated/image-beautiful-printed-photographs-laid-out-o-1765566738524-2.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Film processing in four simple steps. Fast turnaround guaranteed.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Want the details?</h3>
        <p class="text-gray-500 text-sm">Learn more about our film processing services and pricing.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          All services
        </button>
        <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
          Download price list
        </button>
      </div>
    </div>
  </div>
</section>
