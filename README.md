# Eugene WebDevs Talk on Headless WordPress with JS
Go Headless! See what happens when the wp-admin makes friends with JS frameworks

## About

What is a headless CMS, and why should you care about it? We're going to talk about Headless WordPress, what you can do with it, and what the pros and cons are. As a bonus, we'll be showing you how to set it up using several popular JS frameworks and APIs like REST and GraphQL.

## Links

* [Slides](https://docs.google.com/presentation/d/13VTWBlUkiylzs7RtQkPWuFq70myF_tNtcKJlnv6eik8/edit?usp=sharing)
* Video
* [Meetup](https://www.meetup.com/eugenewebdevs/events/264942113/)
* Presenters: [Nikole](https://github.com/websupergirl) and [Greg](https://github.com/mckelveygreg)

## Testing Tools

* WordPress Plugins to make this work:
	* [GraphQL API for WordPress](https://www.wpgraphql.com/) - turns on the GraphQL API
	* [GraphiQL for WordPress](https://github.com/wp-graphql/wp-graphiql) - install after the GraphQL plugin
	* [WP Maintenance Mode](https://wordpress.org/plugins/wp-maintenance-mode/) to shut off the front end of WordPress for those not logged in.
* **Endpoints** for testing: [GraphQL](https://headless.thedevdrop.com/graphql) and [REST](https://headless.thedevdrop.com/wp-json/) ([see complete list of endpoints](https://developer.wordpress.org/rest-api/reference/))
* **Fake Data** for your WordPress Install (You may want to add multiple users before adding additional data so you can spread it out.)
	* [WordPress Theme Test Data](https://codex.wordpress.org/Theme_Unit_Test)
	* [FakerPress WordPress plugin](https://wordpress.org/plugins/fakerpress/) for generating fake data
	* Ipsum generators for funsies: [Jeff Goldblum](https://jeffsum.com/) and [Carl Sagan](http://saganipsum.com/)
* **[GraphQL online](https://lucasconstantino.github.io/graphiql-online/)** for offsite testing

## Resources for Additional Learning

* [React](https://reactjs.org/)
	* Video: [Crash Course: Headless WordPress with WPGraphQL, ACF, and React](https://www.youtube.com/watch?v=9KGuI0UmpMw) This was the basis of Nikole's React demo (minus ACF and with some additions), which is you can find in [live](https://websupergirl.github.io/react-headless-wp/), [build](https://github.com/websupergirl/react-headless-wp/tree/gh-pages), and [source](https://github.com/websupergirl/react-headless-wp/tree/master) forms.
* [Vue.js](https://vuejs.org/)
* [Gatsby](https://www.gatsbyjs.org/)
	* **[Live Previews with WordPress and Gatsby](https://justinwhall.com/live-previews-with-wordpress-gatsby/)** A great walkthrough to get you up and running with WordPress and Gatsby
	* **WPCasts Series on WP/Gatsby** A series combining WordPress, Gatsby, and Elementor
		* Video: [Static WordPress Generation Part 1: Getting Started](https://www.youtube.com/watch?v=N5UtB36x_O8) Getting Started With GatsbyJS, Elementor, and WPGraphQL
		* Video: [Static WordPress Generation Part 2: Downloading Images](https://www.youtube.com/watch?v=5KpSXoqsuYM) How To Download External Images to Gatsby
		* Video: [Static WordPress Generation Part 3: Performance](https://www.youtube.com/watch?v=LWOCOUHB5-Q) GatsbyJS and WordPress Performance Comparison
* [GraphQL](https://graphql.org/)
* [WordPress REST API Handbook](https://developer.wordpress.org/rest-api/)
* Video: [Should You Use WordPress As A Headless CMS?](https://www.youtube.com/watch?v=rHNl5PZT0VU)
