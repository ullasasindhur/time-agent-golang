# Time Agent (Golang)

This project is an agent written in Go that tells the current time in a specific city. It is built using the Google ADK.

## Reference
For more information on the Google ADK, visit:
https://google.github.io/adk-docs/get-started/go/

## Instructions to Run

Follow these steps to set up and run the agent on your local machine.

### 1. Initialize the Module
Run the following commands to initialize the Go module and fetch the required dependencies:

```/dev/null/shell#L1-2
go mod init my-agent/main
go mod tidy
```

### 2. Set the API Key (Windows)
You need to set the `GOOGLE_API_KEY` environment variable. In PowerShell, use the following command:

```/dev/null/powershell#L1
$env:GOOGLE_API_KEY = "AI....."
```

### 3. Run the Agent
Finally, run the agent using:

```/dev/null/shell#L1
go run agent.go
```
 