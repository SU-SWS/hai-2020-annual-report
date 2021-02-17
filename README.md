# Asset Proxy for Storyblok CDN

This repo contains redirect rules to mask the asset CDN from storyblok.

To use:

* For assets from `https://a.storyblok.com` use `https://assets.stanford.edu/a`
* For assets from `https://img2.storyblok.com` use `https://assets.stanford.edu/i`

## Examples: 

**Image URL**  
Raw URL: `https://img2.storyblok.com/f/78141/360x360/1f41a7549e/do-not-delete-me-i-am-used-for-testing.png`  
asked URL: `https://assets.stanford.edu/i/f/78141/360x360/1f41a7549e/do-not-delete-me-i-am-used-for-testing.png`  

**Asset URL (Files such as PDFs and word docs)**  
Raw URL: `https://a.storyblok.com/f/78141/360x360/1f41a7549e/do-not-delete-me-i-am-used-for-testing.png`  
Masked URL: `https://assets.stanford.edu/a/f/78141/360x360/1f41a7549e/do-not-delete-me-i-am-used-for-testing.png`  

## Resources
* https://www.storyblok.com/docs/content-and-asset-cdn
* https://www.storyblok.com/docs/custom-assets-domain
