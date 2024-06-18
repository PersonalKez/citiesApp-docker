This is the compose file for building/orchestrating the following respositories in addition to this repository:

- https://github.com/PersonalKez/citiesApp_BE
- https://github.com/PersonalKez/citiesApp_fe

As well as the official and unaltered dockerhub images for:
- mysql
- nginx
- memcached

To form a travel diary. Effectively a database containing names, countries, and travel times of cities. For my personal use (I travel a lot) but also to serve as a CRUD skeleton for other scalable apps such as blog posts and twitter-likes. 

Stack:
- vanillaJS + HTML, speed over pretty formatting and overly-complex interactions
- nodeJS, easier to just use JS everywhere in a more 'casual' app
- NGINX, ease of use and config, beginning to take over from Apache
- MYSQL, used everywhere, relatively simple. Sort of regret not using postgres though. 
- memcached, used everywhere, mostly simple to use. NodeJS lib is a bit spotty though so watch out if you take the same route

TO USE
docker compose up
localhost:8089
enjoy