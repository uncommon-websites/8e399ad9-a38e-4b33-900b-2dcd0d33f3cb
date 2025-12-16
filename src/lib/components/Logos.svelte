<script>
  const logos = [
    { name: "Cool Air HVAC", font: "font-sans font-bold" },
    { name: "Precision Heating", font: "font-sans font-bold tracking-tight" },
    { name: "Elite Climate", font: "font-sans font-bold" },
    { name: "Pro Comfort", font: "font-sans font-bold" },
    { name: "Rapid Response", font: "font-sans font-bold" },
    { name: "Total Temp", font: "font-sans font-bold" },
    { name: "Air Masters", font: "font-sans font-bold" },
    { name: "Climate Pro", font: "font-sans font-bold" },
    { name: "HVAC Solutions", font: "font-sans font-bold" },
    { name: "Comfort First", font: "font-sans font-bold" },
    { name: "Peak Performance", font: "font-sans font-bold" },
    { name: "Service Plus", font: "font-sans font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by HVAC shops recovering revenue every day
    </p>
    
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-x-8 gap-y-12 items-center justify-items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
      {#each logos as logo}
        <div class="text-xl md:text-2xl text-gray-800 flex items-center justify-center w-full">
           <!-- Placeholder for actual SVG logos -->
           <span class="{logo.font}">{logo.name}</span>
        </div>
      {/each}
    </div>
  </div>
</section>
