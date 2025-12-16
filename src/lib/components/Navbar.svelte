<script lang="ts">
  import { onMount } from 'svelte';
  
  let isScrolled = $state(false);

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 20;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<nav class={[
  'fixed top-0 left-0 right-0 z-50 transition-all duration-200',
  isScrolled ? 'bg-white/95 backdrop-blur-sm border-b border-gray-200' : 'bg-white'
]}>
  <div class="container-custom">
    <div class="flex items-center justify-between h-16">
      <!-- Logo & Brand -->
      <div class="flex items-center gap-10">
        <a href="/" class="flex items-center gap-2.5 group">
          <svg width="22" height="18" viewBox="0 0 152 125" fill="none" xmlns="http://www.w3.org/2000/svg" class="transition-transform group-hover:scale-105">
            <path d="M143.58 84.2131H151.874L141.028 72.9422C125.504 56.7801 104.026 47.6357 81.4839 47.6357H78.9319H73.4028H70.6382C48.309 47.6357 26.8304 56.7801 11.0937 72.9422L0.248047 84.2131H8.54176C30.871 84.2131 52.3495 75.0688 68.0863 58.9067L76.1674 50.613C71.4889 79.1093 30.871 124.193 30.871 124.193H76.38H121.889C121.889 124.193 81.6965 79.7473 76.5927 51.2509L84.0358 59.1193C99.5599 75.0688 121.038 84.2131 143.58 84.2131Z" fill="currentColor"/>
            <path d="M69.362 31.0482L75.9544 24.2431L82.5469 31.0482C95.3064 44.4457 113.17 51.8888 131.671 51.8888H138.476L129.545 42.5318C116.785 29.1342 98.9216 21.6912 80.4203 21.6912H78.2937H73.6152H71.4886C52.9872 21.6912 35.3365 29.1342 22.3643 42.5318L13.4326 52.1014H20.2377C38.7391 52.1014 56.6024 44.4457 69.362 31.0482Z" fill="currentColor"/>
            <path d="M70.638 7.65573L75.9544 2.12659L81.2709 7.65573C91.6912 18.5013 106.152 24.6685 121.251 24.6685H126.78L119.55 17.0127C109.129 6.16712 94.6684 0 79.5696 0H77.8684H74.0405H72.3392C57.2404 0 42.7796 6.16712 32.3593 17.0127L25.1289 24.6685H30.658C45.7568 24.6685 60.2177 18.5013 70.638 7.65573Z" fill="currentColor"/>
          </svg>
          <span class="text-lg font-semibold text-gray-900">Wrench</span>
        </a>
        
        <div class="hidden md:flex items-center gap-1">
          <a href="#features" class="px-3 py-2 text-sm text-gray-600 hover:text-gray-900 rounded-md hover:bg-gray-50 transition-colors">Features</a>
          <a href="#pricing" class="px-3 py-2 text-sm text-gray-600 hover:text-gray-900 rounded-md hover:bg-gray-50 transition-colors">Pricing</a>
          <a href="#integrations" class="px-3 py-2 text-sm text-gray-600 hover:text-gray-900 rounded-md hover:bg-gray-50 transition-colors">Integrations</a>
        </div>
      </div>

      <!-- Actions -->
      <div class="flex items-center gap-2">
        <a href="#" class="hidden sm:block px-4 py-2 text-sm font-medium text-gray-700 hover:text-gray-900 transition-colors">
          Sign in
        </a>
        <a href="#" class="px-4 py-2 text-sm font-medium bg-gray-900 text-white rounded-md hover:bg-gray-800 transition-colors">
          Get started
        </a>
      </div>
    </div>
  </div>
</nav>
