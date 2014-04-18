## Install FreeRadius 2.2.1 w/ Docker

### Using This Repo

```
git clone git@github.com:tomislacker/docker-freeradius.git
cd docker-freeradius
docker build -rm -no-cache -t tomislacker/freeradius .
```

## Roadmap
### Revised Dockerfile
One of the things I'm looking to do is move all the calls in scripts/install_freeradius.sh to the Dockerfile
