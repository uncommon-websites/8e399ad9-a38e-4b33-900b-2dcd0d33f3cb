<script lang="ts">
  // Hero component
</script>

<!-- Hero Section with Gradient Background -->
<section class="relative pt-20 pb-16 md:pt-28 md:pb-24 overflow-hidden">
  <!-- Interesting Gradient Background -->
  <div class="absolute inset-0 bg-gradient-to-br from-green-50 via-white to-blue-50"></div>
  
  <!-- Subtle Pattern Overlay -->
  <div class="absolute inset-0 opacity-30" style="background-image: radial-gradient(circle at 1px 1px, rgb(0 0 0 / 0.05) 1px, transparent 0); background-size: 40px 40px;"></div>
  
  <!-- Content -->
  <div class="relative container-custom">
    <div class="max-w-4xl mx-auto text-center mb-12 md:mb-16">
      
      <!-- Trust Badge -->
      <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-white border border-gray-200 text-sm font-medium mb-8">
        <span class="flex items-center gap-1.5 text-gray-700">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
          Trusted by 200+ HVAC shops
        </span>
      </div>

      <!-- Main Headline - Punchier & Shorter -->
      <h1 class="text-5xl md:text-7xl font-bold text-gray-900 mb-6 leading-[1.1] tracking-tight">
        Never miss another<br/>service call
      </h1>

      <!-- Subheadline - Simplified -->
      <p class="text-xl md:text-2xl text-gray-600 mb-10 leading-relaxed font-medium">
        AI handles your calls, schedules jobs, and sends invoices.<br class="hidden md:block"/>
        Setup in 10 minutes. No complexity.
      </p>

      <!-- CTA Buttons -->
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-6">
        <a href="#" class="group w-full sm:w-auto px-8 py-4 text-lg font-semibold bg-gray-900 text-white rounded-xl hover:bg-gray-800 transition-all hover:scale-105">
          Start free trial
        </a>
        <a href="#" class="w-full sm:w-auto px-8 py-4 text-lg font-semibold text-gray-700 hover:text-gray-900 transition-colors flex items-center justify-center gap-2 group">
          <svg class="group-hover:scale-110 transition-transform" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="5 3 19 12 5 21 5 3"/></svg>
          Watch demo
        </a>
      </div>
      
      <p class="text-sm text-gray-500">No credit card • 14-day free trial</p>
    </div>

    <!-- Simplified Dashboard Preview -->
    <div class="relative w-full max-w-5xl mx-auto">
      <!-- Floating Elements for Visual Interest -->
      <div class="absolute -top-4 -left-4 w-20 h-20 bg-green-200 rounded-full blur-3xl opacity-60"></div>
      <div class="absolute -bottom-4 -right-4 w-32 h-32 bg-blue-200 rounded-full blur-3xl opacity-60"></div>
      
      <!-- Main Dashboard Card -->
      <div class="relative rounded-2xl border-2 border-gray-200 bg-white overflow-hidden">
        
        <!-- Browser Bar -->
        <div class="bg-gray-50 border-b border-gray-200 px-5 py-3 flex items-center gap-3">
          <div class="flex gap-2">
            <div class="w-3 h-3 rounded-full bg-red-400"></div>
            <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
            <div class="w-3 h-3 rounded-full bg-green-400"></div>
          </div>
          <div class="flex-1 text-center">
            <div class="inline-flex items-center gap-2 px-3 py-1 bg-white rounded-md border border-gray-200">
              <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
              <span class="text-xs text-gray-600 font-mono">app.wrench.com</span>
            </div>
          </div>
        </div>

        <!-- Dashboard Content - Simplified -->
        <div class="bg-gradient-to-b from-white to-gray-50 p-8 md:p-10">
          
          <!-- Header with Live Status -->
          <div class="flex items-center justify-between mb-8 pb-6 border-b-2 border-gray-100">
            <div>
              <h2 class="text-2xl font-bold text-gray-900 mb-1">Today's schedule</h2>
              <p class="text-gray-600 font-medium">8 jobs • 5 techs active</p>
            </div>
            <div class="flex items-center gap-2 px-4 py-2 bg-green-50 text-green-700 font-semibold rounded-lg border-2 border-green-200">
              <div class="w-2.5 h-2.5 bg-green-500 rounded-full animate-pulse"></div>
              AI active
            </div>
          </div>

          <!-- Single Job Card - Clean & Simple -->
          <div class="bg-white rounded-xl border-2 border-gray-100 p-6 mb-6 hover:border-gray-200 transition-colors">
            <div class="flex items-start gap-4">
              <div class="w-12 h-12 rounded-full bg-gradient-to-br from-blue-500 to-blue-600 flex items-center justify-center text-white font-bold text-lg flex-shrink-0">
                MJ
              </div>
              <div class="flex-1 min-w-0">
                <div class="flex items-start justify-between gap-4 mb-2">
                  <div>
                    <p class="font-bold text-gray-900 text-lg">Mike Johnson</p>
                    <p class="text-gray-600">AC repair • 2:00 PM</p>
                  </div>
                  <span class="px-3 py-1.5 bg-green-100 text-green-700 text-sm font-bold rounded-lg whitespace-nowrap">En route</span>
                </div>
                <p class="text-gray-500">123 Oak Street</p>
              </div>
            </div>
          </div>

          <!-- AI Activity Card - Hero Element -->
          <div class="relative bg-gradient-to-br from-gray-900 to-gray-800 rounded-xl p-6 text-white overflow-hidden">
            <!-- Subtle pattern -->
            <div class="absolute inset-0 opacity-10" style="background-image: radial-gradient(circle at 1px 1px, white 1px, transparent 0); background-size: 20px 20px;"></div>
            
            <div class="relative">
              <div class="flex items-center justify-between mb-5">
                <div class="flex items-center gap-3">
                  <div class="w-8 h-8 rounded-full bg-white flex items-center justify-center">
                    <span class="text-sm font-bold text-gray-900">AI</span>
                  </div>
                  <span class="font-bold">AI receptionist</span>
                </div>
                <span class="text-xs text-green-400 font-semibold">Just now</span>
              </div>
              
              <div class="space-y-3">
                <p class="text-white font-medium text-lg">New call: Mrs. Anderson needs AC service</p>
                <div class="space-y-2 text-gray-300 pl-4 border-l-2 border-gray-600">
                  <p>✓ Checked availability</p>
                  <p>✓ Scheduled for tomorrow 10 AM</p>
                  <p>✓ Sent confirmation text</p>
                </div>
                <div class="pt-4 mt-4 border-t-2 border-gray-700">
                  <p class="text-green-400 font-bold text-xl">Revenue captured: $285</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
