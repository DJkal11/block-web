<script> 
 import DiscoverCard from "$lib/components/DiscoverCard.svelte";
 let select = "all";
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="content bg-white">
	<div class="m-auto text-center pt-20">
		<h1 class="text-5xl pb-10">Marketplace</h1>
		<button on:click={() => select = "all"} class="{select === "all" ? 'relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium rounded-lg  bg-blue-500 text-white  hover:text-white border-2 border-blue-400' : 'border-2 border-blue-400 relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br'}">
			<span class="relative text-xl px-5 py-2.5 transition-all ease-in duration-75 bg-transparent dark:bg-gray-900 rounded-md ">
				All Categories
			</span>
		  </button>
		  <button on:click={() => select = "Art"} class="{select === "Art" ? 'relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium rounded-lg  bg-blue-500 text-white  hover:text-white border-2 border-blue-400' : 'border-2 border-blue-400 relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br'}">
			<span class="relative text-xl px-5 py-2.5 transition-all ease-in duration-75 bg-transparent dark:bg-gray-900 rounded-md group-hover:bg-opacity-0">
				Art
			</span>
		  </button>
		  <button on:click={() => select = "video"} class="{select === "video" ? 'relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium rounded-lg  bg-blue-500 text-white  hover:text-white border-2 border-blue-400' : 'border-2 border-blue-400 relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br'}">
			<span class="relative text-xl px-5 py-2.5 transition-all ease-in duration-75 bg-transparent dark:bg-gray-900 rounded-md group-hover:bg-opacity-0">
				Video
			</span>
		  </button>
		  <button on:click={() => select = "special"} class="{select === "special" ? 'relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium rounded-lg  bg-blue-500 text-white  hover:text-white border-2 border-blue-400' : 'border-2 border-blue-400 relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br'}">
			<span class="relative text-xl px-5 py-2.5 transition-all ease-in duration-75 bg-transparent dark:bg-gray-900 rounded-md group-hover:bg-opacity-0">
				Special Tokens
			</span>
		  </button>
		  <button on:click={() => select = "collect"} class="{select === "collect" ? 'relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium rounded-lg  bg-blue-500 text-white  hover:text-white border-2 border-blue-400' : 'border-2 border-blue-400 relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br'}">
			<span class="relative text-xl px-5 py-2.5 transition-all ease-in duration-75 bg-transparent dark:bg-gray-900 rounded-md group-hover:bg-opacity-0">
				Collectibles
			</span>
		  </button>
		  <button on:click={() => select = "photos"} class="{select === "photos" ? 'relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium rounded-lg  bg-blue-500 text-white  hover:text-white border-2 border-blue-400' : 'border-2 border-blue-400 relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br'}">
			<span class="relative text-xl px-5 py-2.5 transition-all ease-in duration-75 bg-transparent dark:bg-gray-900 rounded-md group-hover:bg-opacity-0">
				Photos
			</span>
		  </button>
		  <button on:click={() => select = "adult"} class="{select === "adult" ? 'relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium rounded-lg  bg-blue-500 text-white  hover:text-white border-2 border-blue-400' : 'border-2 border-blue-400 relative inline-flex items-center justify-center p-0.5 mb-2 mr-2 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br'}">
			<span class="relative text-xl px-5 py-2.5 transition-all ease-in duration-75 bg-transparent dark:bg-gray-900 rounded-md group-hover:bg-opacity-0">
				Adult
			</span>
		  </button>
        </div> 

		<div class="flex flex-wrap w-screen p-20"> 
         <DiscoverCard />
		 <DiscoverCard />
		 <DiscoverCard />
		 <DiscoverCard />
		 <DiscoverCard />
		 <DiscoverCard />




		</div>
</div>

<style>
	
</style>
