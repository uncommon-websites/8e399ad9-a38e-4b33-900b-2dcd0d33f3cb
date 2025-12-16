<script lang="ts">
  // Integrations component
  
  const integrations = [
    {
      name: 'QuickBooks',
      description: 'Sync invoices and payments automatically',
      category: 'Accounting',
      logo: '/integrations/quickbooks.svg'
    },
    {
      name: 'Stripe',
      description: 'Accept payments instantly on-site',
      category: 'Payments',
      logo: '/integrations/stripe.svg'
    },
    {
      name: 'Google Calendar',
      description: 'Two-way calendar synchronization',
      category: 'Scheduling',
      logo: '/integrations/google-calendar.svg'
    },
    {
      name: 'Zapier',
      description: 'Connect to 5,000+ apps',
      category: 'Automation',
      logo: '/integrations/zapier.svg'
    },
    {
      name: 'Twilio',
      description: 'SMS notifications and reminders',
      category: 'Communication',
      logo: '/integrations/twilio.svg'
    },
    {
      name: 'Microsoft Outlook',
      description: 'Email and calendar integration',
      category: 'Scheduling',
      logo: '/integrations/outlook.svg'
    }
  ];
</script>

<section id="integrations" class="py-20 md:py-28 bg-gray-50">
  <div class="container-custom">
    <!-- Section Header -->
    <div class="max-w-3xl mx-auto text-center mb-16">
      <h2 class="text-3xl md:text-5xl font-bold text-gray-900 mb-4">
        Works with the tools you already use
      </h2>
      <p class="text-lg text-gray-600">
        Wrench integrates seamlessly with your existing accounting, payment, and scheduling tools. No need to change your workflow.
      </p>
    </div>

    <!-- Integrations Grid -->
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 max-w-5xl mx-auto mb-12">
      {#each integrations as integration}
        <div class="bg-white rounded-lg border border-gray-200 p-6 hover:border-gray-300 transition-colors">
          <div class="flex items-start gap-4">
            <!-- Logo Placeholder -->
            <div class="w-12 h-12 rounded-lg bg-gray-100 border border-gray-200 flex items-center justify-center flex-shrink-0">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <rect x="3" y="3" width="18" height="18" rx="2"/>
                <circle cx="12" cy="12" r="3"/>
              </svg>
            </div>
            
            <div class="flex-1 min-w-0">
              <div class="flex items-center gap-2 mb-1">
                <h3 class="font-semibold text-gray-900">{integration.name}</h3>
                <span class="px-2 py-0.5 bg-gray-100 text-gray-600 text-xs rounded-full">{integration.category}</span>
              </div>
              <p class="text-sm text-gray-600">{integration.description}</p>
            </div>
          </div>
        </div>
      {/each}
    </div>

    <!-- API Access -->
    <div class="max-w-3xl mx-auto text-center">
      <div class="bg-white rounded-lg border border-gray-200 p-8">
        <div class="inline-flex items-center justify-center w-12 h-12 rounded-full bg-gray-100 mb-4">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <polyline points="16 18 22 12 16 6"/>
            <polyline points="8 6 2 12 8 18"/>
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-gray-900 mb-2">Need a custom integration?</h3>
        <p class="text-gray-600 mb-4">
          Our REST API makes it easy to build custom integrations with your existing systems.
        </p>
        <a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:text-gray-700 transition-colors">
          View API documentation
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="m9 18 6-6-6-6"/>
          </svg>
        </a>
      </div>
    </div>
  </div>
</section>
