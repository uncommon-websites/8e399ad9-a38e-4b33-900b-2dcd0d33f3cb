<script>
  import Navbar from '$lib/components/Navbar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import Logos from '$lib/components/Logos.svelte';
  import ProblemStatement from '$lib/components/ProblemStatement.svelte';
  import FeaturesGrid from '$lib/components/FeaturesGrid.svelte';
  import FeatureAri from '$lib/components/FeatureAri.svelte';
  import Testimonials from '$lib/components/Testimonials.svelte';
  import Integrations from '$lib/components/Integrations.svelte';
  import CTA from '$lib/components/CTA.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen bg-white font-body selection:bg-green-100 selection:text-green-900">
  <Navbar />
  
  <main>
    <Hero />
    <Logos />
    <ProblemStatement />
    <FeaturesGrid />
    <FeatureAri />
    <Testimonials />
    <Integrations />
    <CTA />
  </main>

  <Footer />
  
  <!-- Floating Chat Button -->
  <div class="fixed bottom-6 right-6 z-50">
      <button class="w-14 h-14 bg-black rounded-full flex items-center justify-center hover:scale-105 transition-transform border-2 border-gray-200">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
      </button>
  </div>
</div>

