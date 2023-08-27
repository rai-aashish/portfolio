

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>


<section>

	<h1 class="_6b6b" style="">Aashish Rai</h1>




</section>

<style>

section {
	width: 100%;
	height:90vh;
	display: grid;
	place-items: center;
}
h1 {
  font-size: 72px;
  font-weight: 700;
  background: -webkit-linear-gradient(#eee, #333);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-size: 200%;
  background-image:linear-gradient(83.84deg, #0088FF -6.87%, #A033FF 26.54%, #FF5C87 58.58%);
  animation-name:gradient ;
  animation-duration:1.5s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}

@keyframes gradient{
	0%{
		background-position: 0% 0%;
	}
	100%{
		background-position:100% 100%;

	}
}
</style>
