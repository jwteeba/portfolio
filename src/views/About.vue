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
								Front End Experience
							</h3>
							<p>
								I have good experience working with Vue.js, AngularJS to create web application. Worked
								with Vaadin to create user interface in java.
							</p>
						</div>
					</div>
					<div class="column">
						<div class="box">
							<h3 class="title is-4 has-text-weight-medium">
								Full Stack Experience
							</h3>
							<p>
							Use Kubernetes to orchestrate containers across multiple hosts. I have great experience in designing,
							building, configuring, and exposing cloud native applications for Kubernetes. I have experience writing scripts
							that run task on a HPC, building APIs to interact with a database and backend service.
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
								Built and maintained applications using Vue.js
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
								Use Kubernetes to build, monitor, and troubleshoot scalable applications and tools
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
								Built REST APIs and Backend Applications using Node.js
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
				<p class="tech-box-title title is-4 has-text-weight-light has-text-centered">APIs • Machine Learning • Python • Java • Bash • High Performance Computing • Agile Development • Data science</p>
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