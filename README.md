# Evaluation Function API

<div style="text-align:center" align="center">
 <img src="https://github.com/lambda-feedback/evaluation-function-api/actions/workflows/openapi_docs.yml/badge.svg?branch=main" />
 <a href="https://lambda-feedback.github.io/evaluation-function-api/">
    <img src="https://img.shields.io/badge/Docs-OpenAPI-blue?logo=github&labelColor=24292E"/>
 </a>
</div>

This Repository contains the specification and validation schemas for the
Lambda Feedback Evaluation Function API.

## Overview

The Evaluation Function API uses an RPC-like approach via HTTP, handling commands in the command HTTP header. It evaluates student responses with the `eval` command. For more complex cases, the optional `preview` command allows to perform lightweight checks without full evaluation.

### Command Header

The `command` header specifies the action to be performed by the evaluation function. The API currently supports two commands: `eval` and `preview`.

Historically, some evaluation functions may also support the two legacy commands `healthcheck` and `docs`, which are used for health checks and documentation retrieval, respectively. However, these commands are considered deprecated.

### Documentation

The full documentation is available [here](https://lambda-feedback.github.io/evaluation-function-api/).
