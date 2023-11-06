# Docker Example Site
Clone the repository:

```bash
git clone https://github.com/ucalgary-ssd101/docker-example-site.git
```

`cd` to the directory:

```bash
cd docker-example-site
```

Build the Docker image:

```bash
docker build -t ssd101-site .
```

Run the image:

```bash
docker run --rm -p 8080:80 ssd101-site
```

Open the browser to: `localhost:8080`