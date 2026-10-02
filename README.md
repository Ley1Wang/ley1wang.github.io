# Siyu Chen portfolio

This site is published from this repository alone. Its planned custom domain is `siyu.wangleyi.top`; the `wangleyi.top` portfolio repository does not need a copy of these files.

To make the domain work after pushing this repository:

1. In this repository's GitHub **Settings → Pages**, set **Custom domain** to `siyu.wangleyi.top`.
2. At the DNS provider for `wangleyi.top`, add a **CNAME** record with name `siyu` and target `ley1wang.github.io`.
3. Once DNS and GitHub Pages finish updating, enable **Enforce HTTPS** in Pages settings.

GitHub Pages does not let a separate repository claim a URL path such as `wangleyi.top/siyu-chen/` through its Custom domain setting. A path under the existing site would require routing at a proxy or copying files into that site.
