# {{project-name}}-api

{{description}}

## Build

```bash
cargo clean && cargo build --release
```


## Package

Create a Docker image with the binary:

```bash
docker build -t {{project-name}}-api .
```


## Run

Via binary:
```bash
cargo run
```

Via Docker:
```bash
docker run -d -p 8080:8080 --name {{project-name}}-api {{project-name}}-api
```
