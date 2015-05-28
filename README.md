# rpi-python3

[![dockeri.co](http://dockeri.co/image/maxkueng/rpi-python3)](https://registry.hub.docker.com/u/maxkueng/rpi-python3/)

Raspberry Pi compatible Docker base image with Python preinstalled.

Run all the commands from within the project root directory.

### Build Details
- [Source Repository](https://github.com/maxkueng/rpi-python3)
- [Dockerfile](https://github.com/maxkueng/rpi-python3/blob/master/Dockerfile)
- [DockerHub] (https://registry.hub.docker.com/u/maxkueng/rpi-python3/)


#### Build the Docker Image
```bash
make build
```

#### Run the Docker Image and get the version of the installed Python
```bash
make version
```

#### Push the Docker Image to the Docker Hub
* First use a `docker login` with username, password and email address
* Second push the Docker Image to the official Docker Hub

```bash
make push
```

## License

The MIT License (MIT)

Copyright (c) 2015 Max Kueng
Copyright (c) 2015 Hypriot

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

