<script>
</script>

<section id="heroSection">
	<div class="containerImg">
		<img src="/matheusMachado.jpg" alt="Foto de Matheus Machado de Camargo" class="imgHero" />
	</div>
	<div>
		<h1>Matheus Machado de Camargo</h1>
		<p class="subtitle">Desenvolvedor Web Full-Stack</p>
		<p class="subtitle last">São Paulo, Brasil</p>
		<p>
			Hoje em dia estou focado em desenvolver projetos menores para alimentar meu portfólio pessoal
			e desenvolver minha experiência prática.
		</p>
	</div>
</section>

<style>
	#heroSection {
		width: 100%;
		max-width: 1440px;
		margin: auto;
		display: flex;
		padding: 24px;
		display: flex;
		flex-direction: row;
		gap: 64px;
		justify-content: space-between;
		align-items: center;
	}
	@media (max-width: 600px) {
		#heroSection {
			flex-direction: column;
		}
	}
	.containerImg {
		width: 40vw;
		min-width: 250px;
		aspect-ratio: 1 /1;
		border-radius: 50%;
		overflow: hidden;
	}
	.imgHero {
		width: 100%;
		height: 100%;
		object-fit: cover;
	}
	h1 {
		font-weight: 600;
		font-size: 2rem;
	}
	.subtitle {
		font-weight: 200;
		font-size: 1.5rem;
		color: var(--cor-50);
	}
	.subtitle.last {
		margin-bottom: 32px;
	}
</style>
