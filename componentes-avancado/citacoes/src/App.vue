/* eslint-disable */
<template>
	<div id="app">
		<CitacoesEx />
		<SobreEx />
	</div>
</template>

<script>
import CitacoesEx from './components/CitacoesEx'
import SobreEx from './components/SobreEx'

export default {
	components: { CitacoesEx, SobreEx }
}
</script>

<style>
	#app {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		height: 100vh;
		font-size: 1.6rem;
	}

	button {
        outline: none;
        padding: 5px 15px 10px;
        margin: 10px 5px;
        border-radius: 3px;
        font-size: 2rem;
        font-weight: 300;
        color: #FFF;
        background-color: rgba(0, 0, 0, .5);
    }
</style>