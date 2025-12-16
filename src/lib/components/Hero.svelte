<script lang="ts">
  // Hero component
</script>

<section class="pt-24 pb-12 md:pt-32 md:pb-16">
  <div class="container-custom">
    <div class="max-w-3xl mx-auto text-center mb-16">
      
      <!-- Social Proof Badge -->
      <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-gray-100 text-gray-700 text-xs font-medium mb-6">
        <span class="flex items-center gap-1">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
          Trusted by 200+ HVAC shops
        </span>
      </div>

      <!-- Headline -->
      <h1 class="text-4xl md:text-6xl font-bold text-gray-900 mb-5 leading-tight">
        Stop losing revenue to missed calls and forgotten follow-ups
      </h1>

      <!-- Subheadline -->
      <p class="text-lg md:text-xl text-gray-600 mb-8 leading-relaxed">
        Wrench handles scheduling, follow-ups, and invoicing automatically. Built specifically for HVAC shops with 5-15 techs. Setup takes 10 minutes.
      </p>

      <!-- CTA Buttons -->
      <div class="flex flex-col sm:flex-row items-center justify-center gap-3 mb-4">
        <a href="#" class="w-full sm:w-auto px-6 py-3 text-base font-semibold bg-gray-900 text-white rounded-lg hover:bg-gray-800 transition-all">
          Start free trial
        </a>
        <a href="#" class="w-full sm:w-auto px-6 py-3 text-base font-semibold text-gray-700 hover:text-gray-900 transition-colors flex items-center justify-center gap-2">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="5 3 19 12 5 21 5 3"/></svg>
          Watch demo
        </a>
      </div>
      
      <p class="text-sm text-gray-500">No credit card required</p>
    </div>

    <!-- Product Preview -->
    <div class="relative w-full max-w-6xl mx-auto">
      <!-- Main Dashboard Preview -->
      <div class="relative rounded-lg border border-gray-200 bg-white overflow-hidden">
        <!-- Simple Browser Bar -->
        <div class="bg-gray-50 border-b border-gray-200 px-4 py-2.5 flex items-center gap-3">
          <div class="flex gap-1.5">
            <div class="w-2.5 h-2.5 rounded-full bg-gray-300"></div>
            <div class="w-2.5 h-2.5 rounded-full bg-gray-300"></div>
            <div class="w-2.5 h-2.5 rounded-full bg-gray-300"></div>
          </div>
          <div class="text-xs text-gray-500 font-mono">app.wrench.com</div>
        </div>

        <!-- Dashboard Content -->
        <div class="bg-white p-6 md:p-8">
          <!-- Header -->
          <div class="flex items-center justify-between mb-6 pb-4 border-b border-gray-100">
            <div>
              <h2 class="text-xl font-semibold text-gray-900 mb-1">Today's schedule</h2>
              <p class="text-sm text-gray-500">8 jobs scheduled • 5 technicians active</p>
            </div>
            <div class="flex items-center gap-2 px-3 py-1.5 bg-green-50 text-green-700 text-sm font-medium rounded-md border border-green-100">
              <div class="w-2 h-2 bg-green-500 rounded-full animate-pulse"></div>
              AI receptionist active
            </div>
          </div>

          <!-- Job List -->
          <div class="space-y-3 mb-8">
            <div class="flex items-start gap-4 p-4 bg-gray-50 rounded-lg border border-gray-100">
              <div class="w-10 h-10 rounded-full bg-blue-100 flex items-center justify-center text-blue-700 font-semibold text-sm flex-shrink-0">
                MJ
              </div>
              <div class="flex-1 min-w-0">
                <div class="flex items-start justify-between gap-4 mb-1">
                  <div>
                    <p class="font-medium text-gray-900">Mike Johnson</p>
                    <p class="text-sm text-gray-600">AC repair • 2:00 PM</p>
                  </div>
                  <span class="px-2.5 py-1 bg-green-100 text-green-700 text-xs font-medium rounded whitespace-nowrap">En route</span>
                </div>
                <p class="text-sm text-gray-500">123 Oak Street</p>
              </div>
            </div>

            <div class="flex items-start gap-4 p-4 bg-gray-50 rounded-lg border border-gray-100">
              <div class="w-10 h-10 rounded-full bg-purple-100 flex items-center justify-center text-purple-700 font-semibold text-sm flex-shrink-0">
                SD
              </div>
              <div class="flex-1 min-w-0">
                <div class="flex items-start justify-between gap-4 mb-1">
                  <div>
                    <p class="font-medium text-gray-900">Sarah Davis</p>
                    <p class="text-sm text-gray-600">Maintenance check • 3:30 PM</p>
                  </div>
                  <span class="px-2.5 py-1 bg-gray-100 text-gray-700 text-xs font-medium rounded whitespace-nowrap">Scheduled</span>
                </div>
                <p class="text-sm text-gray-500">456 Maple Avenue</p>
              </div>
            </div>
          </div>

          <!-- AI Activity Card -->
          <div class="bg-gray-900 rounded-lg p-5 text-white">
            <div class="flex items-center justify-between mb-4">
              <div class="flex items-center gap-2">
                <div class="w-6 h-6 rounded-full bg-white flex items-center justify-center">
                  <span class="text-xs font-bold text-gray-900">AI</span>
                </div>
                <span class="text-sm font-medium">AI receptionist</span>
              </div>
              <span class="text-xs text-green-400">Just now</span>
            </div>
            <div class="space-y-2 text-sm">
              <p class="text-white">New call from Mrs. Anderson requesting AC service</p>
              <div class="space-y-1 text-gray-400 pl-4 border-l-2 border-gray-700">
                <p>✓ Checked technician availability</p>
                <p>✓ Scheduled appointment for tomorrow at 10:00 AM</p>
                <p>✓ Assigned to Tech #3 (closest to location)</p>
                <p>✓ Sent confirmation text to customer</p>
              </div>
              <div class="pt-3 mt-3 border-t border-gray-800">
                <p class="text-green-400 font-medium">Revenue captured: $285</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
