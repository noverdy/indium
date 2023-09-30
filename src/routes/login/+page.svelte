<main class="h-full px-8 pt-16 flex flex-col">
	<h1 class="font-semibold text-2xl text-center mb-8">
		<span class="border-b-8 border-teal-700">Log in</span> to Indium
	</h1>
	<h2 class="text-neutral-500 font-medium text-center leading-relaxed mb-16">
		Welcome back! Sign in using your social account or email to continue.
	</h2>
	<form action="" class="grow flex flex-col mb-8">
		<div class="mb-8">
			<label for="email" class="text-teal-700 font-semibold mb-2 block"> Your email </label>
			<input
				type="email"
				name="email"
				id="email"
				class="block w-full border-b border-neutral-500 py-2 text-xl outline-none focus:border-teal-400"
				required
			/>
		</div>
		<div class="mb-8 grow">
			<label for="password" class="text-teal-700 font-semibold mb-2 block"> Password </label>
			<input
				type="password"
				name="password"
				id="password"
				class="block w-full border-b border-neutral-500 py-2 text-xl outline-none focus:border-teal-400"
				required
			/>
		</div>
		<div class="text-center">
			<button
				type="submit"
				class="bg-teal-700 text-white p-4 block w-full rounded-2xl font-semibold text-center mb-4"
			>
				Log in
			</button>
			<a href="." class="font-semibold text-teal-700">Forgot password?</a>
		</div>
	</form>
</main>
