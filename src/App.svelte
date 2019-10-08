<script>
	
	import IconoVoluta from "./componentes/Voluta/IconoVoluta.svelte";
	import IconoTwitterAzul from "./componentes/Twitter/Iconos/IconoTwitterAzul.svelte";
	import Informacion from "./componentes/Informacion/Informacion.svelte";
	import Twitter from "./componentes/Twitter/Twitter.svelte";
	import Tweet from "./componentes/Twitter/Tweet.svelte";
	import FraseViva from "./componentes/FraseViva/FraseViva.svelte";

</script>

<style>
	* {
		outline: 1px solid rgb(141, 141, 143);
	}
	
	 .Contenedor-1 {
		display: flex;
		flex-flow: row wrap;
		justify-content: space-between;
		align-content: space-around;
		padding: 1rem;
	}

	.FraseViva {
		display: flex;
		flex-flow: row wrap;
		justify-content: space-between;
		align-content: space-around;
		padding: 1rem;
	}

	


</style>


<div class="Contenedor-1">
		
			<Informacion/>
			<Twitter/>
			<IconoTwitterAzul/>
			<IconoVoluta/>
			<div class="FraseViva">
				<FraseViva/>
			</div>
		
		
</div>


		



