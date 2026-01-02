<script lang="ts">
	import FeatureBlock from './FeatureBlock.svelte';
</script>

<!-- Block 1: Autonomous Research -->
<FeatureBlock 
	title="Autonomous research agents" 
	description="Deep research tasks completed end-to-end. From gathering sources to synthesizing insights, agents handle the entire workflow."
	buttons={[
		{ text: "START A RESEARCH TASK", icon: true },
		{ text: "LEARN MORE" }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-4 font-mono text-xs">
		<div class="flex items-center gap-2 border-b border-border pb-2 mb-4">
			<span class="text-green-500">●</span>
			<span class="text-muted">Researching: Market trends in AI</span>
		</div>
		<div class="space-y-2 text-[10px] text-muted">
			<div class="flex items-center gap-2">
				<span class="text-green-500">✓</span>
				<span>Analyzed 47 sources</span>
			</div>
			<div class="flex items-center gap-2">
				<span class="text-green-500">✓</span>
				<span>Extracted key insights</span>
			</div>
			<div class="flex items-center gap-2">
				<span class="text-accent animate-pulse">→</span>
				<span>Generating report...</span>
			</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 2: Operations Automation -->
<FeatureBlock 
	title="Operations on autopilot" 
	description="Automate repetitive ops tasks like data entry, monitoring, and reporting. Set it and let agents handle the rest."
	buttons={[
		{ text: "AUTOMATE A TASK", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full max-w-md bg-white border border-border rounded shadow-sm p-6 flex flex-col gap-4">
		<div class="flex items-center gap-2 text-xs font-mono text-muted">
			<div class="w-4 h-4 border border-current rounded-sm flex items-center justify-center">
				<div class="w-2 h-2 bg-current rounded-[1px]"></div>
			</div>
			Daily monitoring active
		</div>
		<div class="w-full bg-gray-100 h-1.5 rounded-full overflow-hidden">
			<div class="bg-green-500 h-full w-full"></div>
		</div>
		<div class="flex gap-1">
			{#each Array(20) as _, i}
				<div class="w-1 h-3 {i < 15 ? 'bg-green-200' : 'bg-gray-100'}"></div>
			{/each}
		</div>
		<div class="mt-2 flex items-center gap-2 text-[10px] text-muted font-mono uppercase">
			<span class="w-3 h-3 border border-green-500 rounded-full flex items-center justify-center text-green-500">✓</span>
			AUTOMATED
		</div>
	</div>
</FeatureBlock>

<!-- Block 3: Transparent Execution Logs -->
<FeatureBlock 
	title="Complete transparency" 
	description="See every step your agent takes. Full execution logs build trust and let you verify the work being done."
	buttons={[
		{ text: "VIEW SAMPLE LOG", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="border-b border-border bg-gray-50 text-muted p-2 font-semibold">
			EXECUTION LOG
		</div>
		{#each [
			{ time: "10:23:41", action: "Started research task", status: "complete" },
			{ time: "10:23:42", action: "Accessed 12 data sources", status: "complete" },
			{ time: "10:24:15", action: "Analyzed content patterns", status: "complete" },
			{ time: "10:24:58", action: "Cross-referenced findings", status: "complete" },
			{ time: "10:25:30", action: "Generating summary", status: "active" },
			{ time: "10:25:45", action: "Finalizing report", status: "pending" }
		] as log}
			<div class="grid grid-cols-[80px_1fr_60px] gap-2 p-2 border-b border-border/50 items-center">
				<div class="text-muted">{log.time}</div>
				<div class="text-foreground">{log.action}</div>
				<div class="flex items-center justify-end">
					{#if log.status === "complete"}
						<span class="text-green-500">✓</span>
					{:else if log.status === "active"}
						<span class="text-accent animate-pulse">●</span>
					{:else}
						<span class="text-gray-300">○</span>
					{/if}
				</div>
			</div>
		{/each}
	</div>
</FeatureBlock>

<!-- Block 4: Browser-Based Security -->
<FeatureBlock 
	title="Secure by design" 
	description="Agents run in your browser and isolated sandboxes. Your data stays under your control—no server-side processing of sensitive information."
	buttons={[
		{ text: "LEARN ABOUT SECURITY", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px] p-6 flex flex-col gap-4">
		<div class="flex items-center gap-3 pb-3 border-b border-border">
			<div class="w-8 h-8 rounded border-2 border-green-500 flex items-center justify-center">
				<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
					<path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/>
				</svg>
			</div>
			<div>
				<div class="font-semibold text-foreground">Browser Sandbox</div>
				<div class="text-muted">Isolated execution</div>
			</div>
		</div>
		<div class="space-y-2 text-muted">
			<div class="flex items-center gap-2">
				<span class="text-green-500">✓</span>
				<span>Client-side processing</span>
			</div>
			<div class="flex items-center gap-2">
				<span class="text-green-500">✓</span>
				<span>No data leaves your browser</span>
			</div>
			<div class="flex items-center gap-2">
				<span class="text-green-500">✓</span>
				<span>Sandboxed execution</span>
			</div>
			<div class="flex items-center gap-2">
				<span class="text-green-500">✓</span>
				<span>Full audit trail</span>
			</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 5: Multi-Tenant Workspaces -->
<FeatureBlock 
	title="Built for teams" 
	description="Multi-tenant workspaces let teams collaborate on agent tasks, share execution logs, and manage workflows together."
	buttons={[
		{ text: "CREATE WORKSPACE", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-4 flex flex-col gap-4">
		<div class="flex items-center justify-between border-b border-border pb-2">
			<div class="text-[10px] font-mono text-foreground font-semibold">
				Team Workspace
			</div>
			<div class="text-[10px] text-muted">5 members</div>
		</div>
		
		<!-- Team Members -->
		<div class="space-y-2">
			{#each [
				{ name: "Sarah Chen", role: "Admin", active: true },
				{ name: "Mike Torres", role: "Member", active: true },
				{ name: "Alex Kim", role: "Member", active: false }
			] as member}
				<div class="flex items-center justify-between p-2 rounded bg-gray-50">
					<div class="flex items-center gap-2">
						<div class="w-6 h-6 rounded-full bg-primary-200 flex items-center justify-center text-[10px] font-semibold">
							{member.name.split(' ').map(n => n[0]).join('')}
						</div>
						<div class="text-[10px]">
							<div class="font-medium">{member.name}</div>
							<div class="text-muted">{member.role}</div>
						</div>
					</div>
					<div class="flex items-center gap-1">
						<span class="w-1.5 h-1.5 rounded-full {member.active ? 'bg-green-500' : 'bg-gray-300'}"></span>
					</div>
				</div>
			{/each}
		</div>

		<div class="mt-auto pt-3 border-t border-border">
			<div class="text-[10px] text-muted font-mono">
				12 active tasks • 47 completed
			</div>
		</div>
	</div>
</FeatureBlock>
