# Distributed Kv Simulator

    Small distributed key-value simulator with deterministic node routing.

    ## Stack

    - Language: Go
    - Difficulty: very high
    - Scope: small, self-contained service/tool with clear extension points

    ## Project layout

    The repository keeps implementation code under `src/` where that is idiomatic, plus a short runnable entry point and a small sample payload when useful.

    ## Run

    ```bash
    go test ./...
go run .
    ```

    ## Engineering notes

    The implementation keeps parsing, domain logic and output formatting separate enough to grow without turning into a script dump. Generated artifacts and dependency folders are intentionally ignored.
