__OTEL-Instrumentation__

- Trace instrumentation with `GO` opentelemetry `SDK`
- Go Gin framework instrumentation with `gin.Context`

__Visualization with Jaeger__

OpenTelemetry Go and Jaeger Tracing: Export traces to Jaeger.

### HOW TO RUN?
setup `mongodb` and `Jaeger` instances using docker compose.

````shell
docker-compose up
````

### RUN SERVER

````shell
go run cmd/main.go
````

__Jaeger Local Address__

````text
http://localhost:16686/search
````

__App address__

````text
http://localhost:8080/todo
````