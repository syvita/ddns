# DDNS

*Decentralised Domain Name System*

---

## Introduction

In Q4 2021, metaverse will attempt to register the namespace `.ddns` on BNS. This will be the beginning of building a decentralised and censorship-resistant Web 3.0 on Bitcoin. 

Domains registered on DDNS are globally unique, strongly owned, human-readable and hijack-resistant.

To access a DDNS site, you'll initially need to either change your current DNS servers to ones that support DDNS or install the browser extension. We recommend changing your DNS settings. We'll host a number of these servers, but the code is open-source and anyone can run one. You can run one on your local network for people using it, or open it up for everyone to use.

## Using DDNS

DDNS sites don't use TLDs like Web2.0 domains do (eg. instead of https://apple.com/, you'd visit https://apple). This is what distinguishes DDNS names from Web2.0 domains.

Names aren't registered to a single database (like ICANN) and anyone can create one. Funds generated from the registration fees will directly support metaverse, and make it harder for massdomain registrations.

When you visit 'https://example' using DDNS, the DNS resolver will resolve example.ddns on the blockchain using a Stacks node. 
When you visit 'https://example.com' using DDNS, the resolver will resolve example.com on Web 2.0 as usual.

## Subdomains

Subdomains exist on DDNS in a similar way to how they work on Web 2.0. If you want to visit 'https://subdomain.example', the DNS resolver will resolve example.ddns on the blockchain using a Stacks node. 

Issues arise when the name is a TLD that Web 2.0, like .com. For example, if someone registers the name 'com', DDNS servers will not resolve any of its subdomains as they will have the same address as a Web 2.0 domain unless the user requesting the resolution explicitly prioritises DDNS names over Web 2.0 domains. By default, this option is disabled, but will be enabled by default in the future.
