---
title: "easy-day-js Targets Mastra, Dependency Attacks Grow"
url: "https://www.sonatype.com/blog/easy-day-js-targets-mastra-dependency-attacks-grow"
date: "2026-06-17"
author: "Sonatype Security Research Team"
feed_url: "https://www.sonatype.com/blog/rss.xml"
---
Security researchers identified a supply chain attack involving the npm package easy-day-js, designed to impersonate the dayjs library and added as a dependency to compromised Mastra AI framework packages. Once installed, it used postinstall scripts to download and execute remote payloads. The campaign demonstrates an emerging pattern where attackers hijack trusted packages and use malicious dependencies as delivery mechanisms rather than publishing entirely new malicious packages.
