# Curriculum Vitae
[PDF](CV.pdf)

# Build/compile
This repo comes with a Docker environment for compiling the LaTeX source code.  

1. Build and run the environment
```
docker-compose build
docker-compose run env
```

2. Build document within container:
```
./build.sh
```

3. Refresh CV.pdf