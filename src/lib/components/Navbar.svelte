<script lang="ts">
	import { ChevronDown, ArrowRight } from 'lucide-svelte';
</script>

<div class="fixed top-0 left-0 w-full z-50 bg-background/80 backdrop-blur-md border-b border-white/5">
	<!-- Top Banner -->
	<div class="bg-background text-[11px] text-gray-400 py-2.5 text-center border-b border-white/5 tracking-wide">
		Specialized commercial counsel for startups. <a href="#" class="text-white hover:text-gray-300 transition-colors inline-flex items-center gap-1 group">Schedule a consultation <ArrowRight size={10} class="group-hover:translate-x-0.5 transition-transform" /></a>
	</div>

	<!-- Navbar -->
	<nav class="max-w-[1400px] mx-auto px-6 h-16 flex items-center justify-between">
		<!-- Logo -->
		<a href="/" class="text-3xl font-serif tracking-tight text-white pt-1">Sapien Esq</a>

		<!-- Links -->
		<div class="hidden md:flex items-center gap-8 text-[13px] font-medium text-gray-300">
			<button class="hover:text-white transition-colors flex items-center gap-1">
				Services <ChevronDown size={14} class="opacity-50" />
			</button>
			<button class="hover:text-white transition-colors flex items-center gap-1">
				Industries <ChevronDown size={14} class="opacity-50" />
			</button>
			<a href="#" class="hover:text-white transition-colors">Clients</a>
			<a href="#" class="hover:text-white transition-colors">About</a>
			<button class="hover:text-white transition-colors flex items-center gap-1">
				Resources <ChevronDown size={14} class="opacity-50" />
			</button>
		</div>

		<!-- Contact -->
		<a href="#" class="text-[13px] font-medium text-white hover:text-gray-300 transition-colors">
			Contact
		</a>
	</nav>
</div>
