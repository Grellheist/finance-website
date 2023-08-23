<script lang="ts">
	import '../app.css';
	import Navbar from '../components/Navbar.svelte';
	import ScrollToTop from '../components/ScrollToTop.svelte';
	import Prices from '../components/Prices.svelte';
	import Reviews from '../components/Reviews.svelte';
</script>

<Navbar />

<div
	class="flex flex-col lg:flex-row gap-12 items-center justify-center p-12 mb-12 bg-[#EDFDF2] select-text"
	id="millionare"
>
	<div class="flex flex-col gap-12 items-center">
		<h1
			class="max-w-[590px] text-base-text text-4xl font-semibold md:leading-[64px] text-center tracking-tight sm:text-5xl lg:max-w-[460px] lg:text-5xl lg:text-left lg:m-0 xl:max-w-[550px] xl:text-6xl"
		>
			You too can become a <span class="text-transparent bg-clip-text z-20 bg-green-700"
				>millionare</span
			>! <s>Maybe</s>
		</h1>
		<p
			class="mt-6 mb-8 max-w-[400px] text-base font-serif text-center font-light text-gray-600 lg:text-left lg:mx-0 lg:max-w-[520px]"
		>
			Not by using our website, but if you try hard enough and invest in the correct stuff, who
			knows.
		</p>
		<div class="mt-9 flex flex-col justify-start xl:space-x-4 xl:flex-row">
			<div class="flex items-center w-64 lg:w-72 h-20">
				<svg
					width="70"
					height="52"
					viewBox="0 0 42 42"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<rect width="42" height="42" rx="12" fill="#DFFCE9" />
					<g clip-path="url(#clip0_3202_51666)">
						<path
							d="M27 17H26V15C26 12.24 23.76 10 21 10C18.24 10 16 12.24 16 15V17H15C13.9 17 13 17.9 13 19V29C13 30.1 13.9 31 15 31H27C28.1 31 29 30.1 29 29V19C29 17.9 28.1 17 27 17ZM18 15C18 13.34 19.34 12 21 12C22.66 12 24 13.34 24 15V17H18V15ZM27 29H15V19H27V29ZM21 26C22.1 26 23 25.1 23 24C23 22.9 22.1 22 21 22C19.9 22 19 22.9 19 24C19 25.1 19.9 26 21 26Z"
							fill="#0D772F"
						/>
					</g>
					<defs>
						<clipPath id="clip0_3202_51666">
							<rect width="24" height="24" fill="white" transform="translate(9 9)" />
						</clipPath>
					</defs>
				</svg>
				<p class="ml-5 font-light font-serif text-[#454843]">Our website is safe and secure</p>
			</div>
			<div class="flex items-center w-64 lg:w-72 h-20">
				<svg
					width="70"
					height="52"
					viewBox="0 0 42 42"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<rect width="42" height="42" rx="12" fill="#DFFCE9" />
					<g clip-path="url(#clip0_3202_51658)">
						<path
							d="M13 15H31V13H13C11.9 13 11 13.9 11 15V26H9V29H23V26H13V15ZM32 17H26C25.45 17 25 17.45 25 18V28C25 28.55 25.45 29 26 29H32C32.55 29 33 28.55 33 28V18C33 17.45 32.55 17 32 17ZM31 26H27V19H31V26Z"
							fill="#0D772F"
						/>
					</g>
					<defs>
						<clipPath id="clip0_3202_51658">
							<rect width="24" height="24" fill="white" transform="translate(9 9)" />
						</clipPath>
					</defs>
				</svg>
				<p class="ml-5 font-light font-serif text-[#454843]">You can access anywhere and anytime</p>
			</div>
		</div>
	</div>
	<img src="/images/graph.jpg" alt="Graph on tablet" loading="lazy" class="w-[640px] rounded" />
</div>
<ScrollToTop />
<div
	class="flex flex-col gap-12 items-center justify-center p-12 mb-12 bg-[#FEFDF9] select-text"
	id="tutorial"
>
	<div class="flex flex-col lg:flex-row gap-12 items-center">
		<img src="/images/graph-2.jpg" alt="Graph on laptop" loading="lazy" class="w-[640px] rounded" />
		<div class="flex-col gap-12 flex items-center">
			<h2
				class="max-w-[590px] text-base-text text-4xl font-semibold md:leading-[64px] text-center tracking-tight sm:text-5xl lg:max-w-[460px] lg:text-5xl lg:text-left lg:m-0 xl:max-w-[550px] xl:text-6xl"
			>
				Want to become a rich person? Here's how
			</h2>
			<div
				class="w-full mt-10 mb-10 grid grid-cols-1 sm:grid-cols-2 gap-y-10 gap-x-10 md:gap-y-8 md:gap-x-14"
			>
				<div class="lg:mb-0">
					<div class="flex flex-row md:flex-col">
						<span
							class="rounded-xl mb-4 max-w-[47px] bg-[#DFFCE9] text-[#0D772F] flex items-center justify-center px-3 pt-3 pb-2 text-center text-xl font-bold leading-0 tracking-wider mr-3"
							>01</span
						>
						<div>
							<p
								class="text-lg font-serif sm:text-xl max-w-[300px] text-base-text font-semibold md:max-w-[222px] tracking-wide mb-2 leading-6"
							>
								Earn a lot of money
							</p>
							<span
								class="font-light font-serif sm:max-w-[400px] tracking-wide text-base block text-[#5C5F5A]"
								>Honestly I dunno how you would do that but it is within the realm of possibility.
								So just do it (it's a joke you should still invest even if you don't earn a lot).</span
							>
						</div>
					</div>
				</div>
				<div class="lg:mb-0">
					<div class="flex flex-row md:flex-col">
						<span
							class="rounded-xl mb-4 max-w-[47px] bg-[#DFFCE9] text-[#0D772F] flex items-center justify-center px-3 pt-3 pb-2 text-center text-xl font-bold leading-0 tracking-wider mr-3"
							>02</span
						>
						<div>
							<p
								class="text-lg font-serif sm:text-xl max-w-[300px] text-base-text font-semibold md:max-w-[222px] tracking-wide mb-2 leading-6"
							>
								Don't spend more than you earn
							</p>
							<span
								class="font-light font-serif sm:max-w-[400px] tracking-wide text-base block text-[#5C5F5A]"
								>I mean this is pretty straightforward right?</span
							>
						</div>
					</div>
				</div>
				<div class="lg:mb-0">
					<div class="flex flex-row md:flex-col">
						<span
							class="rounded-xl mb-4 max-w-[47px] bg-[#DFFCE9] text-[#0D772F] flex items-center justify-center px-3 pt-3 pb-2 text-center text-xl font-bold leading-0 tracking-wider mr-3"
							>03</span
						>
						<div>
							<p
								class="text-lg font-serif sm:text-xl max-w-[300px] text-base-text font-semibold md:max-w-[222px] tracking-wide mb-2 leading-6"
							>
								Invest your money
							</p>
							<span
								class="font-light font-serif sm:max-w-[400px] tracking-wide text-base block text-[#5C5F5A]"
								>Investing is just like buying a money printer. You can make your money become more
								money. Please don't buy a money printer.</span
							>
						</div>
					</div>
				</div>
				<div class="lg:mb-0">
					<div class="flex flex-row md:flex-col">
						<span
							class="rounded-xl mb-4 max-w-[47px] bg-[#DFFCE9] text-[#0D772F] flex items-center justify-center px-3 pt-3 pb-2 text-center text-xl font-bold leading-0 tracking-wider mr-3"
							>04</span
						>
						<div>
							<p
								class="text-lg font-serif sm:text-xl max-w-[300px] text-base-text font-semibold md:max-w-[222px] tracking-wide mb-2 leading-6"
							>
								Use a money planner
							</p>
							<span
								class="font-light font-serif sm:max-w-[400px] tracking-wide text-base block text-[#5C5F5A]"
								>You're basically assuming total control over your money by doing this (real
								advice).</span
							>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<div
	class="flex flex-col gap-12 items-center justify-center p-12 bg-[#EDFDF2] select-none"
	id="reviews"
>
	<h2
		class="max-w-[590px] text-base-text text-4xl font-semibold md:leading-[64px] tracking-tight sm:text-5xl lg:max-w-[460px] lg:text-5xl lg:text-left lg:m-0 xl:max-w-[550px] xl:text-6xl"
	>
		What users think of us
	</h2>
	<div class="flex flex-col lg:flex-row max-w-5xl mx-auto gap-12 text-center">
		<Reviews
			src="/testimonials/kylen.jpg"
			name="Kylen Frerking"
			testimonial="Ever since I've started using this website I've been more careful with my spendings. It's awesome!"
		/>
		<Reviews
			src="/testimonials/clare.jpg"
			name="Clare Wedi"
			testimonial="I have been making more money and I'm almost a rich person. It's all thanks to this website! It actually made me earn more!"
		/>
		<Reviews
			src="/testimonials/darren.jpg"
			name="Darren Kremer"
			testimonial="One day I saw a homeless guy on the street. I told him I use this website and he gave me money. Splendid."
		/>
	</div>
</div>
<div
	class="flex flex-col gap-12 items-center justify-center p-12 bg-[#FEFDF9] select-none"
	id="prices"
>
	<h1
		class="max-w-[590px] text-base-text text-4xl font-semibold md:leading-[64px] text-center tracking-tight sm:text-5xl lg:max-w-[460px] lg:text-5xl lg:text-left lg:m-0 xl:max-w-[550px] xl:text-6xl"
	>
		Our prices
	</h1>
	<div class="flex flex-col xl:flex-row gap-12">
		<Prices
			name="Free Plan"
			price={0}
			benefits={['Money planner']}
			notIncluded={[
				'Unlimited supply of "Good morning" messages',
				'3 free memes everyday',
				'7 tons of feathers delivered to you',
				'I will come to your house once a day',
				'Free girlfriend',
				'Free gaming PC',
				'You are going to be rich'
			]}
		/>
		<Prices
			name="Aristocrat Plan"
			price={39}
			benefits={[
				'Money planner',
				'Unlimited supply of "Good morning" messages',
				'3 free memes everyday',
				'7 tons of feathers delivered to you',
				'I will come to your house once a day'
			]}
			notIncluded={['Free girlfriend', 'Free gaming PC', 'You are going to be rich']}
		/>
		<Prices
			name="Jeff Bezos Plan"
			price={999}
			benefits={[
				'Money planner',
				'Unlimited supply of "Good morning" messages',
				'3 free memes everyday',
				'7 tons of feathers delivered to you',
				'I will come to your house once a day',
				'Free girlfriend',
				'Free gaming PC',
				'You are going to be rich'
			]}
			notIncluded={[]}
		/>
	</div>
</div>
