+++
title = "Institure For The Study of Non-Linear Time"
+++
<div style="text-align: center; margin: 0 0; line-height: 5;">The Institute aims to clarify aspects of every day experience in a nonliner manner.</div>


# Affilites of the Instiute

{{ grid(
	text = [
		["Edwin Gold","Leuven Univeristy"],
		["Simon Carlfjord","GeoMind"],
	],
	urls = [
		"#speaker-a",
		"#speaker-b",
	],
	images = [
        "Edwin 2.jpg",
		"Byline-223x300.jpg",
		

	],
	narrow = true) }}


{{ new_block() }}


# Research

{{ table(
	data = "papers.csv",
	columns = ["Title","Authors"],
	button_names = ["paper",""] ,
	button_data_columns = [3,4],
	button_output_columns = [1,1]) }}

{{ new_block() }}
