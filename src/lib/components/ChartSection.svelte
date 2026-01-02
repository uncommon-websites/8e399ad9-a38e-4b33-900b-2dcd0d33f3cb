<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="flex flex-col md:flex-row justify-between items-start mb-16 gap-8">
			<div>
				<h2 class="text-3xl font-medium mb-2">Measurable productivity gains</h2>
				<p class="text-xl text-muted font-light">Time saved on complex research and operations tasks</p>
			</div>
			<div class="max-w-xs text-[10px] text-muted leading-relaxed border-l border-border pl-4">
				<strong class="text-foreground block mb-1">About this data</strong>
				Based on early user feedback across research, competitive analysis, and operational tasks. Users report significant time savings when delegating complex multi-step workflows to Wren's autonomous agents. Time measurements compare manual completion vs. agent-assisted completion for equivalent quality outputs.
			</div>
		</div>

		<div class="relative w-full h-[500px] border border-border bg-primary-50/30 p-8 font-mono text-xs">
			<!-- Chart Grid -->
			<div class="absolute inset-0 p-8 grid grid-rows-6 grid-cols-1">
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
			</div>
			
			<!-- Y Axis Label -->
			<div class="absolute left-2 top-1/2 -translate-y-1/2 -rotate-90 text-muted origin-center whitespace-nowrap">
				TIME SAVED (%)
			</div>

			<!-- X Axis Label -->
			<div class="absolute bottom-2 left-1/2 -translate-x-1/2 text-muted">
				TASK COMPLEXITY
			</div>

			<!-- Top Left Legend -->
			<div class="absolute top-4 left-4 flex gap-4 text-[10px] text-muted">
				<span class="bg-gray-200 px-1 rounded text-foreground">User reported data</span>
			</div>

			<!-- Bar Chart Visualization -->
			
			<!-- Research Tasks -->
			<div class="absolute bottom-[8%] left-[15%] flex flex-col items-center group cursor-pointer z-10">
				<div class="w-16 bg-accent h-[280px] rounded-t"></div>
				<div class="mt-2 text-[10px] text-center">
					<div class="font-bold text-accent">85%</div>
					<div class="text-muted">Research</div>
				</div>
			</div>

			<!-- Competitive Analysis -->
			<div class="absolute bottom-[8%] left-[35%] flex flex-col items-center group cursor-pointer">
				<div class="w-16 bg-accent h-[300px] rounded-t"></div>
				<div class="mt-2 text-[10px] text-center">
					<div class="font-bold text-accent">90%</div>
					<div class="text-muted">Analysis</div>
				</div>
			</div>

			<!-- Data Collection -->
			<div class="absolute bottom-[8%] left-[55%] flex flex-col items-center group cursor-pointer">
				<div class="w-16 bg-accent h-[260px] rounded-t"></div>
				<div class="mt-2 text-[10px] text-center">
					<div class="font-bold text-accent">80%</div>
					<div class="text-muted">Data Ops</div>
				</div>
			</div>

			<!-- Report Generation -->
			<div class="absolute bottom-[8%] right-[15%] flex flex-col items-center group cursor-pointer">
				<div class="w-16 bg-accent h-[240px] rounded-t"></div>
				<div class="mt-2 text-[10px] text-center">
					<div class="font-bold text-accent">75%</div>
					<div class="text-muted">Reports</div>
				</div>
			</div>

			<!-- Bottom Right Legend -->
			<div class="absolute bottom-4 right-4 flex items-center gap-4 text-[10px]">
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-accent rounded-full"></div>
					<span class="text-accent font-bold">WITH WREN</span>
				</div>
			</div>
		</div>
	</div>
</section>
