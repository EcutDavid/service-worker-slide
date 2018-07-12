# service worker slide
Slide for my service worker talk: [davidguan.me/service-worker-slide](http://davidguan.me/service-worker-slide)

## FAQ
1. How many sw an origin can have?
A service worker registration is a tuple of a scope url and a set of service workers, an installing worker, a waiting worker, and an active worker. A user agent may enable many service worker registrations at a single origin so long as the scope url of the service worker registration differs.
