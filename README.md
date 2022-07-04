# longstitch-docker
Debian 10 with longstitch scaffolding pipeline


Run e.g. like so:
```bash
user@host-$ docker run -v $(pwd):/in -w /in --rm chrishah/longstitch:v1.0.1 longstitch
```

Run test:
```bash
user@host-$ git clone https://github.com/bcgsc/LongStitch.git
user@host-$ cd LongStitch/tests
user@host-$ docker run -v $(pwd):/in -w /in --rm chrishah/longstitch:v1.0.1 ./run_longstitch_demo.sh
```
