<script lang="ts">
	import Project from "../components/Project.svelte";
	import Section from "../components/Section.svelte";
</script>

<div class="content">
	<h1>Vysp3r</h1>

	<Section title="About">
		<ul style="list-style-type: none; padding-left: 0px;">
			<li>
				🔭 I’m working at <a href="https://nexone.ca/">NexOne</a>
				and <a href="https://www.benny-co.com/">Benny&Co</a>
			</li>
			<li>
				📫 I'm reachable by email at
				<a href="mailto:dev@vysp3r.com">dev@vysp3r.com</a>
				or by
				<a href="https://www.linkedin.com/in/charles-malouin/">
					LinkedIn
				</a>
				or
				<a href="https://t.me/Vysp3r">Telegram</a>
			</li>
			<li>🌱 I’m learning sockets in C</li>
			<li>
				🤩 I'm a <a href="https://fedoraproject.org/">Fedora</a>,
				<a href="https://www.gnome.org/">GNOME</a>,
				<a href="https://www.valvesoftware.com/">Valve</a>,
				<a href="https://sbox.facepunch.com/">S&Box</a>
				and
				<a href="https://robertsspaceindustries.com/">Star Citizen</a> fanboy
			</li>
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
			title="RetroPlus"
			description="A simple ROM downloader"
			url="https://github.com/Vysp3r/RetroPlus"
		/>
	</Section>
</div>
