# world-simplest-riff-function


```bash
export DOCKER_ID=....

riff function create command wsrf \
  --git-repo https://github.com/making/world-simplest-riff-function.git \
  --artifact hello.sh \
  --image ${DOCKER_ID}/wsrf \
  --verbose
```

```
riff service invoke wsrf --text -- -d riff
```
