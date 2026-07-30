+++
title = "Institute"
+++

# Design

Welcome to the Institute website built with the Academic Workshop theme.
This front page now showcases all major sections of the theme.

## Features

* Responsive speaker and organizer grids
* Schedule table
* Accepted papers table from CSV
* Highlighted upcoming seminar
* Full seminar list


{{ new_block() }}


# List of Speakers

{{ grid(
	text = [
		["Speaker A","Institution A"],
		["Speaker B","Institution B"],
		["Speaker C","Institution C"],
		["Speaker D","Institution D"],
		["Speaker E","Institution E"],
	],
	urls = [
		"#speaker-a",
		"#speaker-b",
		"#speaker-c",
		"#speaker-d",
		"#speaker-e",
	],
	images = [
		"placeholder.svg",
		"placeholder.svg",
		"placeholder.svg",
		"placeholder.svg",
		"placeholder.svg",
	],
	narrow = true) }}


{{ new_block() }}


# List of Organizers

{{ grid(
	text = [
		"Organizer A",
		"Organizer B",
	],
	image_dir = "organizers") }}


{{ new_block() }}


# Schedule

| Time             | Event            |
| ---------------- | ---------------- |
| 12:00pm - 1:00pm | Introduction and Opening Remarks |
| 1:00pm - 2:00pm  | Speaker A        |
| 2:00pm - 3:00pm  | Speaker B        |
| 3:00pm - 4:00pm  | Discussion Panel |


{{ new_block() }}


# Accepted Papers

{{ table(
	data = "papers.csv",
	columns = ["Title","Authors"],
	button_names = ["paper","poster"],
	button_data_columns = [3,4],
	button_output_columns = [1,1]) }}

{{ new_block() }}

# Upcoming Seminar

{{ highlights(section_name = "seminars") }}

{{ new_block() }}

# List of Seminars

{{ list(section_name = "seminars") }}

{{ button(name = "All Seminars", url = "seminars") }}
