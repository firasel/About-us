<svelte:head>
	<title>About</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="py-16 min-h-screen">
	<div class="relative">
		<div class="container">
			<h1 class="text-center text-[50px] font-medium leading-[57px] text-[#17AEA4] mb-14">
				About us
			</h1>
			<img
				class="hidden md:block absolute max-w-lg xl:max-w-full right-0 -top-10 z-[-1]"
				src="/bg1.png"
				alt="bg"
			/>
			<img
				class="hidden md:block absolute max-w-lg xl:max-w-full left-0 top-0 z-[-1]"
				src="/bg2.png"
				alt="bg"
			/>
			<div
				class="border-[3px] rounded-[20px] border-primary box-border text-center flex items-center justify-center"
			>
				<div class="py-[72px] max-w-[938px]">
					<h2 class="text-[25px] font-bold leading-[29px] text-secondary mb-6">
						A fast and simple URl shortener
					</h2>
					<span class="w-20 h-[3px] bg-secondary block mb-5 mx-auto" />
					<p class="text-[22px] font-normal leading-[42px] text-secondary">
						Free URL Shortener for transforming long,ugly links into nice, memorable and trackable
						short URLs. Use it to shorten links for any social media platforms. blogs, SMS, emails,
						ads, or pretty much anywhere else you want to share them. Twitter, Facebook, Youtube,
						instagram, WhatsApp, emails, SMS,videos.
					</p>
				</div>
			</div>
		</div>
	</div>
	<div class="container mt-28">
		<h1 class="text-center text-[50px] font-medium leading-[57px] text-[#17AEA4] mb-14">
			How it Work
		</h1>
		<div class="grid grid-cols-1 md:grid-cols-3 gap-12 text-center relative">
			<div class="px-8 py-20 border-[3px] rounded-[20px] border-primary">
				<h2 class="text-[40px] font-medium leading-[46px] capitalize mb-9">Copy Long URL</h2>
				<p class="text-[20px] font-light text-black leading-[34px] break-words">
					https://www.thrdailystar.net/business/global-economy/news/german-industrial-output-falls-more-expected-3241836
				</p>
			</div>
			<div class="px-8 py-20 border-[3px] rounded-[20px] border-primary">
				<h2 class="text-[40px] font-medium leading-[46px] capitalize mb-14">
					Paste into the sortener ber
				</h2>
				<p class="text-[20px] font-light text-black leading-[34px] break-words">
					Random short: Teely.me/TreRB6T or Brand short: Teel.me /DIFT02023
				</p>
			</div>
			<div class="px-8 py-20 border-[3px] rounded-[20px] border-primary">
				<h2 class="text-[40px] font-medium leading-[46px] capitalize mb-14">track every click</h2>
				<p class="text-[20px] font-light text-black leading-[34px] break-words">
					Track every click on hourly, daily, monthly, and yearly basis.
				</p>
			</div>
		</div>
	</div>
</section>
