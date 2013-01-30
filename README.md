#Dota 2 WebAPI Examples#

WebAPI forum: http://dev.dota2.com/forumdisplay.php?f=411

<br>


###Example 1: Live League Game Signature Image###

![Signature](http://server.danieljennings.net/live_league_signature.php)

*This image is an example of what the signature looks like, but is not live itself.*

#####Requirements:#####
* A web server capable of serving PHP pages (e.g. http://httpd.apache.org/)
* PHP5 (http://www.php.net)
* ImageMagick for PHP5 (http://www.php.net/manual/en/imagick.installation.php)
* Memcached for PHP5 (http://www.php.net/manual/en/memcached.installation.php)

#####Demonstrates:#####
* WebAPI: GetLeagueListing
* WebAPI: GetLiveLeagueGames
* Caching: Using Memcached to reduce latency by caching WebAPI results
* Images: Using ImageMagick to render images on-demand.

<br>
