---
title: "Developing a Fediverse App"
tags:
- tech
- fediverse
---

Developing an app for Fediverse requires you to know lot of protocols (rules; you need to follow them for communications; need not implement all of them) and standards (guidelines). Here are the protocols. As I develop more understanding, I will add more notes here.

- Webfinger (service discovery)
	- Spec: https://www.rfc-editor.org/rfc/rfc7033
- ActivityPub
	- Spec: https://www.w3.org/TR/activitypub/
	- ActivityStreams
	- Actors Object
		- Spec: https://www.w3.org/TR/activitypub/#actors
	- ActivityPub Objects
- HTTP Signatures
- Linked Data Signatures
- [[notes/OAuth2]] (only if you want to develop a Mastodon API compliant app; not needed if you want to add ActivityPub to your existing app)

## Specs
- [ActivityPub Spec](https://www.w3.org/TR/activitypub/)

## Reference Implementations (Mastodon)
- https://takahe-server.readthedocs.io/en/latest/features/
- https://docs.gotosocial.org/en/latest/api/swagger/
- https://docs.joinmastodon.org/client/public/
- https://humungus.tedunangst.com/r/honk
- https://takahe-server.readthedocs.io/en/latest/features/
- https://docs.microblog.pub/

## References
- [Things I've learned about ActivityPub so far](https://raphaelluckom.com/posts/Things%20I%27ve%20learned%20about%20ActivityPub%20so%20far.html)
- https://indieweb.org/Micropub
- testing: https://micropub.rocks/
- https://indieweb.org/Mastodon