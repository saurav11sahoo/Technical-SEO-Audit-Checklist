
# Website Performance Audit Checklist

Website performance affects how quickly users can access content, interact with page elements, and navigate a website.

This checklist helps SEO professionals investigate performance issues, evaluate Core Web Vitals, and identify opportunities to improve website speed and user experience.

## 1. Core Web Vitals

Review the three current Core Web Vitals metrics.

### Largest Contentful Paint (LCP)

- [ ] Measure how quickly the main page content loads.
- [ ] Identify the Largest Contentful Paint element.
- [ ] Investigate slow server response times.
- [ ] Optimise large hero images and other important page assets.
- [ ] Review render-blocking resources.
- [ ] Evaluate image loading priorities.

Good threshold: 2.5 seconds or less.

### Interaction to Next Paint (INP)

- [ ] Review delays following user interactions.
- [ ] Identify long-running JavaScript tasks.
- [ ] Investigate slow event handlers.
- [ ] Review unnecessary third-party scripts.
- [ ] Check responsiveness of menus, forms, and interactive elements.

Good threshold: 200 milliseconds or less.

### Cumulative Layout Shift (CLS)

- [ ] Identify unexpected layout shifts.
- [ ] Set explicit dimensions for images and videos.
- [ ] Reserve space for advertisements and embedded content.
- [ ] Review dynamically injected page elements.
- [ ] Check font loading behaviour.
- [ ] Investigate layout shifts during page loading.

Good threshold: 0.1 or less.

## 2. Page Loading and Server Performance

- [ ] Review Time to First Byte (TTFB).
- [ ] Identify slow server responses.
- [ ] Investigate unnecessary redirects.
- [ ] Review server-side processing delays.
- [ ] Check browser caching configuration.
- [ ] Evaluate compression for text-based resources.
- [ ] Review CDN usage where appropriate.

## 3. Image Optimisation

- [ ] Identify oversized images.
- [ ] Use modern image formats where appropriate, such as WebP or AVIF.
- [ ] Compress images without unnecessary quality loss.
- [ ] Serve appropriately sized images for different devices.
- [ ] Implement lazy loading for below-the-fold images where appropriate.
- [ ] Avoid lazy loading the primary above-the-fold LCP image.
- [ ] Specify image dimensions to prevent layout shifts.

## 4. JavaScript and CSS

- [ ] Identify unnecessary JavaScript.
- [ ] Review long-running main-thread tasks.
- [ ] Reduce unused CSS where practical.
- [ ] Review render-blocking CSS.
- [ ] Defer or async-load scripts where appropriate.
- [ ] Check third-party scripts for performance impact.
- [ ] Avoid loading resources that are not required on a page.

## 5. Mobile Performance

- [ ] Test important pages on mobile devices.
- [ ] Review mobile Core Web Vitals.
- [ ] Check image sizing and responsive delivery.
- [ ] Review mobile navigation responsiveness.
- [ ] Test forms and interactive elements.
- [ ] Check for layout shifts on smaller screens.
- [ ] Evaluate performance under constrained network conditions.

## 6. Performance Monitoring

- [ ] Review the Core Web Vitals report in Google Search Console.
- [ ] Test representative URLs with PageSpeed Insights.
- [ ] Review Lighthouse diagnostics.
- [ ] Compare mobile and desktop performance.
- [ ] Separate field data from lab test results.
- [ ] Monitor performance after major site releases.
- [ ] Document recurring performance issues.

## Recommended Performance Tools

- Google PageSpeed Insights
- Google Search Console
- Chrome Lighthouse
- Chrome DevTools
- Chrome UX Report (CrUX)
- WebPageTest

## Understanding Field Data and Lab Data

Field data represents performance experienced by real users across different devices and network conditions.

Lab data is collected through controlled tests and is useful for diagnosing performance problems.

Use field data to understand real-world user experience and lab testing to investigate potential causes of performance issues.

## Audit Prioritisation

Prioritise performance improvements based on:

1. The number and importance of affected pages.
2. The severity of the performance issue.
3. Real-user experience across mobile and desktop.
4. Potential impact on important user journeys.
5. Implementation complexity and available resources.

## Validation

After implementing performance improvements, rerun relevant tests and monitor field data over time.

Verify that improvements are consistent across important page templates and devices rather than relying on a single Lighthouse score.

## Official Documentation

- Core Web Vitals: https://web.dev/articles/vitals
- Google Search Central: https://developers.google.com/search/docs/appearance/core-web-vitals
- PageSpeed Insights: https://pagespeed.web.dev/

This checklist is a starting point for a website-specific performance audit.
