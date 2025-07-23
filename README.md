![badge](https://github.com/lackingworth/Go-Notely/actions/workflows/ci.yml/badge.svg) ![badge](https://github.com/lackingworth/Go-Notely/actions/workflows/cd.yml/badge.svg)
# Notely

## Local Development

Make sure you're on Go version 1.22+.

Create a `.env` file in the root of the project with the following contents:

```bash
PORT="8080"
```

Run the server:

```bash
go build -o notely && ./notely
```

*This starts the server in non-database mode.* It will serve a simple webpage at `http://localhost:8080`.

*Work in progress*