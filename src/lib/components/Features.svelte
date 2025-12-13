<script lang="ts">
	import FeatureSection from './FeatureSection.svelte';
	import { FileText, Shield, Zap, Search, Globe, Scale } from 'lucide-svelte';
</script>

<section>
	<div class="py-24 text-center border-b border-white/5">
		<h2 class="text-3xl md:text-4xl font-serif">
			Comprehensive Commercial Legal Services <br />
			for Every Stage of Your Startup Journey
		</h2>
	</div>

	<!-- Feature 1: Commercial Playbooks -->
	<FeatureSection
		title="Commercial Playbooks"
		subtitle="Optimized for Speed & Simplicity"
		description="Custom playbooks for customer agreements and corporate partnerships that accelerate your sales cycle while protecting your interests."
		linkText="Learn More"
		reversed={false}
	>
		<!-- Playbook Visual -->
		<div class="bg-white text-black p-8 rounded shadow-2xl w-full max-w-md relative">
			<div class="mb-6">
				<h3 class="font-bold text-xl mb-4">Customer Agreement Playbook</h3>
				<div class="space-y-3">
					<div class="flex items-start gap-3">
						<div class="w-2 h-2 bg-black rounded-full mt-2"></div>
						<div>
							<p class="font-semibold text-sm">Payment Terms</p>
							<p class="text-xs text-gray-600">Net 30, annual prepay preferred</p>
						</div>
					</div>
					<div class="flex items-start gap-3">
						<div class="w-2 h-2 bg-black rounded-full mt-2"></div>
						<div>
							<p class="font-semibold text-sm">Liability Cap</p>
							<p class="text-xs text-gray-600">12 months fees paid, negotiate for enterprise</p>
						</div>
					</div>
					<div class="flex items-start gap-3">
						<div class="w-2 h-2 bg-black rounded-full mt-2"></div>
						<div>
							<p class="font-semibold text-sm">Data Processing</p>
							<p class="text-xs text-gray-600">Standard DPA, GDPR compliant</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</FeatureSection>

	<!-- Feature 2: Contract Negotiation -->
	<FeatureSection
		title="Contract Negotiation"
		subtitle="Close Deals Fast"
		description="Expert negotiation with Fortune 500 companies and enterprise customers. We understand startup risk profiles and optimize for deal velocity."
		linkText="Learn More"
		reversed={true}
	>
		<!-- Negotiation Visual -->
		<div class="w-full max-w-sm">
			<div class="bg-white text-black p-8 rounded shadow-2xl aspect-[4/3] flex flex-col items-center justify-center gap-4">
				<FileText size={48} strokeWidth={1.5} />
				<span class="text-2xl font-serif text-center">Enterprise SaaS<br/>Agreements</span>
			</div>
		</div>
	</FeatureSection>

	<!-- Feature 3: Deal Desk Services -->
	<FeatureSection
		title="Deal Desk Services"
		subtitle="Your Outside Legal Team"
		description="Act as your external deal desk for late-stage companies. Review contracts, manage negotiations, and provide real-time guidance to your sales team."
		linkText="Learn More"
		reversed={false}
	>
		<!-- Deal Desk Visual -->
		<div class="bg-white text-black p-6 rounded shadow-2xl w-full max-w-md text-xs">
			<div class="grid grid-cols-3 gap-4 mb-4 font-semibold border-b pb-2">
				<div>Deal</div>
				<div>Status</div>
				<div>Value</div>
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

	<!-- Feature 4: Stage-Based Services -->
	<FeatureSection
		title="Stage-Based Services"
		subtitle="Tailored to Your Growth"
		description="From first-time founders to pre-IPO unicorns, we provide the right level of legal support for your company stage and budget."
		linkText="Learn More"
		reversed={true}
	>
		<!-- Stage Services Visual -->
		<div class="grid grid-cols-2 gap-4 w-full max-w-md">
			<div class="bg-white text-black p-6 rounded shadow-lg flex flex-col items-center text-center gap-4 aspect-square justify-center hover:scale-[1.02] transition-transform duration-300">
				<Zap size={32} strokeWidth={1.5} />
				<span class="font-medium text-lg">Early Stage</span>
			</div>
			<div class="bg-white text-black p-6 rounded shadow-lg flex flex-col items-center text-center gap-4 aspect-square justify-center hover:scale-[1.02] transition-transform duration-300">
				<FileText size={32} strokeWidth={1.5} />
				<span class="font-medium text-lg">Growth Stage</span>
			</div>
			<div class="bg-white text-black p-6 rounded shadow-lg flex flex-col items-center text-center gap-4 aspect-square justify-center hover:scale-[1.02] transition-transform duration-300">
				<Shield size={32} strokeWidth={1.5} />
				<span class="font-medium text-lg">Pre-IPO</span>
			</div>
			<div class="bg-white text-black p-6 rounded shadow-lg flex flex-col items-center text-center gap-4 aspect-square justify-center hover:scale-[1.02] transition-transform duration-300">
				<Globe size={32} strokeWidth={1.5} />
				<span class="font-medium text-lg">Product Counsel</span>
			</div>
		</div>
	</FeatureSection>
</section>
