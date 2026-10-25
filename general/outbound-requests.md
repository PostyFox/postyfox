# Outbound Requests

Outbound requests from our platform that we host(generally regarded as "bot" traffic), has a specific pattern; it comes from specific set of IP Addresses (which we provide to folk like FurAffinity and Cloudflare for the purposes of whitelisting), but we also use a number of UserAgents as well.

The combination of these two things are enough for websites to identify us (fingerprint) to know with confidence that it is us - and therefore, trust our traffic, without putting their websites at risk.

Our current active user agent is:

```
Mozilla/5.0 (compatible; PostyFox/1.0; +http://docs.postyfox.com)
```

