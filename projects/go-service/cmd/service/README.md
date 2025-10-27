# Go Service - Service

This directory will contain the main entry point for the Go microservice.

## Expected Structure

When real code is added, the following should be present:

- `main.go` - Application entry point
- `go.mod` - Go module definition (at repository root or service root)
- `go.sum` - Go dependency checksums
- Test files (`*_test.go`)

## Expected Commands

- **go vet ./...** - Static analysis to find potential bugs
- **go test ./...** - Run all tests in the module

## Foundation CI Detection

The foundation CI workflow (`.github/workflows/ci.yml`) will automatically detect this as a Go project when:

- A `go.mod` file exists in the repository root or project directory

Once detected, CI will:

1. Run `go vet ./...` to perform static analysis
2. Run `go test ./...` to execute tests

## Getting Started

(To be added when real code is implemented)
