I've been watching the Namaste React course and I'm loving it! I'm posting my practice codes from episode 1 here.

Episode 1 additional topics:-

1. what is cdn and why do we need it?
   A Content Delivery Network (CDN) is a system of servers spread out around the world that helps deliver web content other data to users based on their geographic location
   Content Delivery Networks (CDNs) increase performance(it will be fast as it get rresponse rom nearest server), reliability(if one server is down another will take over).

2)but why cdn is not recommended in creating react app
A CDN is not usually recommended for creating a React app because:

Frequent Changes: During development, your code changes a lot. Using a CDN can make it harder to see those changes immediately.
Local Development: Developers work locally, where a CDN isn't needed and can complicate things.
Build and Deploy: React apps are typically bundled into optimized files during deployment. Serving these directly from your server is simpler and ensures the latest version is always used.
However, CDNs are great for serving static assets like images and stylesheets to improve load times for users around the world.

3)what is cache?
a cache is a temporary storage area that keeps copies of data or files so that future requests for that data can be served faster.
