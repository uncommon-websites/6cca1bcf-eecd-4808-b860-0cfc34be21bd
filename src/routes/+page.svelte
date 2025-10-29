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
	import IconUsers from "~icons/lucide/users";
	import IconZap from "~icons/lucide/zap";
	import IconCalendarCheck from "~icons/lucide/calendar-check";
	import IconMap from "~icons/lucide/map";
	import IconUserPlus from "~icons/lucide/user-plus";
	import IconSmartphone from "~icons/lucide/smartphone";
</script>

<Hero
	centered={false}
	title="Turn spontaneous travel ideas into weekend adventures"
	subtitle="Coordinate with friends in real-time and discover destinations together, no planning paralysis required"
	imageSrc="/generated/image-a-diverse-group-of-3-4-young-professiona.webp"
	callsToAction={[
		{
			href: "#",
			label: "Start planning"
		},
		{
			href: "#",
			label: "See how it works"
		}
	]}
/>
<LogoScroller
	label="Trusted by teams at"
	logoUrls={[
		'https://cdn.brandfetch.io/airbnb.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/wework.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bumble.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/spotify.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Group travel, reimagined"
	text="JourneyGo helps young professionals turn spontaneous weekend getaway ideas into reality. We coordinate your friend group in real-time, curate destinations that match everyone's vibe, and eliminate the planning paralysis that kills most trips before they start."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Kapoor",
			position: "Marketing Manager",
			company: "Zenith Digital",
			quote:
				"We went from endless group chats to a confirmed Napa trip in under 20 minutes. JourneyGo eliminated the back-and-forth that usually kills our weekend plans.",
			image: "/generated/image-candid-environmental-portrait-of-a-confi.webp"
		},
		{
			name: "Marcus Chen",
			position: "Product Designer",
			company: "Atlas Labs",
			quote:
				"Finally coordinated our friend group's bachelor party without the usual planning chaos. Real-time voting on destinations saved us hours of indecision.",
			image: "/generated/image-candid-environmental-portrait-of-a-frien.webp"
		},
		{
			name: "Sofia Ramirez",
			position: "Software Engineer",
			company: "Frontier Tech",
			quote:
				"Spontaneous coastal getaway with college friends that actually happened. We discovered destinations we'd never have found searching individually.",
			image: "/generated/image-candid-environmental-portrait-of-a-confi.webp"
		}
	]}
/>

<Features
	title="Plan trips together, not alone"
	subtitle="Everything your friend group needs to turn ideas into adventures"
	features={[
		{
			title: "Real-time group coordination",
			description:
				"See everyone's availability and preferences instantly, so you spend less time texting back and forth and more time actually going places.",
			icon: IconUsers,
			imageSrc: "/generated/image-young-professionals-in-their-20s-and-30s.webp"
		},
		{
			title: "Spontaneous trip discovery",
			description:
				"Browse curated weekend destinations that match your group's vibe and budget, designed for friends who decide Thursday to leave Friday.",
			icon: IconZap,
			imageSrc: "/generated/image-a-diverse-group-of-friends-in-their-late.webp"
		},
		{
			title: "Quick decision-making",
			description:
				"Vote on destinations, activities, and dates with simple swipes that eliminate planning paralysis and keep momentum alive.",
			icon: IconCalendarCheck,
			imageSrc: "/generated/image-a-group-of-friends-in-a-warmly-lit-urban.webp"
		},
		{
			title: "Pre-built itinerary templates",
			description:
				"Start with proven weekend plans created by real travelers, then customize them to fit your group's style without building from scratch.",
			icon: IconMap,
			imageSrc: "/generated/image-friends-in-their-late-20s-exploring-a-ne.webp"
		},
		{
			title: "Seamless friend invites",
			description:
				"Add friends with a single tap and watch your travel circle grow as trips get easier to coordinate with the people you actually want to go with.",
			icon: IconUserPlus,
			imageSrc: "/generated/image-a-group-of-friends-in-their-late-20s-to-.webp"
		},
		{
			title: "Mobile-first experience",
			description:
				"Plan entire trips from your phone while commuting, waiting in line, or lounging on the couch because spontaneous doesn't mean complicated.",
			icon: IconSmartphone,
			imageSrc: "/generated/image-young-professionals-on-a-road-trip-adven.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
