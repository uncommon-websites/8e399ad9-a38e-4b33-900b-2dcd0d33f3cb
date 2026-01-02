<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-16">
			
			<!-- Left Column: CTA & Visual -->
			<div class="flex flex-col h-full">
				<div class="mb-8">
					<p class="font-mono text-xs text-muted mb-4">Get started</p>
					<h2 class="text-2xl font-medium mb-4">Focus on what matters. Let agents handle the rest.</h2>
					<p class="text-muted font-light mb-8 text-sm leading-relaxed max-w-md">
						Wren delivers autonomous AI agents that complete complex research and operations tasks end-to-end, with full transparency.
					</p>
					<div class="flex gap-3 mb-12">
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							START FREE TRIAL
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">W</span>
						</button>
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							VIEW DEMO
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">D</span>
						</button>
					</div>
				</div>
				
				<!-- Agent Activity Visual -->
				<div class="mt-auto w-full h-48 bg-gradient-to-br from-primary-950 to-gray-900 relative overflow-hidden flex items-center justify-center">
					<!-- Grid pattern -->
					<div class="absolute inset-0 opacity-20" style="background-image: linear-gradient(rgba(255,255,255,0.1) 1px, transparent 1px), linear-gradient(90deg, rgba(255,255,255,0.1) 1px, transparent 1px); background-size: 20px 20px;"></div>
					
					<!-- Pulsing dots representing agent activity -->
					{#each Array(30) as _, i}
						<div 
							class="absolute w-1 h-1 bg-primary-400 rounded-full animate-pulse" 
							style="
								left: {Math.random() * 100}%; 
								top: {Math.random() * 100}%;
								animation-delay: {Math.random() * 2}s;
								opacity: {0.3 + Math.random() * 0.7};
							"
						></div>
					{/each}
					
					<div class="absolute inset-0 flex items-center justify-center">
						<div class="bg-white/10 backdrop-blur-sm text-white font-mono text-[10px] px-3 py-1.5 z-10 border border-white/20 rounded">
							<span class="text-green-400">●</span> Agents active
						</div>
					</div>
				</div>
			</div>

			<!-- Right Column: Updates -->
			<div>
				<p class="font-mono text-xs text-muted mb-8">What's new</p>
				
				<div class="space-y-12">
					<!-- Update 1 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">January 15</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Multi-tenant workspaces now available</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Teams can now collaborate on agent tasks with shared workspaces. Invite team members, share execution logs, and manage workflows together. Perfect for small teams scaling their AI-assisted operations.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Product Update</span>
						</div>
					</div>

					<!-- Update 2 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">January 8</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Enhanced execution transparency</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Every agent action is now logged with millisecond precision. See exactly what your agents are doing, when they're doing it, and why. New visualization tools make it easy to audit and verify completed work.
							</p>
							<div class="flex gap-2">
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Product Update</span>
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Trust & Safety</span>
							</div>
						</div>
					</div>

					<!-- Update 3 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">December 20</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Research agents hit 85% time savings</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Early users report saving an average of 85% of time on deep research tasks. Our autonomous research agents handle everything from source gathering to insight synthesis, delivering comprehensive reports in minutes instead of hours.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Case Study</span>
						</div>
					</div>

					<!-- Update 4 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">December 10</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Wren launches autonomous AI agent platform</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Introducing Wren: autonomous AI agents that deliver real work, end-to-end. Starting with research and operations tasks, running securely in your browser with complete transparency.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Launch</span>
						</div>
					</div>
				</div>
			</div>

		</div>
	</div>
</section>
