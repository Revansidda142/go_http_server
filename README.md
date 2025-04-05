# Simple Go HTTP Server

A lightweight HTTP server implementation in Go that demonstrates basic web server functionality.

## Features

- Basic HTTP server implementation
- Multiple endpoint handlers
- Request logging
- Static file serving
- JSON response support

## Requirements

- Go 1.21 or higher

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Revansidda142/go_http_server.git
```

2. Navigate to the project directory:
```bash
cd go_http_server
```

3. Run the server:
```bash
go run main.go
```

The server will start on `http://localhost:8080`

## API Endpoints

- `GET /` - Home page
- `GET /health` - Health check endpoint
- `GET /api/time` - Returns current server time
- `POST /api/echo` - Echoes back the JSON request body

## License

MIT License