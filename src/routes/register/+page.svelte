<script>
	import '../../app.css';
</script>

<div class="flex justify-center items-center h-screen bg-[#EDFDF2]">
	<div class="w-96 p-6 shadow-lg bg-white rounded-xl">
		<h1 class="text-3xl block text-center font-semibold"><i class="bi bi-person-fill" />New here?</h1>
		<hr class="mt-3" />
		<div class="mt-3">
			<label for="name" class="block text-base mb-2">How should we call you?</label>
			<input
				type="text"
				id="name"
				class="border w-full text-base px-2 py-1 focus:outline-none focus:ring-0 focus:border-gray-600"
				placeholder="Enter Your Name..."
			/>
		</div>
		<div class="mt-3">
			<label for="username" class="block text-base mb-2">Create your Username</label>
			<input
				type="text"
				id="username"
				class="border w-full text-base px-2 py-1 focus:outline-none focus:ring-0 focus:border-gray-600"
				placeholder="Enter Username..."
			/>
		</div>
		<div class="mt-3">
			<label for="password" class="block text-base mb-2">Password</label>
			<input
				type="password"
				id="password"
				class="border w-full text-base px-2 py-1 focus:outline-none focus:ring-0 focus:border-gray-600"
				placeholder="Enter Password..."
			/>
		</div>
		<div class="mt-3">
			<label for="confirm" class="block text-base mb-2">Confirm your Password</label>
			<input
				type="password"
				id="confirm"
				class="border w-full text-base px-2 py-1 focus:outline-none focus:ring-0 focus:border-gray-600"
				placeholder="Confirm Password..."
			/>
		</div>
		<div class="mt-5">
			<button
				type="submit"
				class="border-2 border-green-700 bg-green-700 text-white py-1 w-full rounded-md hover:bg-green-800 font-semibold"
				><i class="fa-solid fa-right-to-bracket" />&nbsp;&nbsp;Register</button
			>
		</div>
		<div class="flex justify-between pt-4 pb-4">
			<div>
				<a href="/login" class="hover:text-green-800 font-semibold">Already registered?</a>
			</div>
		</div>
	</div>
</div>
