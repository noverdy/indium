<main class="bg-zinc-950 text-white h-full flex flex-col">
	<nav class="grid grid-cols-3 items-center px-4 py-6 text-xl">
		<div class="grow">
			<button class="border border-white w-12 h-12 rounded-full">
				<i class="fa-solid fa-magnifying-glass" />
			</button>
		</div>
		<h1 class="text-center">Home</h1>
		<div class="grow flex place-content-end">
			<img src="/placeholder.jpg" alt="user" class="rounded-full w-12 h-12" />
		</div>
	</nav>

	<section class="grow bg-white text-black rounded-t-[3.5rem] px-4 overflow-y-scroll relative">
		<div class="bg-white sticky top-0 left-0 right-0 py-2 mb-8">
			<div class="bg-neutral-200 h-1 mx-auto w-8 rounded-full" />
		</div>
		<div class="flex flex-col gap-12">
			{#each { length: 10 } as _}
				<a href="/chat/id">
					<section class="flex gap-4">
						<img src="/placeholder.jpg" alt="partner" class="w-14 h-14 rounded-full" />
						<div class="grow">
							<span class="flex justify-between items-center">
								<h2 class="text-xl font-semibold">Chat name</h2>
								<p class="text-neutral-500 text-sm">2 mins ago</p>
							</span>
							<p class="text-neutral-500 text-sm">Chat message</p>
						</div>
					</section>
				</a>
			{/each}
		</div>
	</section>

	<footer class="bg-white border-t-2 border-teal-50 text-black py-4">
		<ul class="flex items-center justify-around">
			<li class="text-teal-700 text-center">
				<i class="fa-regular fa-comment-dots" />
				<p>Message</p>
			</li>
			<li class="text-neutral-500 text-center">
				<i class="fa-regular fa-address-book" />
				<p>Contacts</p>
			</li>
			<li class="text-neutral-500 text-center">
				<i class="fa-solid fa-gear" />
				<p>Settings</p>
			</li>
		</ul>
	</footer>
</main>
