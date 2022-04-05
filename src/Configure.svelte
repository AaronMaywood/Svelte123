<script>
import LinkItem from './LinkItem.svelte';
</script>
<div class="subheading">Configure</div>

<div class="link-list">
	<LinkItem
		href="https://storybook.js.org/docs/react/addons/addon-types"
		src="https://raw.githubusercontent.com/storybookjs/storybook/next/examples/vue-3-cli/src/stories/assets/stackalt.svg"
		alt="plugin"
		title="Presets for popular tools"
		desc="Easy setup for TypeScript, SCSS and more."
	/>
	<LinkItem />
	<LinkItem />
	<LinkItem />
</div>

<style>
.subheading {
	--mediumdark: '#999999';
	font-weight: 900;
	font-size: 13px;
	color: #999;
	letter-spacing: 6px;
	line-height: 24px;
	text-transform: uppercase;
	margin-bottom: 12px;
	margin-top: 40px;
}

.link-list {
	display: grid;
	grid-template-columns: 1fr;
	grid-template-rows: 1fr 1fr;
	row-gap: 10px;
}

@media (min-width: 620px) {
	.link-list {
		row-gap: 20px;
		column-gap: 20px;
		grid-template-columns: 1fr 1fr;
	}
}

@media all and (-ms-high-contrast:none) {
	.link-list {
		display: -ms-grid;
		-ms-grid-columns: 1fr 1fr;
		-ms-grid-rows: 1fr 1fr;
	}
}
</style>
