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
		<a href="https://github.com/matheusmachado-dev/clone-tabnews" class="card">
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
<section id="contact-section">
	<h2>Contato</h2>
	<div class="container-contact">
		<ul class="contact-list">
			<li class="contact-item">
				<a href="mailto:matheusmc.dev@gmail.com">
					<img src="gmail.svg" alt="icone do gmail" width="24" height="24" />
					matheusmc.dev@gmail.com
				</a>
			</li>
			<li class="contact-item">
				<a href="https://github.com/matheusmachado-dev">
					<img src="github.svg" alt="icone do github" width="24" height="24" />
					matheusmachado-dev
				</a>
			</li>
			<li class="contact-item">
				<a href="https://www.linkedin.com/in/matheusmachadodev/">
					<img src="linkedin.svg" alt="icone do linkedin" width="24" height="24" />
					matheusmachadodev
				</a>
			</li>
		</ul>
		<form action="https://formspree.io/f/mqakokqa" method="POST">
			<p>Envie sua mensagem</p>
			<input type="hidden" name="_language" value="pt-BR" />
			<label>
				Seu nome:
				<input type="text" name="name" />
			</label>
			<label>
				Seu email:
				<input type="email" name="email" />
			</label>
			<label>
				Sua mensagem:
				<textarea name="message"></textarea>
			</label>
			<button type="submit">Enviar</button>
		</form>
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

	.container-contact {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		align-items: center;
		gap: 32px;
	}
	.contact-list {
		display: flex;
		flex-direction: column;
		gap: 12px;
	}
	.contact-item {
		list-style: none;
	}
	.contact-item a {
		display: flex;
		flex-direction: row;
		gap: 12px;
	}
	form {
		width: 100%;
		max-width: 640px;
		min-width: 220px;
		display: flex;
		flex-direction: column;
		gap: 12px;
		padding: 12px;
		background-color: var(--cor-80);
		border-radius: 12px;
	}
	form p {
		font-size: 1.2rem;
		font-weight: 500;
	}
	form label {
		display: flex;
		flex-direction: column;
	}
	form label input,
	form label textarea {
		background-color: var(--cor-70);
		padding: 12px;
		color: var(--cor-10);
		border: none;
		border-radius: 12px;
	}
	form button {
		border-radius: 12px;
		padding: 12px;
		background-color: var(--cor-10);
		color: var(--cor-90);
		font-family: 'Poppins';
		font-size: 1rem;
		max-width: 80px;
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
	@media (max-width: 750px) {
		.container-contact {
			flex-direction: column;
			gap: 24px;
			align-items: start;
		}
	}
</style>
