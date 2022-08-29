<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="content">
	<h1>CSS 5 Examples link</h1>

	<h3>CSS Syntax</h3>
	<div class="jigs-bar-block">
		<a sveltekit:prefetch class="jigs-button jigs-bar-item jigs-grey" 
			target="_blank"
			href="/trycss_syntax1"
		>
			CSS syntax
		</a>
	</div> 
	<hr/>

	<h3>CSS Selectors</h3>
	<div class="jigs-bar-block">
		<a class="jigs-button jigs-bar-item ws-grey" 
			sveltekit:prefetch 
			target="_blank" 
			href="/trycss_syntax_element">
			The element selector
		</a>
		<a 
			sveltekit:prefetch
			class="jigs-button jigs-bar-item ws-grey jigs-border-top" 
			target="_blank"
			href="/trycss_syntax_id">
			The id selector
		</a>
		<a sveltekit:prefetch 
			class="jigs-button jigs-bar-item ws-grey jigs-border-top" 
			target="_blank" 
			href="/trycss_syntax_class">
			The class selector (for all elements)
		</a>
		
		<a 
			sveltekit:prefetch
			class="jigs-button jigs-bar-item ws-grey jigs-border-top" 
			target="_blank" 
			href="/trycss_syntax_element_class">
			The class selector (for only &lt;p&gt; elements)
		</a>
		
		<a 
			sveltekit:prefetch
			class="jigs-button jigs-bar-item ws-grey jigs-border-top" 
			target="_blank" 
			href="/trycss_syntax_element_class2">
			An HTML element that refer to two classes
		</a>
		
		<a 
			sveltekit:prefetch
			class="jigs-button jigs-bar-item ws-grey jigs-border-top"
			target="_blank" 
			href="trycss_syntax_universal">
			The universal selector
		</a>
		
		<a sveltekit:prefetch class="jigs-button jigs-bar-item ws-grey jigs-border-top" target="_blank" href="/trycss_grouping">Grouping selectors</a> 
	</div>

</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}

	.jigs-bar-block .jigs-bar-item {
		width: 100%;
		display: block;
		padding: 8px 16px;
		text-align: left;
		border: none;
		white-space: normal;
		float: none;
		outline: 0;
	}

	.jigs-grey {
		background-color: #E7E9EB!important;
		color: black!important;
	}
	.jigs-button {
		-webkit-touch-callout: none;
		-webkit-user-select: none;
		-khtml-user-select: none;
		-moz-user-select: none;
		-ms-user-select: none;
		user-select: none;
	}
	.jigs-button {
		border: none;
		display: inline-block;
		padding: 8px 16px;
		vertical-align: middle;
		overflow: hidden;
		text-decoration: none;
		color: inherit;
		background-color: inherit;
		text-align: center;
		cursor: pointer;
		white-space: nowrap;
	}

	hr {
    	margin: 20px -16px;
		/* border: 0; */
    	border-top: 1px solid #eee;
		/* box-sizing: content-box;
		/* height: 0; */
		/* overflow: visible;  */
	}
</style>
