<script lang="ts">
	import Project from "../components/Project.svelte";
	import Section from "../components/Section.svelte";
</script>

<div class="content">
	<h1>Vysp3r</h1>

	<Section title="About">
		<ul style="list-style-type:none;">
			<li>🔭 I’m working at LABPLAS and Benny&Co</li>
			<li>
				🌱 I’m learning
				<a
					href="https://www.coursera.org/professional-certificates/google-ux-design"
				>
					UX Design
				</a>
			</li>
			<li>
				📫 I'm reachable by email at
				<a href="mailto:dev@vysp3r.com"> dev@vysp3r.com </a>
				or by
				<a href="https://t.me/Vysp3r"> Telegram </a>
			</li>
			<li>🤩 I'm a Fedora, GNOME, Valve and Star Citizen fanboy</li>
			<li>🆓 I'm all about FOSS</li>
			<li>🖥️ I host most of the services I use</li>
			<li>😡 I hate browser based applications</li>
		</ul>
	</Section>

	<Section title="Projects">
		<Project
			title="ProtonPlus"
			description="A simple Wine and Proton-based compatibility tools manager"
			url="https://github.com/Vysp3r/ProtonPlus"
		/>

		<Project
			title="Markets"
			description="A simple stock, currency and cryptocurrency tracker"
			url="https://github.com/Vysp3r/Markets"
		/>

		<Project
			title="The Hub"
			description="A S&Box gamemode by Three Thieves"
			url="https://asset.party/thieves"
		/>
	</Section>
</div>
