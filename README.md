# Info
Reworking the original *www.placeonthe.net* site moving away from WordPress to a static site.

# Changelog
## 2021-08-16
### Fixed
- Styling errors within the CTF pages
- Converted `<>` tags in `level-1.html` XML output to HTML code

### Added
- `.gitignore` file

## 2021-08-15
### Added
- CTF page for the first level of Cloud Flaws

## 2021-08-10
### Added
- Article title and written date to articles
### Changed
- File structure, moving the articles into `YYYY/MM/` directories
### Fixed
- Title headers for the new articles

## 2021-08-09
### Added
- New content including `protect-directories-in-nginx.html`, `troubleshoot-with-curl.html` and `wpscan-api-token-with-docker.html`

## 2021-08-05
### Added
- CSS `@media` rule to header/list elements to scale on mobile devices
### Changed
- Introduced CSS versioning in the HTML files

## 2021-08-04
### Added
- Header to `index.html` for menu links with placeholders
### Changed
- CSS style of `<li></li>` elements

## 2021-07-31
### Added
- `<meta>` tags to the header to define charset and window sizes across the board
### Fixed
- Updated each page to match styling

## 2021-07-30
### Added
- Custom 404 page created with neon flashing CSS

### Fixed
- Typo on the SSH page header where the stylesheet was not being read
- Incorrect CSS class usage on the WP scanning page

### Changed
- `<pre><code>` styling in CSS
- The stylesheet from `styles.css` to `style.css`
- How `a href` links are colored
- Updated CSS color from #ff4473 to #0ebfe9 for heading and links
- Layout change, shifted to using `max-width: 960px;` as opposed to `text-align: center;` to keep the content centered

### Removed
- Triangles from bullet points
