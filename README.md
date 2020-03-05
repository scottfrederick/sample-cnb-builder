# Sample Bionic Builder

### Prerequisites
* [Pack](https://buildpacks.io/docs/install-pack/)

### Usage

#### Creating the builder

```bash
scripts/build.sh
```

#### Build app with builder

```bash
pack build sample-app --builder sample-builder:bionic --path path/to/jar
```

_After building the app you should be able to simply run it via `docker run -it -p 8080:8080 sample-app`.
Go to [localhost:8080](http://localhost:8080) to see the app running._
