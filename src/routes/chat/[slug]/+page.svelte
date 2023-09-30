<main class="h-full flex flex-col">
	<nav class="flex items-center justify-between p-4">
		<div class="flex items-center gap-3">
			<a href="/">
				<i class="fa-solid fa-arrow-left-long" />
			</a>
			<img src="/placeholder.jpg" alt="Chat partner" class="w-12 h-12 rounded-full" />
			<div>
				<h1 class="text-xl font-semibold">Chat name</h1>
				<p class="text-neutral-500 text-sm">2 mins ago</p>
			</div>
		</div>
		<i class="fa-solid fa-phone" />
	</nav>

	<section class="px-4 flex flex-col-reverse gap-3 overflow-y-auto pb-4 grow">
		{#each { length: 10 } as _}
			<div class="text-end leading-relaxed">
				<div class="bg-teal-600 mb-1 rounded-3xl rounded-tr-none text-white px-5 py-3 inline-block">
					What&apos;s up?
				</div>
				<p class="text-neutral-500 text-sm mx-4">2 min ago</p>
			</div>
			<div class="text-start leading-relaxed">
				<div class="bg-slate-100 mb-1 rounded-3xl rounded-tl-none px-5 py-3 inline-block">
					Carl, it&apos;s Sweet.
				</div>
				<p class="text-neutral-500 text-sm mx-4">2 min ago</p>
			</div>
		{/each}
	</section>

	<section class="bg-white p-4 border-t-2 border-teal-50 flex gap-4">
		<input
			type="text"
			class="bg-gray-100 placeholder-neutral-500 p-2 rounded-xl grow"
			placeholder="Write your message..."
		/>
		<button disabled class="text-xl text-teal-700 disabled:text-neutral-500">
			<i class="fa-solid fa-paper-plane" />
		</button>
	</section>
</main>
