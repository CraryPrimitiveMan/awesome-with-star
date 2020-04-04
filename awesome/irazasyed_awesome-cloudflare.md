# Information comes from [irazasyed/awesome-cloudflare](https://github.com/irazasyed/awesome-cloudflare)
# Awesome Cloudflare [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) [<img src="media/cf-logo.svg" width="250" align="right" alt="Cloudflare">](https://www.cloudflare.com)

> Curated list of awesome [Cloudflare](https://www.cloudflare.com) worker recipes, open-source projects, guides, blogs and other resources.

Cloudflare provides content delivery network (CDN) services, DDoS mitigation, Internet security and distributed domain name server (DNS) services, sitting between the visitor and the Cloudflare user's hosting provider, acting as a reverse proxy for websites.

## Contents

- [Community](#community)
- [Blog](#blog)
- [DNS](#dns)
- [Developers](#developers)
- [Apps](#apps)
  - [Open Source](#open-source)
- [Workers](#workers)
  - [Reference](#reference)
  - [Tools](#tools)
  - [Recipes](#recipes)
- [Other](#other)

## Community

- [Forum](https://community.cloudflare.com)
- [Reddit](https://www.reddit.com/r/CloudFlare)
- [`@Cloudflare` on Twitter](https://twitter.com/cloudflare)
- [Facebook](https://www.facebook.com/Cloudflare)
- [YouTube](https://www.youtube.com/cloudflare-)
- [GitHub](https://github.com/cloudflare)
- [GitHub Topic](https://github.com/topics/cloudflare)
- [Stack Exchange](https://stackexchange.com/search?q=cloudflare)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/cloudflare)
- [Server Fault](https://serverfault.com/questions/tagged/cloudflare)

## Blog

- [Official Blog](https://blog.cloudflare.com)

## DNS

- [DNS Zone Files](https://github.com/irazasyed/dns-zone-files) - Ready to import common config zone files for easy configuration of various services. :star:18
- [Lexicon](https://github.com/AnalogJ/lexicon) - CLI tool to manipulate DNS records on various DNS providers in a standardized way. :star:854
- [Th3inspector](https://github.com/Moham3dRiahi/Th3inspector) - All in one CLI tool for information gathering. :star:808
- [Partner Panel](https://github.com/ZE3kr/Cloudflare-CNAME-Setup) - Tool for hosting partners to provide a DNS management panel for customers. :star:880
- [CFPMP](https://github.com/Netrvin/CFPMP) - Partner management panel. :star:168
- [Flares](https://github.com/lfaoro/flares) - DNS backup tool. :star:152
- [Block Bad Bot Ruleset](https://github.com/SukkaW/cloudflare-block-bad-bot-ruleset) - Collection of rulesets to block malicious crawlers with firewall rules. :star:73
- [Docker DDNS](https://github.com/oznu/docker-cloudflare-ddns) - Docker image to use the free DNS Service as a dynamic DNS provider. :star:201
- [DDNS script for Synology](https://github.com/joshuaavalon/SynologyCloudflareDDNS) - DDNS script for Synology NAS. :star:103
- [Dynamic DNS Bash](https://github.com/yulewang/cloudflare-api-v4-ddns) - Dynamic DNS updater in bash script. :star:50
- [Dynamic DNS PHP](https://github.com/lyoshenka/cloudflare-ddns) - Dynamic DNS updater in PHP. :star:138
- [Dynamic DNS Python](https://github.com/adrienbrignon/cloudflare-ddns) - Dynamic DNS updater in python. :star:127
- [Multi-Provider DDNS Script](https://github.com/phuslu/ddns) - Multiple providers ddns script without dependencies. :star:35
- [Argo Tunnel Client](https://github.com/cloudflare/cloudflared) - CLI client for Argo tunnel, a tunneling daemon that proxies any local webserver through the Cloudflare network. :star:687
- [Upper](https://github.com/ostark/upper) - Speeds up craft dramatically using a cache proxy in front of your webserver. :star:81
- [Cloud Buster](https://github.com/SageHack/cloud-buster) - A comprehensive pentest tool that checks sites for origin IP leaks. :star:122
- [CLI Tool](https://github.com/danielpigott/cloudflare-cli) - CLI tool for interacting with Cloudflare. :star:86
- [Detector](https://github.com/k4m4/cloudflare-detect) - Detect whether a site is running behind Cloudflare. :star:11
- [Scrape](https://github.com/Anorov/cloudflare-scrape) - Python module to bypass anti-bot page. :star:1873
- [CloudFlair](https://github.com/christophetd/CloudFlair) - Tool to find origin servers of websites protected by CloudFlare who are publicly exposed. :star:985

## Developers

- [Developers Hub](https://developers.cloudflare.com) - Developer docs including API reference, articles, and sample code for all products.
- [Open Source](https://cloudflare.github.io) - Official open-source projects.
- [API Docs](https://api.cloudflare.com) - API documentation.
- [Integration Resources](https://www.cloudflare.com/integrations) - Plugins for content management systems, control panels, cloud providers, ecommerce platforms and more.
- [Technical Resources](https://www.cloudflare.com/technical-resources) - Technical tools and resources.
- [The Serverlist Newsletter](https://blog.cloudflare.com/serverlist) - The serverlist is a Cloudflare-curated newsletter about all things serverless.

## Apps

> [Cloudflare Apps](https://www.cloudflare.com/apps/developers) lets you ship your tool or service to millions of sites. Any Cloudflare customer can preview & install your code on their site in seconds.

- [Apps Directory](https://www.cloudflare.com/apps)
- [Documentation](https://www.cloudflare.com/apps/developer/docs/getting-started)
- [Developer Fund](https://www.cloudflare.com/fund)
- [App Ideas](https://github.com/cloudflare-apps/ideas) :star:33

### Open Source

- [Official OSS Apps](https://github.com/cloudflare-apps) - Collection of official apps.
- [Logflare](https://github.com/Logflare/cloudflare-app) - Log management & event analytics. :star:15

## Workers

> [Cloudflare Workers](https://www.cloudflare.com/products/cloudflare-workers) provides a serverless execution environment that allows you to create entirely new applications or augment existing ones without configuring or maintaining infrastructure.

### Reference

- [Documentation](https://workers.cloudflare.com/docs)
- [Tutorials](https://workers.cloudflare.com/docs/tutorials)
- [Runtime](https://workers.cloudflare.com/docs/reference/runtime)
- [Workers KV](https://workers.cloudflare.com/docs/reference/storage)

### Tools

- [Wrangler](https://github.com/cloudflare/wrangler) - `wrangler` is a CLI tool designed for folks who are interested in using Cloudflare workers. :star:1275
- [Playground](https://www.cloudflareworkers.com) - Simple, instant way to preview and test code directly in the browser against any site.
- [Serverless Plugin](https://workers.cloudflare.com/docs/reference/tooling/serverless) - Plugin for [serverless framework](https://github.com/serverless/serverless) to develop and deploy serverless applications using Workers.
- [Worker App Kit](https://github.com/postlight/cloudflare-worker-app-kit) - Handy set of tools for creating, developing, testing, and deploying worker app. :star:42
- [GitHub Action](https://github.com/cpilsworth/cloudflare-worker-action) - Deploy a worker on push to the master branch. :star:9
- [Workers KV Viewer](https://github.com/jroyal/cloudflare-workers-kv-viewer) - CLI based interactive viewer for workers KV storage. :star:11
- [Redirect Management](https://forwarding.app) - Generate redirect worker.

### Recipes

- [Examples Collection](https://github.com/cloudflare/worker-examples) - Collection of recipes. :star:443
- [Hello World JS Boilerplate](https://github.com/cloudflare/worker-template) - Template for kick starting a worker project in JS. :star:40
- [Hello World Rust Boilerplate](https://github.com/cloudflare/rustwasm-worker-template) - Template for kick starting a worker project using wasm-pack. :star:69
- [Router](https://github.com/cloudflare/worker-template-router) - Router that can be used with REST APIs or apps for basic routing logic. :star:47
- [Static](https://github.com/cloudflare/worker-template-static) - Generate a static HTML or JSON page from raw strings in your workers script. :star:4
- [Fetch](https://github.com/cloudflare/worker-template-fetch) - Examples of making fetch requests and generating JSON post requests. :star:9
- [Incoming Request](https://github.com/ashleygwilliams/worker-template-requests) - Examples of reading in a POST request body of type JSON and form-data.
- [Redirect](https://github.com/cloudflare/worker-template-redirect) - Examples of sending single and bulk redirects from a Worker script. :star:3
- [Img-Color](https://github.com/xtuc/img-color-worker) - Retrieve the dominant color of a png or jpeg image. :star:5
- [Binast](https://github.com/xtuc/binast-cf-worker-template) - Serve binast via a worker. :star:1
- [Pwnage Protection](https://github.com/detroitenglish/pw-pwnage-cfworker) - Secure password scoring and user pwnage protection api - [Usage](https://community.cloudflare.com/t/estimate-strength-of-users-new-password-input-with-zxcvbn-and-query-haveibeenpwned-for-matches-against-known-hacked-accounts/26378). :star:112
- [Cache Purger Proxy](https://gist.github.com/vdbelt/20f116236d2ebffa92f131e679c0551a) - Proxies purge cache requests - [Usage](https://community.cloudflare.com/t/worker-recipe-cache-purge-proxy/29978).
- [URL Router](https://github.com/berstend/service-worker-router) - Fast url router - [Usage](https://community.cloudflare.com/t/open-source-fast-url-router-for-workers-js-typescript/33406). :star:60
- [Edge Proxy](https://github.com/DigitalOptimizationGroup/cloudflare-edge-proxy) - Enable A/B testing, canary releasing, gatekeeping, and SEO A/B/N testing. :star:36
- [Blue / Green Deployments](https://github.com/DigitalOptimizationGroup/blue-green-cloudflare-workers) - Working example of blue / green deployments with canary releasing. :star:9
- [Preact PWA](https://github.com/DigitalOptimizationGroup/cloudflare-worker-preact-pwa) - Preact progressive web app. :star:54
- [CURL Interceptor](https://github.com/Gaafar/curl-worker) - Intercepts requests from `curl` command and returns something different. :star:24
- [Worker with built-in Router](https://github.com/anderly/cloudflare-worker-routing) - Allows you to separate your worker logic into different functions and/or controllers. :star:25
- [Connecting to Google Storage](https://community.cloudflare.com/t/connecting-to-google-storage/32350) - Pull files from Google's cloud storage.
- [CSRF Protection](https://gist.github.com/simonerni/3501b8de6320ac37398d08d9d2d08561) - Protect any origin from CSRF by verifying origin/referer headers.
- [URL Query Strings Parser](https://community.cloudflare.com/t/parse-url-query-strings-with-cloudflare-workers/90286) - Parse url query strings.
- [Regrex Replacement and Injection](https://community.cloudflare.com/t/perform-regex-replacements-and-inject-css-javascript-with-cloudflare-workers/90279) - Perform regex replacements and inject CSS/JS.
- [Webpack Boilerplate](https://github.com/detroitenglish/cloudflare-workers-webpack-boilerplate) - Boilerplate to build, bundle and deploy workers with webpack. :star:88
- [Basic Auth](https://github.com/dommmel/cloudflare-workers-basic-auth) - Protection using basic auth. :star:19
- [Send Logs to Logdna](https://github.com/boynet/cf-logdna-worker) - Simple recipe to send logs to logdna. :star:16
- [IP lookup service](https://github.com/matthewgall/beta.ipinfo.in) - IP lookup service using workers. :star:4
- [Airtable Proxy](https://github.com/portable-cto/airtable-proxy-worker) - Allows you to make secure requests to the Airtable API from your frontend. :star:25
- [TypeScript Workers](https://github.com/udacity/cloudflare-typescript-workers) - Types and mocks for building a tested typescript worker. :star:46
- [Proxies](https://github.com/GitbookIO/proxies-on-cloudflare) - Makes it easy to build workers, by providing high-level proxying primitives addressing common needs. :star:19
- [Static Worker](https://github.com/manatarms/static-worker) - Provides functions that make it easy to host a static website. :star:7
- [Bannero](https://github.com/nondanee/bannero) - Bannero image API for simpledesktops. :star:2
- [Hasura](https://github.com/nathanwaters/hasura-cloudflare-worker) - Example using Facebook-based authorization and graphql proxy queries with hasura. :star:4
- [IP Redirects](https://community.cloudflare.com/t/ip-redirects/18285) - Redirect users based on their ip address.
- [Switch Image to WebP](https://github.com/vidaxl-com/cloudflare_webworkers/blob/master/examples/webp.js) - Reroute image to webp when supported. :star:3
- [Geographic Routing and Load Balancer](https://community.cloudflare.com/t/geographic-routing-and-load-balancing-with-cloudflare-workers/21900) - Geographic routing and load balancing with workers.
- [UTM Tag Stripper](https://community.cloudflare.com/t/strip-utm-query-string/47941) - Strip UTM tags in query string.
- [Short URL Redirector](https://community.cloudflare.com/t/short-url-using-workers/39877) - Redirect short links.
- [Repo Hunt](https://github.com/signalnerve/repo-hunt) - Find cool open-source projects daily. :star:20
- [Performance Optimized Workers](https://github.com/pmeenan/cf-workers) - Collection of worker scripts, generally focused on performance optimizations. :star:71

## Other

- [Support](https://support.cloudflare.com)
- [System Status](https://www.cloudflarestatus.com)
- [Network Map](https://www.cloudflare.com/network)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Irfaq Syed](https://github.com/irazasyed) has waived all copyright and
related or neighboring rights to this work.

> Cloudflare is a registered trademark of Cloudflare, Inc.

