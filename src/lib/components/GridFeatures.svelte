<script lang="ts">
	import { ShieldCheck, Bot, Scale, Globe } from 'lucide-svelte';
</script>

<section class="py-32 border-b border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-24">
			<h2 class="text-4xl md:text-5xl font-serif">Unlock Professional Class AI for Your Firm</h2>
		</div>

		<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-x-8 gap-y-16">
			<div class="flex flex-col gap-6">
				<ShieldCheck size={28} class="text-white" strokeWidth={1.5} />
				<div>
					<h3 class="text-lg font-medium mb-3">Enterprise-Grade Security</h3>
					<p class="text-gray-400 leading-relaxed text-sm">
						Robust, industry-standard protection with zero training on your data.
					</p>
				</div>
			</div>

			<div class="flex flex-col gap-6">
				<Bot size={28} class="text-white" strokeWidth={1.5} />
				<div>
					<h3 class="text-lg font-medium mb-3">Agentic Workflows</h3>
					<p class="text-gray-400 leading-relaxed text-sm">
						Produce expert-quality work product for complex workflows, with no prompting required.
					</p>
				</div>
			</div>

			<div class="flex flex-col gap-6">
				<Scale size={28} class="text-white" strokeWidth={1.5} />
				<div>
					<h3 class="text-lg font-medium mb-3">Domain-Specific Models</h3>
					<p class="text-gray-400 leading-relaxed text-sm">
						High-performing custom models built for complex professional work.
					</p>
				</div>
			</div>

			<div class="flex flex-col gap-6">
				<Globe size={28} class="text-white" strokeWidth={1.5} />
				<div>
					<h3 class="text-lg font-medium mb-3">24/7 Customer Support</h3>
					<p class="text-gray-400 leading-relaxed text-sm">
						White glove support to resolve issues and maximize your Harvey experience.
					</p>
				</div>
			</div>
		</div>
	</div>
</section>
