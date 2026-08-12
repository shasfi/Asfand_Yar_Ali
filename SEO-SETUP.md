# SEO setup for asfandyarali.vercel.app

This project is a single-page portfolio, so `/` is currently the only genuine indexable page URL. Section anchors such as `#projects` are not separate URLs and should not be added to the XML sitemap.

## Included in the project
- `sitemap.xml` with the canonical home URL and `lastmod`
- `robots.txt` pointing to the sitemap
- Canonical URL and crawl/index directives
- Unique title and meta description
- Open Graph and Twitter image metadata
- JSON-LD for WebSite, WebPage and Person
- Favicon SVG, PNG and ICO variants plus web manifest
- Skip-link and semantic main content landmark
- No-JavaScript summary for basic accessibility/resilience
- Animated laptop website preview in the hero area

## Google Search Console
1. Deploy the site to the canonical HTTPS domain.
2. In Search Console, add the exact property for `https://asfandyarali.vercel.app/`.
3. Submit `https://asfandyarali.vercel.app/sitemap.xml`.
4. Use URL Inspection for `/` and request indexing after deployment and after major content changes.
5. Test the live URL and watch Page indexing, Core Web Vitals and HTTPS reports.

## Important ranking note
No code can guarantee a #1 Google ranking for every keyword. Rankings depend on query intent, competition, content quality, links, reputation, technical health and Google's systems. This package focuses on strong technical foundations and crawlability without inventing duplicate pages.
