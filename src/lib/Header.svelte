<script>
</script>

<header>
	<div class="container">
		<p>Matheus Machado de Camargo</p>
		<nav>
			<ul>
				<li><a href="#top">Início</a></li>
				<li><a href="#portfolio-section">Portfólio</a></li>
				<li><a href="#contact-section">Contato</a></li>
			</ul>
		</nav>
	</div>
</header>

<style>
	header {
		font-size: 1.5rem;
		width: 100%;
		background-color: var(--cor-70);
	}
	.container {
		width: 100%;
		max-width: 1440px;
		padding: 12px 24px;
		margin: auto;
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		align-items: center;
	}
	p {
		font-weight: 600;
		max-width: 50%;
	}
	ul {
		display: flex;
		flex-direction: row;
		gap: 24px;
	}
	@media (max-width: 600px) {
		ul {
			flex-direction: column;
		}
	}
</style>
