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
	import IconCode from "~icons/lucide/code";
	import IconBrainCircuit from "~icons/lucide/brain-circuit";
	import IconZap from "~icons/lucide/zap";
	import IconShield from "~icons/lucide/shield";
	import IconGauge from "~icons/lucide/gauge";
	import IconGitBranch from "~icons/lucide/git-branch";
</script>

<Hero
	centered={true}
	title="AI infrastructure for developers who build products, not models"
	subtitle="Integrate advanced machine learning and natural language processing into your applications without specialized ML talent. Start shipping intelligent features in minutes, not months."
	imageSrc="/generated/image-observational-documentary-style-image-of.webp"
/>
<LogoScroller
	label="Trusted by innovative tech companies"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="We provide production-ready machine learning and natural language processing through simple, developer-friendly APIs. Tech companies without specialized ML teams can integrate advanced AI capabilities into their products in hours instead of months. Transform your application with intelligent features while your team focuses on what they do best—building exceptional user experiences."
/>

<Testimonials
	testimonials={[
		{
			name: "Arjun Patel",
			position: "Engineering Lead",
			company: "DataFlow Systems",
			quote:
				"We reduced our ML integration timeline from 6 months to 3 weeks. The API documentation is incredibly clear, and we shipped our first intelligent feature in days without hiring a single ML engineer. That saved us $400K in specialized talent costs.",
			image: "/generated/image-documentary-style-portrait-of-a-professi.webp"
		},
		{
			name: "Maya Thompson",
			position: "VP of Product",
			company: "CloudScale",
			quote:
				"The risk mitigation alone justified our investment. Their proprietary models eliminated the compliance headaches we faced with competitor APIs. We passed our security audit on the first attempt, saving 8 weeks of remediation work and protecting a $2M enterprise deal.",
			image: "/generated/image-confident-african-american-female-execut.webp"
		},
		{
			name: "Chen Wei",
			position: "Founder & CTO",
			company: "Nexus AI",
			quote:
				"We cut our infrastructure costs by 60% compared to building in-house. The performance benchmarks they delivered were 3x faster than our previous solution, letting us handle 10x more requests without scaling our team. That's pure bottom-line impact.",
			image: "/generated/image-observational-intimate-portrait-of-a-pro.webp"
		}
	]}
/>

<Features
	title="Build intelligent features without hiring ML engineers"
	subtitle="Everything you need to integrate advanced AI capabilities into your product, from natural language processing to machine learning models, all through a developer-first API."
	features={[
		{
			title: "Simple integration that takes minutes, not months",
			description:
				"Add AI capabilities with a few lines of code using our intuitive REST API and comprehensive SDKs. Ship intelligent features in your next sprint without learning complex ML frameworks or managing infrastructure.",
			icon: IconCode,
			imageSrc: "/generated/image-2-close-up-shot-of-hands-typing-on-a-key.webp"
		},
		{
			title: "Pre-trained models for common use cases",
			description:
				"Access battle-tested NLP models for sentiment analysis, entity extraction, text classification, and summarization. Our proprietary models are fine-tuned on diverse datasets and outperform standard implementations.",
			icon: IconBrainCircuit,
			imageSrc: "/generated/image-1-documentary-style-portrait-of-a-develo.webp"
		},
		{
			title: "Scale from prototype to production seamlessly",
			description:
				"Start with generous free tier limits and scale to millions of requests without infrastructure headaches. Our managed service handles load balancing, caching, and optimization automatically.",
			icon: IconZap,
			imageSrc: "/generated/image-5-sunlit-modern-office-workspace-with-la.webp"
		},
		{
			title: "Enterprise-grade security and compliance",
			description:
				"Built for teams handling sensitive data with SOC 2 compliance, end-to-end encryption, and granular access controls. Your data stays yours—we never train models on customer information.",
			icon: IconShield,
			imageSrc: "/generated/image-3-two-developers-engaged-in-focused-conv.webp"
		},
		{
			title: "Real-time monitoring and analytics",
			description:
				"Track API usage, model performance, and cost metrics through intuitive dashboards. Get instant alerts when latency spikes or accuracy drops so you can maintain product quality.",
			icon: IconGauge,
			imageSrc: "/generated/image-4-developer-reviewing-code-on-a-laptop-a.webp"
		},
		{
			title: "Version control for AI models",
			description:
				"Deploy model updates with confidence using staged rollouts and instant rollbacks. Test changes against production traffic before full deployment to prevent regressions.",
			icon: IconGitBranch,
			imageSrc: "/generated/image-6-developer-seated-at-a-cozy-workspace-f.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Start building with AI today"
	subtitle="No ML expertise required"
	description="Join thousands of developers who ship intelligent features without the complexity. Get started in minutes with our interactive documentation and generous free tier. Transform your application before your competition does."
	imageSrc="/generated/image-documentary-style-portrait-of-a-happy-te.webp"
	callsToAction={[
		{
			href: '/get-started',
			label: 'Start free',
			variant: 'primary'
		},
		{
			href: '/documentation',
			label: 'View documentation',
			variant: 'secondary'
		}
	]}
/>
