# DDNS

*Decentralised Domain Name System*

---

## Introduction

In Q4 2021, labs³ will attempt to register the namespace `.ddns` on BNS. This will be the beginning of building a decentralised and censorship-resistant Web 3.0 on Bitcoin. 

Domains registered on DDNS are globally unique, strongly owned, human-readable and hijack-resistant.

To access a DDNS site, you'll have to change your current DNS servers to ones that support DDNS. We'll host a number of these servers initially, but the code is open-source and we encourage you to run your own. You can run one on your local network for people using it, or open it up for everyone on the internet to use. the more the merrier :)

## Using DDNS

DDNS sites don't use TLDs like Web 2.0 domains do (eg. instead of https://apple.com/, you'd visit https://apple). This is what distinguishes DDNS names from Web2.0 domains.

Names aren't registered to a single database (like ICANN) and anyone can create one. Funds generated from the registration fees will directly support metaverse, and make it harder for massdomain registrations.

When you visit 'https://example' using DDNS, the DNS resolver will resolve 'example.ddns' on the blockchain using a Stacks node connected to the DDNS server you connected to.
When you visit 'https://example.com' using DDNS, the resolver will resolve 'example.com' on Web 2.0 as usual.

## Subdomains

Subdomains exist on DDNS in a similar way to how they work on Web 2.0 but inversed. Instead of subdomain.example.com like on Web 2.0, you'd visit example.subdomain. If you want to visit 'https://example.subdomain', the DNS resolver will resolve subdomain.example.ddns on the blockchain using a Stacks node. 

Some issues arise from this as DDNS servers resolve both Web 2.0 and 3.0 names/domains. To prevent this, subdomains that are Web 2.0 TLDs (like 'com', 'org', 'co') will be resolved as Web 2.0 domains. If you own the 'example' name on DDNS, and you add the subdomain 'com', visits to 'example.com' will resolve to the Web 2.0 domain and not the subdomain you set up. This is to prevent duplicate name/domain conflicts between Web 2.0 & 3.0.
