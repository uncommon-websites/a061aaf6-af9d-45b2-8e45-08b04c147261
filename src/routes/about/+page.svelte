<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Data-driven precision",
			description: "Every targeting decision backed by real transaction data and behavioral insights, not guesswork."
		},
		{
			title: "Startup empathy",
			description: "Built by founders who know the pressure of proving traction with limited runway."
		},
		{
			title: "Profitable growth",
			description: "Success means lowering your CAC while finding customers who actually drive recurring revenue."
		}
	];
</script>

<SecondaryHero
	title="Smarter ads, stronger growth"
	subtitle="Find customers who actually pay"
	imageSrc="/generated/image-a-diverse-group-of-young-professionals-c.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Seed-stage B2B SaaS startups waste 40–60% of their limited ad spend on broad audience targeting that doesn't convert to recurring revenue. Growth marketers are flying blind—unable to identify the high-value users who stick around and drive MRR. With burn rates climbing and pressure to show traction before Series A, most are spending more and getting less.",
		"Our platform automatically pulls in real-world transaction data and breaks it down by retention, spend patterns, and behavioral traits. We rebuild your audience around what actually matters—who pays and stays. Then we surface these revenue-driving personas as precise lookalike segments you can run in low-cost channels. No complex dashboards. No hours spent on tagging. Just a clearer path to profitable growth.",
		"Our customers cut cost-per-acquisition by 20–35% within weeks. Better targeting means more revenue per dollar spent and fewer wasted impressions. With our pay-per-whale-identified model, you only pay when we identify users who actually move the needle. Our mission is to help 1,000 SaaS startups reach Series A efficiently—because finding product-market fit shouldn't mean draining your entire runway."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and investors sections removed as no information available -->

<!-- CTA Section -->
<CallToAction
	title="Stop wasting ad spend on guesswork"
	subtitle="Start targeting customers who actually convert"
	description="Join the seed-stage B2B SaaS startups already cutting their customer acquisition costs by 20-35% with data-driven targeting that identifies revenue-driving personas."
/>
