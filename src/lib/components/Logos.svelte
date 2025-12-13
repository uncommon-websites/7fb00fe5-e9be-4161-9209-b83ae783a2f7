<script lang="ts">
	import { ChevronRight } from 'lucide-svelte';
</script>

<section class="py-12 border-b border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-10">
			<p class="text-xl font-serif text-gray-200">Trusted by Leading Companies</p>
		</div>

		<!-- Logos Grid - Using text for now as I don't have the SVGs, but styling to look like logos -->
		<div class="flex flex-wrap justify-center items-center gap-x-16 gap-y-10 opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
			<span class="text-2xl font-sans font-bold tracking-tight text-white">Microsoft</span>
			<span class="text-xl font-sans font-bold text-white">Square</span>
			<span class="text-lg font-serif font-bold tracking-wide text-white">Wells Fargo</span>
			<span class="text-xl font-sans font-bold text-white">JPMorgan Chase</span>
			<span class="text-2xl font-sans font-bold tracking-tight text-white">Google</span>
			<span class="text-xl font-sans font-bold text-white">Foursquare</span>
		</div>

		<div class="text-center mt-12">
			<a href="#" class="text-sm text-gray-400 hover:text-white transition-colors inline-flex items-center gap-1">
				See Client Work <ChevronRight size={12} />
			</a>
		</div>
	</div>
</section>
