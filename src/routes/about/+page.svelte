<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
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
<Culture {values} generating />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	generating
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	generating
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	generating
	title="Ready to collaborate?"
	subtitle="Let's create something amazing"
	description="Join the companies already leveraging our expertise to transform their digital presence and achieve their business goals."
/>
