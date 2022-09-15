# {{project-name}}

{{description}}

## Generator usage

This project was generated via the `cargo-generate` tool and `cargo-generate-all` template.

For example,

```bash
cargo generate digitalsanctum/cargo-generate-all --name foo -d github_user=digitalsanctum -d description="Some description here"
```

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
