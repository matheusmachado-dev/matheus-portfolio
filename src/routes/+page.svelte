<script>
</script>

<section id="hero-section">
	<div class="containerImg">
		<img src="/matheusMachado.webp" alt="Foto de Matheus Machado de Camargo" class="imgHero" />
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
<section id="skills-section">
	<h2>Meus Conhecimentos</h2>
	<h3>Web</h3>
	<div class="container-skills">
		<div class="container-skills-list">
			<p>Front-End</p>
			<ul>
				<li>HTML5, CS3</li>
				<li>JavaScript ES6</li>
				<li>Svelte/SvelteKit</li>
				<li>React</li>
				<li>Next.js</li>
			</ul>
		</div>
		<div class="container-skills-list">
			<p>Back-End</p>
			<ul>
				<li>Node.js</li>
				<li>MySQL</li>
				<li>PostregeSQL</li>
				<li>Rest API</li>
				<li>Next.js</li>
			</ul>
		</div>
		<div class="container-skills-list">
			<p>Testes Automatizados</p>
			<ul>
				<li>Jest</li>
				<li>Cypress</li>
			</ul>
		</div>
	</div>
	<h3>Outros</h3>
	<div class="container-skills">
		<div class="container-skills-list">
			<p>Infraestrutura</p>
			<ul>
				<li>Docker</li>
			</ul>
		</div>
		<div class="container-skills-list">
			<p>Versionamento</p>
			<ul>
				<li>Git</li>
				<li>GitHub</li>
			</ul>
		</div>
	</div>
</section>
<section id="portfolio-section">
	<h2>Portfólio</h2>
	<div class="portfolio-container">
		<a href="https://matheusmachado.blog.br" class="card">
			<div class="card-image">
				<img
					src="/clonetabnews.webp"
					alt="Screenshot da pagina do site matheusmachado.blog"
					loading="lazy"
				/>
			</div>
			<h3>Clone TabNews</h3>
			<ul>
				<li>next.js</li>
				<li>front-end</li>
				<li>back-end</li>
				<li>curso.dev</li>
			</ul>
			<p class="card-description">
				projeto feito durante o curso.dev onde desenvolvi um clone do tabnews.com.br. Uma aplicação
				robusta e real.
			</p>
		</a>
	</div>
</section>

<style>
	section {
		width: 100%;
		max-width: 1440px;
		margin: auto;
		padding: 24px;
	}
	#hero-section {
		display: flex;
		flex-direction: row;
		gap: 64px;
		justify-content: space-between;
		align-items: center;
	}

	.containerImg {
		width: 40vw;
		min-width: 250px;
		aspect-ratio: 1 /1;
		border-radius: 50%;
		border: 1px solid var(--cor-10);
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

	h2 {
		font-size: 2rem;
		font-weight: 500;
		color: var(--cor-50);
	}
	h3 {
		font-size: 1.5rem;
		font-weight: 400;
	}
	.container-skills {
		display: flex;
		flex-direction: row;
		gap: 32px;
		margin-bottom: 1rem;
	}
	.container-skills-list {
		border: 1px solid var(--cor-10);
		border-radius: 12px;
		padding: 12px;
	}
	ul li {
		list-style: inside;
	}

	@media (max-width: 600px) {
		#hero-section {
			flex-direction: column;
		}
		.container-skills {
			flex-wrap: wrap;
			gap: 16px;
		}
	}

	.card {
		width: 100%;
		max-width: 350px;
		padding: 12px;
		border: 1px solid var(--cor-10);
		border-radius: 12px;
		display: flex;
		flex-direction: column;
	}
	.card h3 {
		font-weight: 500;
	}
	.card ul {
		display: flex;
		gap: 12px;
		margin-bottom: 12px;
		font-weight: 200;
	}
	.card ul li {
		list-style: none;
	}
	.card-image img {
		width: 320px;
	}
</style>
