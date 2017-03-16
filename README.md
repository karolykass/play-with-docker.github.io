# Docker 4th birthday repo 


## Live Site

[http://birthday.play-with-docker.com/](http://birthday.play-with-docker.com/)

## Contributing

Just check the [posts](https://github.com/franela/franela.github.io/tree/master/_posts) folder and submit your tutorials there.


## Running trainings site locally

Clone the repo and run the following docker container: `docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 4000:4000 jekyll/jekyll jekyll serve`

Browse the site by visiting http://localhost:4000
