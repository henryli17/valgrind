# Valgrind Docker Container

`docker build -t memory-test:0.1 .`
`docker run -ti -v $PWD/test:/test memory-test:0.1`

[Tutorial](https://www.gungorbudak.com/blog/2018/06/13/memory-leak-testing-with-valgrind-on-macos-using-docker-containers/)