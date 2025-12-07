<script lang="ts">
	import FeatureSection from './FeatureSection.svelte';
	import { FileText, Shield, Zap, Search, Globe, Scale } from 'lucide-svelte';
</script>

<section>
	<div class="py-24 text-center border-b border-white/5">
		<h2 class="text-3xl md:text-4xl font-serif">
			Augment All of Your Work on <br />
			One Integrated, Secure Platform
		</h2>
	</div>

	<!-- Feature 1: Assistant -->
	<FeatureSection
		title="Assistant"
		subtitle="Tailored to Your Expertise"
		description="Delegate complex tasks in natural language to your domain-specific personal assistant."
		linkText="Explore Assistant"
		reversed={false}
	>
		<!-- Assistant UI Mockup -->
		<div class="bg-white text-black p-8 rounded shadow-2xl w-full max-w-md relative">
			<p class="mb-6 font-serif text-lg leading-relaxed">
				As requested, I am providing a detailed summary of the main interim operating covenants that restrict AavantiBio during the period between the signing and closing of the merger agreement with Solid Biosciences Inc. <sup class="bg-gray-200 px-1 rounded text-xs">1</sup> These covenants are designed to ensure that AavantiBio maintains its business operations in a manner consistent with past practices and does not undertake any actions that could adversely affect the merger. <sup class="bg-gray-200 px-1 rounded text-xs">2</sup> <sup class="bg-gray-200 px-1 rounded text-xs">3</sup> Conduct of Business in the Ordinary Course Aav...
			</p>
			<div class="absolute bottom-4 right-4 w-3 h-3 bg-gray-400 rounded-full animate-pulse"></div>
		</div>
	</FeatureSection>

	<!-- Feature 2: Knowledge -->
	<FeatureSection
		title="Knowledge"
		subtitle="Rapid Research, Grounded Results"
		description="Get answers to complex research questions across multiple domains in legal, regulatory, and tax with accurate citations."
		linkText="Explore Knowledge"
		reversed={true}
	>
		<!-- Knowledge UI Mockup -->
		<div class="w-full max-w-sm">
			<div class="bg-white text-black p-8 rounded shadow-2xl aspect-[4/3] flex items-center justify-center">
				<span class="text-3xl font-serif">Tax</span>
			</div>
		</div>
	</FeatureSection>

	<!-- Feature 3: Vault -->
	<FeatureSection
		title="Vault"
		subtitle="Secure Project Workspaces"
		description="Upload, store, and analyze thousands of documents using powerful generative AI."
		linkText="Explore Vault"
		reversed={false}
	>
		<!-- Vault UI Mockup -->
		<div class="bg-white text-black p-6 rounded shadow-2xl w-full max-w-md text-xs">
			<div class="grid grid-cols-3 gap-4 mb-4 font-semibold border-b pb-2">
				<div>File Name</div>
				<div>Parties</div>
				<div>Clause</div>
			</div>
			{#each [1, 2, 3, 4, 5, 6, 7] as i}
				<div class="grid grid-cols-3 gap-4 mb-3 opacity-60">
					<div class="h-2 bg-gray-200 rounded w-3/4"></div>
					<div class="h-2 bg-gray-200 rounded w-full"></div>
					<div class="h-2 bg-gray-200 rounded w-5/6"></div>
				</div>
			{/each}
		</div>
	</FeatureSection>

	<!-- Feature 4: Workflows -->
	<FeatureSection
		title="Workflows"
		subtitle="Streamline Your Work"
		description="Multi-model agents designed to collaborate with professionals to deliver precise, purpose-built work product. More coming soon."
		linkText="Explore Workflows"
		reversed={true}
	>
		<!-- Workflows UI Mockup -->
		<div class="grid grid-cols-2 gap-4 w-full max-w-md">
			<div class="bg-white text-black p-6 rounded shadow-lg flex flex-col items-center text-center gap-4 aspect-square justify-center hover:scale-[1.02] transition-transform duration-300">
				<Shield size={32} strokeWidth={1.5} />
				<span class="font-medium text-lg">Assess Risks</span>
			</div>
			<div class="bg-white text-black p-6 rounded shadow-lg flex flex-col items-center text-center gap-4 aspect-square justify-center hover:scale-[1.02] transition-transform duration-300">
				<FileText size={32} strokeWidth={1.5} />
				<span class="font-medium text-lg">Support Argument</span>
			</div>
			<div class="bg-white text-black p-6 rounded shadow-lg flex flex-col items-center text-center gap-4 aspect-square justify-center hover:scale-[1.02] transition-transform duration-300">
				<Globe size={32} strokeWidth={1.5} />
				<span class="font-medium text-lg">Translation</span>
			</div>
			<div class="bg-white text-black p-6 rounded shadow-lg flex flex-col items-center text-center gap-4 aspect-square justify-center hover:scale-[1.02] transition-transform duration-300">
				<Zap size={32} strokeWidth={1.5} />
				<span class="font-medium text-lg">Credit Agreement</span>
			</div>
		</div>
	</FeatureSection>
</section>
