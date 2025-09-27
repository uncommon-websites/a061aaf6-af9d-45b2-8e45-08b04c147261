<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconDatabase from "~icons/lucide/database";
	import IconUsers from "~icons/lucide/users";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconActivity from "~icons/lucide/activity";
	import IconTarget from "~icons/lucide/target";
	import IconDollarSign from "~icons/lucide/dollar-sign";
</script>

<Hero
	title="Find the customers who actually pay"
	subtitle="Spend less to acquire the users who matter"
	imageSrc="/generated/image-a-professional-growth-marketer-in-a-mode.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linear.app/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="We automatically enrich your transaction data with behavioral insights to identify the customers who actually drive revenue. Growth marketers at seed-stage B2B SaaS startups use our platform to cut customer acquisition costs by 20-35% by targeting high-value personas in low-cost channels. Stop wasting ad spend on broad campaigns that don't convert — discover which customers are worth acquiring and where to find more of them."
/>

<Testimonials
	testimonials={[
		{
			name: "Carmen Rodriguez",
			position: "VP of Growth",
			company: "CloudScale",
			quote:
				"We cut our CAC by 32% in just 8 weeks. Their behavioral insights helped us identify which customer segments actually convert to paid plans.\nNo more burning $15k/month on broad campaigns that don't work.",
			image: "/generated/image-professional-headshot-of-a-confident-his.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Co-founder & CMO",
			company: "DataFlow",
			quote:
				"Finally, we can target customers who actually pay. Their platform showed us our high-value personas were in completely different channels than we thought.\nWe're now scaling profitably toward Series A.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		},
		{
			name: "Jennifer Chen",
			position: "Head of Marketing",
			company: "AutomateNow",
			quote:
				"The pay-per-whale-identified pricing was perfect for our tight runway. We identified 3 whale customers in our first month that covered our investment 5x over.\nThis platform literally saved our startup.",
			image: "/generated/image-professional-headshot-of-a-confident-asi.webp"
		}
	]}
/>

<Features
	title="Stop wasting ad spend on the wrong customers"
	subtitle="Identify and target the users who actually drive revenue growth"
	features={[
		{
			title: "Automatic transaction enrichment",
			description: "Transform raw transaction data into behavioral insights that reveal which customers drive actual MRR growth.",
			icon: IconDatabase
		},
		{
			title: "Revenue-driving persona identification",
			description: "Pinpoint the exact customer profiles that convert from trial to paid with 3x higher lifetime value.",
			icon: IconUsers
		},
		{
			title: "Low-cost channel optimization",
			description: "Automatically shift ad spend to the channels where your best customers actually discover you.",
			icon: IconTrendingUp
		},
		{
			title: "Real-time CAC monitoring",
			description: "Track customer acquisition costs across all channels with guaranteed 20% reduction or your money back.",
			icon: IconActivity
		},
		{
			title: "Behavioral targeting engine",
			description: "Stop wasting budget on broad campaigns by targeting users who match your highest-value customer behaviors.",
			icon: IconTarget
		},
		{
			title: "Pay-per-whale pricing",
			description: "Only pay when we identify a customer who becomes a paying subscriber, eliminating the risk of another failed analytics tool.",
			icon: IconDollarSign
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
