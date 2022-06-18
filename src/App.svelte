<script>
  import Polyrhythm from "./components/Polyrhythm.svelte";
</script>

<main style="height: 100vh">
  <div id="polyviz" class="py-5 text-center">
		<h1>Polyviz</h1>
		<h2 class="h5 text-muted fw-light">
			Polyrhythm Visualizer
		</h2>
	</div>
  <Polyrhythm />
</main>

<style>
	#polyviz h1{
		font-size: 3vw
	}
	#polyviz h2{
		font-size: 1vw
	}
	@media(max-width: 768px){
		#polyviz h1{
			font-size: 12vw
		}
		#polyviz h2{
			font-size: 4vw
		}
	}
</style>
