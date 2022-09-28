<script>
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="The Cosmos Hub" />
</svelte:head>

<section>
	<h1>
	 The Cosmos Hub
	</h1>

	<h2>
		26.09.2022
	</h2>

	<h2>
		authored collectively by members of the Cosmos community
	</h2>

	<div class="authors">
		<div class="column1">
			<p>Sam Hart <br>
			Interchain GmbH</p>
			<p>Ethan Buchman<br>
			Informal Systems</p>
			<p>Jehan Tremback<br>
			Informal Systems</p>
			<p>David Feiock<br>
			Galileo</p>
			<p>Udit Vira<br>
			Hypha Worker Co-op</p>
		</div>

		<div class="column2">
			<p>Zaki Manian<br>
				Iqlusion</p>
			<p>Max Einhorn<br>
			Iqlusion</p>
			<p>Youssef Amrani<br>
			Cosmos Contributor</p>
			<p>Jack Zampolin<br>
			Strangelove</p>
			<p>Sacha Saint-Leger<br>
			Hypha Worker Co-op</p>
		</div>
	</div>

</section>

<section>
	<div class="header">
		1 Introduction
	</div>
	<div class="paragraph">
			The vision of the Cosmos Network, as laid out in 2016, has been realized.<sup>1</sup>
		The creation of a secure software stack for building and connecting applicationspecific blockchains has catalyzed a thriving ecosystem of sovereign interoperable communities and an increasingly dynamic inter-blockchain communication
		economy. The interchain as originally imagined is taking form. The Cosmos Network is an association of autonomous communities connected economically and
		ideologically with the Cosmos Hub. It is a voluntary association of blockchains
		that subscribe to a philosophy of sovereign interoperability, localism, and pluralism. A network of networks that uphold the right for communities to maintain technological sovereignty and peacefully interoperate. This philosophy is
		grounded in a humility for the extraordinarily rich cultural diversity of human
		beings. It is tacit recognition of the fundamental limits of our discretionary
		reason in organizing planetary sustainability, while serving as a call to use technology as best we can to facilitate responsible self-governance. Cosmos offers a
		meta-political economy, one that recognizes the need for representation of different interests at different scales, and for an approach that can bridge the gap
		from local to global and back.

		<div class="snoska">
		<div class="line"></div>
		<sup>1</sup>Kwon, Jae; Buchman, Ethan. “Cosmos Whitepaper.” Mar. 2017,
			<a href="https://v1.cosmos.network/resources/whitepaper">https://v1.cosmos.network/resources/whitepaper.</a>
		</div>
	</div>

</section>
<section>
	<div class="paragraph">
		The Cosmos Hub’s inaugural role was to originate the internet of blockchains.
	It did so by resourcing the development of the Cosmos SDK, IBC, and Tendermint, the core open-source primitives for the blockchain applications that now
	populate the interchain. However, with an active and increasingly sophisticated
	IBC network, the needs of the interchain have evolved. Accordingly, the Cosmos Hub must also transition into a new role: to grow a resilient interchain
	economy.
	</div>
	<div class="paragraph">
	In this new role, the Cosmos Hub becomes a secure platform for others to
	build the next generation of interchain-native infrastructure and applications,
	opening new opportunities for interchain coordination. From this substrate, the
	Cosmos Hub renews its purpose as a provider of infrastructure services whose
	utility scales with the growth of the interchain. The Cosmos Hub will secure
	and capitalize ecosystem-critical applications, while serving as the port of entry
	for new Cosmos participants, and a coordinating center for the infrastructure
	and administrative concerns of the interchain.
	</div>
	<div class="paragraph">
	This paper describes the Cosmos Hub’s layered architecture, beginning with
	the collaborative effort required to build and maintain the Cosmos Stack. One
	layer above is the Hub’s Interchain Security and Liquid Staking functionality,
	which provide a platform for secure economic scaling. And on top of this scaling
	platform, a newly proposed layer of Hub-specific functionality: the Interchain
	Scheduler and the Interchain Allocator, whose joint purpose is to grow a more
	resilient interchain
	</div>
	<ul class="list">
  <li><b>Social Coordination Technology:</b>
	The Cosmos Hub is a natural place
	for Tendermint, Cosmos SDK, and IBC DAOs. A presence on the Cosmos
	Hub will open the funding and control of the open-source software to a
	wider group of stakeholders.
	</li>
	<li><b>Interchain Security:</b>
	Security is a necessary foundation to build essential components for the Cosmos Network, and the Cosmos Hub’s Interchain Security environment will be enriched with new capabilities that
	make it more useful, efficient, and cooperative.
	</li>
  <li><b>Liquid Staking:</b>
	Liquidity is critical in the proof of stake economy. The
	Cosmos community has studied liquid staking for years and will soon
	provide the secure infrastructure for premier vendors to issue liquid staking
	assets.<sup>2</sup>
	</li>
	<div class="snoska">
	<div class="line"></div>
	<sup>2</sup>Lutsch, Felix; Crain, Brian; Shapiro, Gabriel; Dillon, Brendan. “Liquid Staking Research
Report: Implications of Proof-of-Stake Assets in Decentralized Finance.” Jun. 2020,
		<a href="https://mirror.chorus.one/liquid-staking-report.pdf">https://mirror.chorus.one/liquid-staking-report.pdf.</a>
	</div>
	<li>
	<b>Interchain Scheduler:</b>
	The IBC economy is a patchwork of asynchronous
	markets, introducing an enormous variety of cross-domain maximum extractable value (MEV) opportunities. This market can be made more
	efficient, more secure, and more lucrative for Cosmos chains and their
	users. The interchain needs a secure block space market to avoid off-chain
	cartelization and more options for chains seeking to optimize the use of
	block space.
	</li>
	<li>
	<b>Interchain Allocator:</b>
	Sustaining the rapid growth of the interchain
	will require new approaches to on-chain economic coordination. The Interchain Allocator is a platform for delegated parties to grow and align
	ATOM-based markets, facilitating multi-chain trust and coordination.
	The integration of sovereign political economies through transparent collateralized agreements will unlock higher-order economic power and capital efficiency.
	</li>
  </ul>
	<div class="pic">
		<div class="pics-names">
		Hub-specific Functionality
		Secure Economic Scaling
		Cosmos Stask
		</div>
		<div class="pics-grid">
		Interchain Scheduler
		Interchain Security
		Interchain Allocator
		</div>
	</div>
</section>
<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
		margin: 10px 0px;
	}

	.header {
		display: flex;
		font-size: 36px;
		width: 100%;
	}

	.pic {
		display: grid;
		grid-template-columns: 3fr 3fr 3fr;
	}

	.pics-names {
		justify-self: start;
	}

	.pics-grid {
		display: grid;
		grid-template-rows: 3fr 3fr 3fr;
	}

	.authors {
		display: grid;
		grid-template-columns: 1fr 1fr;
		gap: 100px;
	}

	.column1 {
		justify-self: start;
	}

	.column2 {
		justify-self: end;
	}

	.line {
		margin-top: 5px;
		align-self: start;
		width: 40%;
		border: 1px solid black;
	}

	.paragraph {
		margin: 10px 0px;
	}

	sup {
		font-size: 10px;
	}

	.snoska {
		margin: 10px 0px;
		font-size: 12px;
	}
</style>
