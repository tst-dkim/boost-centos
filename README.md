# Updated Boost libraries for CentOS 6.x

I basically hacked the SPEC file for the RPMs produced for SuSe and got these
to work on our boxes without much of a hitch. Will compile fine against gcc
4.4.7. I'm not sure for how much longer or if all the C++11 bindings will
work but our crude testing so far hasn't revealed any problems compared to just
doing a straight `./boostrap.sh` developer-style cowboy coder installation.
