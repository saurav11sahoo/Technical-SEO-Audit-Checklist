# Crawlability Audit Checklist

Crawlability refers to a search engine's ability to discover and access website URLs and their resources.

This checklist helps SEO professionals identify technical issues that prevent search engines from accessing important website content.

## 1. Robots.txt Review

- [ ] Check whether the robots.txt file is accessible.
- [ ] Review disallow directives for unintended restrictions.
- [ ] Verify that important page directories are not blocked.
- [ ] Check whether CSS and JavaScript resources required for rendering are accessible.
- [ ] Confirm that the XML sitemap location is declared where appropriate.

## 2. HTTP Status Codes

- [ ] Identify internal URLs returning 404 errors.
- [ ] Identify server errors (5xx).
- [ ] Review unexpected 403 responses.
- [ ] Identify redirect chains.
- [ ] Check for redirect loops.
- [ ] Verify that important pages return the expected HTTP 200 status.

## 3. Internal Crawl Paths

- [ ] Check whether important pages are reachable through internal links.
- [ ] Identify orphan pages with no meaningful internal links.
- [ ] Review navigation links.
- [ ] Check links within category and service pages.
- [ ] Identify links pointing to redirected or broken destinations.

## 4. XML Sitemap Accessibility

- [ ] Verify that the sitemap is accessible.
- [ ] Check for HTTP errors in the sitemap.
- [ ] Ensure sitemap URLs use the preferred canonical versions.
- [ ] Remove non-indexable or redirected URLs where appropriate.
- [ ] Check whether the sitemap is submitted in Google Search Console.

## 5. JavaScript and Rendering

- [ ] Check whether important content is available after rendering.
- [ ] Review JavaScript-dependent navigation.
- [ ] Verify that important internal links are discoverable.
- [ ] Compare rendered HTML with the initial HTML where necessary.

## 6. Crawl Budget and Crawl Efficiency

- [ ] Identify unnecessary URL parameters.
- [ ] Review duplicate URL patterns.
- [ ] Investigate large numbers of low-value URLs.
- [ ] Review Googlebot crawl activity in server logs when available.
- [ ] Identify recurring server response problems.

## Recommended Tools

- Google Search Console
- Screaming Frog SEO Spider
- Google URL Inspection Tool
- Browser developer tools
- Server access logs

## How to Prioritise Findings

Prioritise issues based on:

1. Whether important pages are affected.
2. The scale of affected URLs.
3. The severity of the crawling restriction.
4. The likely impact on search visibility.
5. Implementation effort.

## Validation

After implementing fixes, re-crawl the affected URLs and verify their HTTP responses, accessibility, internal links and rendering.

This checklist is a starting point. Always validate findings against the specific website and available crawl data.
