Tracks
======
[![Docker image layers](https://images.microbadger.com/badges/image/ssaavedra/tracks.svg)](https://microbadger.com/images/ssaavedra/tracks)

Tracks is a web-based application to help you implement David Allens Getting Things Done™ methodology. It was built using Ruby on Rails.

This is the easy way getting up and running with Tracks, which is one of the greatest software implementations of the GTD™ methodology.

This builds main parts are:
 - Tracks 2.3.0 (stable)
 - Ubuntu 14.04
 - Apache 2 (Passenger)
 - Sqlite3
 - Dockerize (Utility to simplify running applications in docker containers)

It utilizes mostly native Ubuntu 14.04 packages, thus rebuilding it will provide the latest updates.

For production use it is highly recommended to update the `site.yml.template` within the build repo, rename it to `site.yml` then rebuild the container.

Example on how to run the Tracks container:

     docker run -d --name=tracks -p 80:80 staannoe/tracks


 

References:
http://www.getontracks.org/

