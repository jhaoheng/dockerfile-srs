# readme

This Dockerfile made from srs-2.0-release : `https://github.com/ossrs/srs.git`

# change srs version
Change srs git source branch in Dockerfile, like below show

```
RUN     git clone https://github.com/ossrs/srs.git && \
        cd srs/trunk && \
        git checkout 3.0release
``` 