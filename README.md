# ElastAlert Server

This is a fork from https://github.com/Yelp/elastalert

The only advantage of this fork is it fixes https://github.com/Yelp/elastalert/issues/2204 

which occurs when you run ElastAlert with Elastic Search of versions 6 and higher.


## Release a docker image
  
    docker build --build-arg ELASTALERT_VERSION=v0.2.0b2 -t papyrusglobal/elastalert:latest .
    docker push papyrusglobal/elastalert:latest
  