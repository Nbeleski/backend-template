
# Golang Backend Template

Sample structured project for a backend server using golang.
This is a WIP and mostly a reference for myself.

## Project Structure

The project lightly borrows from clean architecture.

```
.
├── cmd
│   └── server
│       └── main.go
├── go.mod
├── internal
│   ├── cinterop
│   │   └── image_processing.go
│   ├── domain
│   │   ├── entities
│   │   │   └── user.go
│   │   ├── repositories
│   │   │   └── user_repository.go
│   │   └── services
│   │       └── user_service.go
│   ├── handlers
│   │   ├── image_handler.go
│   │   └── user_handler.go
│   └── infrastructure
│       ├── database
│       │   ├── postgres.go
│       │   ├── sqlite.go
│       │   └── user_repository.go
│       └── router
│           └── router.go
└── readme.md
```
