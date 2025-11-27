<svelte:head>
	<link
		href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=EB+Garamond:wght@400;500&display=swap"
		rel="stylesheet"
	/>
</svelte:head>
<div class="container">
	<!-- Header -->
	<header>
		<h1>Adam Ducken</h1>
		<p class="contact">adamducken@gmail.com</p>
		<!-- <p class="contact">+371 20224765</p> -->
		<p class="contact">Riga, Latvia</p>
	</header>
	<!-- Summary -->
	<section>
		<h2>Profile</h2>
		<p class="profile-text">
			Full-stack Web3 developer with 3+ years of experience using Rust and TypeScript. Experienced
			with Anchor, Axum, SvelteKit.
		</p>
	</section>
	<!-- Experience -->
	<!-- <section> -->
	<!-- 	<h2>Experience</h2> -->
	<!---->
	<!-- 	<div class="job"> -->
	<!-- 		<div class="job-header"> -->
	<!-- 			<h3>Job Title</h3> -->
	<!-- 			<span class="date">2022 – Present</span> -->
	<!-- 		</div> -->
	<!-- 		<p class="company">Company Name, Location</p> -->
	<!-- 		<p class="description"> -->
	<!-- 			Brief description of responsibilities and achievements in this role. -->
	<!-- 		</p> -->
	<!-- 	</div> -->
	<!-- </section> -->
	<!---->
	<!-- Portfolio Projects -->
	<section>
		<h2>Portfolio Projects</h2>
		<div class="project">
			<div class="project-header">
				<h3>EU ETS Web3 Platform</h3>
				<span class="date">2023 – 2026</span>
			</div>
			<p class="description">
				Developed a Web3 platform prototype to modernize EU ETS using Anchor, Axum, and SvelteKit.
				Designed a dual-token GHG/EUA model, implemented an on-chain registry, hybrid sealed-bid
				auctions using zk-SNARKs with off-chain prover and on-chain verifier, and a hybrid DEX with
				off-chain matching engine and on-chain trade execution, settlement.
			</p>
		</div>
	</section>
	<!-- Education -->
	<section>
		<h2>Education</h2>
		<div class="education">
			<div class="job-header">
				<h3>Programming Technician</h3>
				<span class="date">2022 – 2026</span>
			</div>
			<p class="company">Jelgava Vocational School</p>
		</div>
	</section>
	<!-- Skills -->
	<section class="skills">
		<h2>Skills</h2>
		<p>Skill 1 • Skill 2 • Skill 3 • Skill 4 • Skill 5 • Skill 6</p>
	</section>
</div>

<style>
	:global(*) {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}
	.container {
		font-family: 'EB Garamond', serif;
		background-color: white;
		color: black;
		min-height: 100vh;
		padding: 60px 40px;
		max-width: 850px;
		margin: 0 auto;
		line-height: 1.6;
		font-size: 18px;
	}
	header {
		margin-bottom: 40px;
		border-bottom: 1px solid black;
		padding-bottom: 20px;
	}
	h1 {
		font-family: 'DM Serif Display', serif;
		font-size: 52px;
		font-weight: normal;
		margin-bottom: 10px;
		letter-spacing: 0.5px;
	}
	.contact {
		font-size: 20px;
		color: #333;
	}
	section {
		margin-bottom: 40px;
	}
	section.skills {
		margin-bottom: 0;
	}
	h2 {
		font-family: 'DM Serif Display', serif;
		font-size: 28px;
		margin-bottom: 16px;
		font-weight: normal;
	}
	.profile-text {
		font-size: 19px;
		text-align: justify;
	}
	.job {
		margin-bottom: 20px;
	}
	.job-header {
		display: flex;
		justify-content: space-between;
		margin-bottom: 6px;
	}
	.project {
		margin-bottom: 20px;
	}
	.project-header {
		display: flex;
		justify-content: space-between;
		margin-bottom: 6px;
	}
	h3 {
		font-size: 21px;
		font-weight: 500;
	}
	.date {
		font-size: 18px;
		color: #555;
	}
	.company {
		font-size: 19px;
		font-style: italic;
		margin-bottom: 8px;
	}
	.description {
		font-size: 19px;
	}
	.education {
		margin-bottom: 15px;
	}
	section p {
		font-size: 19px;
	}
</style>
