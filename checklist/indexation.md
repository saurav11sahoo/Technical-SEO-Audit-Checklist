# Indexation Audit Checklist

Indexation is the process through which search engines include eligible web pages in their search indexes.

This checklist helps SEO professionals investigate indexation issues, identify technical barriers, and improve the consistency of indexable website content.

## 1. Google Search Console Review

- [ ] Review the Page Indexing report.
- [ ] Identify important pages that are not indexed.
- [ ] Investigate Crawled - currently not indexed URLs.
- [ ] Investigate Discovered - currently not indexed URLs.
- [ ] Review pages excluded because of noindex directives.
- [ ] Inspect representative URLs using URL Inspection.
- [ ] Compare indexed and submitted sitemap URLs.

## 2. Robots and Indexing Directives

- [ ] Check whether important URLs are blocked by robots.txt.
- [ ] Review meta robots directives.
- [ ] Check X-Robots-Tag HTTP response headers.
- [ ] Verify that important pages do not have unintended noindex directives.
- [ ] Ensure search engines can crawl pages when they need to see their noindex directives.
- [ ] Review differences between staging and production indexing settings.

## 3. Canonicalisation

- [ ] Check the declared canonical URL on important pages.
- [ ] Compare declared canonicals with Google's selected canonical where available.
- [ ] Identify conflicting canonical signals.
- [ ] Check canonical tags on duplicate or similar pages.
- [ ] Ensure canonical URLs are accessible and return successful responses.
- [ ] Check consistency between canonical tags, internal links and XML sitemaps.

## 4. XML Sitemap Review

- [ ] Verify that XML sitemaps are accessible.
- [ ] Include preferred canonical URLs.
- [ ] Exclude URLs that redirect or return errors.
- [ ] Exclude URLs carrying unintended noindex directives.
- [ ] Check sitemap lastmod values for accuracy.
- [ ] Submit relevant sitemaps in Google Search Console.
- [ ] Review discovered and indexed URL patterns.

## 5. Duplicate and Low-Value URLs

- [ ] Identify duplicate URLs caused by parameters.
- [ ] Review filter and sorting URL variations.
- [ ] Check trailing slash and protocol variations.
- [ ] Investigate duplicate content across subdomains.
- [ ] Review pagination and faceted navigation.
- [ ] Determine which URLs should be indexed, canonicalised, or excluded.

## 6. Internal Linking and Indexability

- [ ] Ensure important indexable pages receive relevant internal links.
- [ ] Identify orphan pages.
- [ ] Check whether important pages are accessible through navigation.
- [ ] Review internal links pointing to non-canonical URLs.
- [ ] Verify that important landing pages are not isolated from the site structure.

## 7. Validation and Monitoring

- [ ] Confirm technical changes have been implemented.
- [ ] Recheck affected URLs with URL Inspection.
- [ ] Monitor indexation changes in Search Console.
- [ ] Review sitemap processing and discovered URL trends.
- [ ] Document unresolved issues and follow-up actions.

## Important Note

Submitting a URL or sitemap does not guarantee indexing. Search engines decide which eligible pages to index based on their systems and assessment of the content.

Always investigate indexation issues using multiple signals rather than relying on a single Search Console status.

## Recommended Tools

- Google Search Console
- Google URL Inspection Tool
- Screaming Frog SEO Spider
- XML Sitemap Validator

This checklist is a starting point for a website-specific indexation audit.
