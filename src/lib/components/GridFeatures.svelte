<script lang="ts">
	import { ShieldCheck, Bot, Scale, Globe } from 'lucide-svelte';
</script>

<section class="py-32 border-b border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-24">
			<h2 class="text-4xl md:text-5xl font-serif">Why Startups Choose Sapien Esq</h2>
		</div>

		<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-x-8 gap-y-16">
			<div class="flex flex-col gap-6">
				<ShieldCheck size={28} class="text-white" strokeWidth={1.5} />
				<div>
					<h3 class="text-lg font-medium mb-3">Stanford Network Advantage</h3>
					<p class="text-gray-400 leading-relaxed text-sm">
						Stanford JD with deep connections to Silicon Valley's top venture law firms and startup ecosystem.
					</p>
				</div>
			</div>

			<div class="flex flex-col gap-6">
				<Bot size={28} class="text-white" strokeWidth={1.5} />
				<div>
					<h3 class="text-lg font-medium mb-3">Optimized for Speed</h3>
					<p class="text-gray-400 leading-relaxed text-sm">
						Close deals fast with streamlined processes that understand startup velocity and growth priorities.
					</p>
				</div>
			</div>

			<div class="flex flex-col gap-6">
				<Scale size={28} class="text-white" strokeWidth={1.5} />
				<div>
					<h3 class="text-lg font-medium mb-3">Startup Risk Expertise</h3>
					<p class="text-gray-400 leading-relaxed text-sm">
						Deep understanding of startup risk profiles and capital constraints from counseling hundreds of companies.
					</p>
				</div>
			</div>

			<div class="flex flex-col gap-6">
				<Globe size={28} class="text-white" strokeWidth={1.5} />
				<div>
					<h3 class="text-lg font-medium mb-3">BigLaw Complement</h3>
					<p class="text-gray-400 leading-relaxed text-sm">
						Work seamlessly alongside your corporate counsel, handling commercial and tech transactions.
					</p>
				</div>
			</div>
		</div>
	</div>
</section>
