<template>
	<div>
		<section class="hero is-medium is-primary is-bold">
			<div class="hero-body">
				<div class="container">
					<h1 class="title is-2">
						Meet Jah-Wilson Teeba
					</h1>
				</div>
			</div>
		</section>
		<section class="section">
			<h2 class="title is-3 has-text-weight-medium has-text-centered">
				What I Bring
			</h2>
			<div class="container">
				<div class="columns">
					<div class="column">
						<div class="box">					
							<h3 class="title is-4 has-text-weight-medium">
								Front End Focus
							</h3>
							<p>
								Focused on building user interfaces with JS (Vue), HTML, and CSS (Sass) that are well designed and functional.
							</p>
						</div>
					</div>
					<div class="column">
						<div class="box">
							<h3 class="title is-4 has-text-weight-medium">
								Full Stack Experience
							</h3>
							<p>
								Experience working across the application stack using APIs, Node, Mongo, Mysql, Programming Language(Java, Python, Bash) to deliver production applications from design to deployment.
							</p>
						</div>
					</div>
					<!-- <div class="column">
						<div class="box">
							<h3 class="title is-4 has-text-weight-medium">
								Broad Business Exposure
							</h3>
							<p>
								6 years of startup experience as a co-founder of Knotty Tie Co. Managed and contributed to development, UX, marketing, service, and operations.
							</p>
						</div>
					</div>			 -->
				</div>
			</div>
		</section>
		<section class="section has-background-light">
			<h2 class="title is-3 has-text-weight-medium has-text-centered">
				Educational Background
			</h2>
			<div class="container">
				<div class="columns is-centered">
					<div class="column is-four-fifths">
						<p>
							In 2017, I graduated from Widener University With a bachelor of science in Computer information systems with focuses in computer programming.
						</p>
					</div>
				</div>
			</div>
		</section>
		<section class="section">
			<h2 class="title is-3 has-text-weight-medium has-text-centered">
				Technologies I've Worked With
			</h2>
			<div class="container">
				<div class="columns is-centered">
					<div class="column is-one-fifth">
						<div class="box">
							<figure class="image is-square">
								<img src="../assets/vue-logo.png" alt="Placeholder image">
							</figure>
							<h3 class="tech-box-title title is-4 has-text-weight-medium has-text-centered">
								Vue.js
							</h3>
							<p>
								Full production applications written in Vue
							</p>
						</div>
					</div>
					<div class="column is-one-fifth">
						<div class="box">
							<figure class="image is-square">
								<img src="../assets/k8s-icon.png" alt="Placeholder image">
							</figure>
							<h3 class="tech-box-title title is-4 has-text-weight-medium has-text-centered">
								Kubernetes
							</h3>
							<p>
								Build, Monitor, and Troubleshoot scalable applications and tools in Kubernetes
							</p>
						</div>
					</div>
					<div class="column is-one-fifth">
						<div class="box">
							<figure class="image is-square">
								<img src="../assets/node-logo.png" alt="Placeholder image">
							</figure>
							<h3 class="tech-box-title title is-4 has-text-weight-medium has-text-centered">
								Node.js
							</h3>
							<p>
								Back-ends written using Node and Express
							</p>
						</div>
					</div>
					<div class="column is-one-fifth">
						<div class="box">
							<figure class="image is-square">
								<img src="../assets/docker-icon.png" alt="Placeholder image">
							</figure>
							<h3 class="tech-box-title title is-4 has-text-weight-medium has-text-centered">
								Docker
							</h3>
							<p>
								Run containerized applications from pre-existing images stored in a centralized registry, Deploy images across the cluster • Install, maintain, and operate the Docker platform • Migrate traditional applications to containers
							</p>
						</div>
					</div>
				</div>
				<p class="tech-box-title title is-4 has-text-weight-light has-text-centered">Web API's • Mongodb • Linux • Java • Python • Bash • Agile Development</p>
			</div>
		</section>
		<section class="section has-background-light">
			<h2 class="title is-3 has-text-weight-medium has-text-centered">
				What Drives Me
			</h2>
			<div class="container">
				<div class="columns is-centered">
					<div class="column is-half content">
						<ul>
							<li><Strong>An innate desire to learn:</Strong> As a Software engineer, my drive to learn is what has made me successful.</li>
							<!-- <li><Strong>Compassion for users:</Strong> I strive to make products that give put users first.</li>
							<li><Strong>A passion for justice:</Strong> I want to put my skills to work to make the world a better place for everyone.</li> -->
						</ul>
					</div>
				</div>
			</div>
		</section>
	</div>
</template>

<style type="text/css">
.box {
	height: 100%;
}
.tech-box-title {
	margin-top: 1.5rem;
}
</style>

<script>

	export default {
		name: "about"
	};
</script>