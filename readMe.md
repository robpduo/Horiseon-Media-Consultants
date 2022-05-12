# Read Me - HTML CSS Git Challenege Code Refactor

## Changes Made to index.html
- Added semantic tag for the navigation bar at the top of the page
	- \<nav>\</nav> line 13, line 25

- Replaced \<div> to the  semantic tag \<section>\</section> that will contain the 3 articles found in the webpage for search engine optimization and accessibility

- Seperated the 3 main articles in the body with semantic tags: search-engine-optimization, online-reputation-management, social-media-marketing
	- \<article>\</article>

- Included alt attribute to article 1-3 on in the main body html tag

	- "Key factors in search engine optimization: Content, Headings, Mobile Compatibility, Social Media, Backlink, and Link Building"
	- alt attribute added after the class attribute on the image source of search-engine-optimization  article

	- "Increasing Reputation of the company increases the business's growth"
	- alt attribute added after the class attribute on the image source of online-reputation-management article

	- "Common buzzwords to be aware of: Like, Share, Tweet, and Media"
	- alt attribute added after the class attribute on the image source of social-media-marketing article

- Descriptive title denoting the company's name and the service they provide
	- "Horiseon - Online Media Consultant

- No Alt description added to icons used in class="benefits" since these icons are for decorative purposes

- Included an alt description for the main image below the navigation bar, found in the hero class
- Changed div to section for the hero class below the navigation bar

- \<nav>\</nav> semantic tags used to denote the navigation bar in place of \<div>

- \<aside>\</aside> semantic tags used to denote the side panel to the right of the main body in place of \<div>\</div>

- \<footer>\</footer> semantic tags used to denote the bottom of the screen in place of \<div>\</div>

- \<figure> and \<figcaption> semantic tag used to decribe the side panel components and icons

## Changes Made to styles.css
- Changed selector to style nav tag, line 27, 35, 39 
