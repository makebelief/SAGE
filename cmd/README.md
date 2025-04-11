# Application Entry Point
**By Shayo Victor Otieno (Software Engineer)**

## 📂 Files
- `main.go`: Main application entry point
  - Initializes HTTP server
  - Sets up routes and middleware
  - Coordinates module initialization
- `README.md`: This documentation file

## 🏗️ Architecture
The cmd directory follows the Go standard project layout pattern:
1. Server initialization with graceful shutdown
2. Dependency injection for all modules
3. Centralized configuration management

## 🛠️ Usage
```bash
go run cmd/main.go --port=8080 --env=prod

