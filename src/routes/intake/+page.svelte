<div class="mx-auto mt-10 max-w-2xl rounded-lg border border-gray-700 bg-gray-950 p-8">
	<h1 class="mb-6 text-2xl font-bold text-cyan-400">New Client Intake</h1>
	<label class="mb-1 block text-sm text-gray-300">First Name</label>
	<input
		type="text"
		placeholder="Maria"
		class="mb-4 w-full rounded border border-gray-600 bg-gray-800 p-3 text-white placeholder-gray-500"
	/>
	<label class="mb-1 block text-sm text-gray-300">Last Name</label>
	<input
		type="text"
		placeholder="Santos"
		class="mb-4 w-full rounded border border-gray-600 bg-gray-800 p-3 text-white placeholder-gray-500"
	/>
	<label class="mb-1 block text-sm text-gray-300">Email Address</label>
	<input
		type="email"
		placeholder="[email protected]"
		class="mb-4 w-full rounded border border-gray-600 bg-gray-800 p-3 text-white placeholder-gray-500"
	/>
	<label class="mb-1 block text-sm text-gray-300">Engagement Start Date</label>
	<input
		type="date"
		class="mb-4 w-full rounded border border-gray-600 bg-gray-800 p-3 text-white"
	/>
	<label class="mb-1 block text-sm text-gray-300">Estimated Annual Revenue ($)</label>
	<input
		type="number"
		step="1000"
		min="0"
		placeholder="0"
		class="mb-4 w-full rounded border border-gray-600 bg-gray-800 p-3 text-green-400"
	/>
	<label class="mb-1 block text-sm text-gray-300">Service Type</label>
	<select class="mb-4 w-full rounded border border-gray-600 bg-gray-800 p-3 text-white">
		<option value="" disabled selected>Select a service...</option>
		<option value="bookkeeping">Bookkeeping</option>
		<option value="tax_prep">Tax Preparation</option>
		<option value="advisory">Advisory Services</option>
	</select>
</div>
