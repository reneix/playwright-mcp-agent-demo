# playwright-mcp-agent-demo

A minimal demo that uses Spring Boot 3.4.5, Spring AI Alibaba 1.1.0.0, ReactAgent, and Playwright MCP to drive browser-based automation.

## What it does

- Builds a ReactAgent-based automation service
- Connects to a Playwright MCP server
- Exposes simple HTTP endpoints to run and resume agent tasks
- Can be used to automate browser workflows such as GitHub operations

## Tech stack

- Java 21
- Spring Boot 3.4.5
- Spring AI Alibaba 1.1.0.0
- Spring AI MCP Client
- Playwright MCP

## Run

```bash
mvn spring-boot:run -Dspring-boot.run.profiles=local
```

## Notes

- The project expects a running Playwright MCP server
- Model credentials should be configured locally before running
- This repository was bootstrapped through browser automation for verification purposes
