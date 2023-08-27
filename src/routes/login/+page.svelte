<script>
	import '../../app.css';
</script>

<div class="flex justify-center items-center h-screen bg-[#EDFDF2]">
	<div class="w-96 p-6 shadow-lg bg-white rounded-xl">
		<h1 class="text-3xl block text-center font-semibold"><i class="bi bi-person-fill" />Login</h1>
		<hr class="mt-3" />
		<div class="mt-3">
			<label for="username" class="block text-base mb-2">Username</label>
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
		<div class="mt-3 flex justify-between items-center">
			<div>
				<input type="checkbox" />
				<label for="checkbox">Remember Me</label>
			</div>
		</div>
		<div class="mt-5">
			<button
				type="submit"
				class="border-2 border-green-700 bg-green-700 text-white py-1 w-full rounded-md hover:bg-green-800 font-semibold"
				><i class="fa-solid fa-right-to-bracket" />&nbsp;&nbsp;Login</button
			>
		</div>
		<div class="flex justify-between pt-4 pb-4">
			<div>
				<a href="/" class="hover:text-green-800 font-semibold">Forgot Password?</a>
			</div>
			<div>
				<a href="/register" class="hover:text-green-800 font-semibold">Create new account</a>
			</div>
		</div>
	</div>
</div>
