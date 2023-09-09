# Minimalist Hugo Template for Academic Websites

This repository contains the source code to https://pascalmichaillat.org: an academic website created with [Hugo](https://github.com/gohugoio/hugo) and [PaperMod](https://github.com/adityatelange/hugo-PaperMod). The website is hosted on [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages).

The code is publicly available as a template repository so anyone can generate a new repository with the same directory structure and files, and quickly create their own academic website. The code might also be helpful to anyone who wishes to learn about Hugo or wants to recreate specific features of this website.

## Documentation

The source code is documented at https://pascalmichaillat.org/d5/.

## Features

The PaperMod theme is modified in several ways to be more adapted to academic websites:

+ Organization of the pages in three categories, which are available from any page through the menu and from the home page through buttons: 
	* Papers
	* Courses
	* Design projects
+ Automatically generated list of tags (keywords) used in papers and courses
+ New social icons specific to academia:
	* Office hours
	* Zoom
	* Substack
	* Google Scholar
+ Page metadata tailored to the academic context
+ Personalized color scheme, font, spacing, buttons, and general appearance
+ New archetypes for paper pages, course pages, an archive page, and a search page

## Usage

Do not forget to update the Google Analytics ID in `config.yml`. Either replace the ID `G-97G4MZ4061` with your own ID in the line `googleAnalyticsID: "G-97G4MZ4061"`. Or simnply comment the line `googleAnalyticsID: "G-97G4MZ4061"` if you do not wish to use Google Analytics.

## Speed

Despite the modifications to the PaperMod theme, the website continues to perform well on mobile and desktop devices. Here is an overview of the mobile performance from [PageSpeed Insights](https://pagespeed.web.dev/):

<img width="448" alt="mobile" src="https://github.com/pmichaillat/pmichaillat.github.io/assets/85443660/b54395b0-f9cb-4ad7-8daa-5f86e5f2cddc">

And here is an overview of the desktop performace:

<img width="453" alt="desktop" src="https://github.com/pmichaillat/pmichaillat.github.io/assets/85443660/eff134d2-6097-4bc2-bfd7-4f5c18571789">

Here are the [full report on mobile performance](https://pagespeed.web.dev/analysis/https-pascalmichaillat-org/hl96ythdue?form_factor=mobile) and the [full report on desktop performance](https://pagespeed.web.dev/analysis/https-pascalmichaillat-org/hl96ythdue?form_factor=desktop).

## License

+ The code used to generate this website is licensed under the terms of the MIT License.
+ Except where otherwise noted, the content of this website was created by Pascal Michaillat and is licensed under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
