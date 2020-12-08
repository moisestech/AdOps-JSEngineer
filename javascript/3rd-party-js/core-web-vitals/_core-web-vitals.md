# Core Web Vitals

### Tools

- [Web.dev/measure](https://web.dev/measure)
- [PageSpeedInsights](https://developers.google.com/speed/pagespeed/insights/)

### Blog

- [How to Improve Core Web Vitals](https://simonhearne.com/2020/core-web-vitals/)
- **LCP** (Largest Contentful Paint)
  - a measure of rendering performance, a good replacement for page load time or DOM content ready.
- **FID** (First Input Delay)
  - a measure of how long it takes the browser to respond to discrete user input like clicks or taps.
- **CLS** (Cumulative Layout Shift)
  - a measure of how unstable the page was, a sum of all unexpected layout shifts in the page lifecycle.
    - Web Fonts: match your web font character and line spacing to the fallback font
    - Ads: (pre-allocate layout slots for ads, use a fallback image if ads fail or are blocked.)
    - Late-loading CSS: ensure layout-critical CSS is in the critical path
    - Images: always add a width and height attribute for images, so the browser can allocate space before the image downloads.
    - Dynamic Content: where possible, pre-allocate layout space for dynamic elements.
- **FCP** (First COntentful Paint)
- **TTI** (Time to Interactive)
- **TBT** (Total Blocking Time)
