<script lang="ts">
	import { ChevronRight } from 'lucide-svelte';
</script>

<section class="relative py-32 border-b border-white/5 overflow-hidden">
	<div class="max-w-[1400px] mx-auto px-6 relative z-10">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<!-- Image -->
			<div class="relative rounded-lg overflow-hidden aspect-video lg:aspect-[4/3] bg-gray-800 shadow-2xl">
				<img 
					src="/generated/image-professional-headshot-of-head-of-legal-a-1765652540337-1.webp" 
					alt="Elliot Ginsburg, Head of Legal at Postscript" 
					class="w-full h-full object-cover opacity-70 hover:scale-105 transition-transform duration-700"
				/>
				<div class="absolute inset-0 flex items-center justify-center">
					<span class="text-5xl font-bold tracking-tight text-white drop-shadow-lg">Postscript</span>
				</div>
			</div>

			<!-- Content -->
			<div>
				<div class="mb-10">
					<span class="inline-block px-3 py-1 border border-white/20 rounded text-[10px] uppercase tracking-widest text-gray-300 mb-8">Client Success</span>
					<blockquote class="text-3xl md:text-4xl font-serif leading-[1.2] mb-10 font-light">
						“Rich provided flexibility in time and price, took the time to understand our product deeply, and delivered quality work that improved our sales cycles and customer relations.”
					</blockquote>
					<div class="flex items-center justify-between flex-wrap gap-6">
						<div>
							<cite class="not-italic font-medium block text-lg">Elliot Ginsburg</cite>
							<span class="text-sm text-gray-400">Head of Legal, Postscript</span>
						</div>
						<button class="bg-white text-black px-6 py-3 rounded text-sm font-medium hover:bg-gray-200 transition-colors">
							Read Client Success
						</button>
					</div>
				</div>

				<!-- Dots -->
				<div class="flex gap-2 justify-center lg:justify-start mt-12">
					<button class="w-2 h-2 rounded-full bg-white"></button>
					<button class="w-2 h-2 rounded-full bg-gray-700 hover:bg-gray-500 transition-colors"></button>
					<button class="w-2 h-2 rounded-full bg-gray-700 hover:bg-gray-500 transition-colors"></button>
					<button class="w-2 h-2 rounded-full bg-gray-700 hover:bg-gray-500 transition-colors"></button>
				</div>
			</div>
		</div>
	</div>
</section>
