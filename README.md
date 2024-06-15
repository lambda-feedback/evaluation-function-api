# Evaluation Function API

<p style="text-align:center">
 <img src="https://github.com/lambda-feedback/evaluation-function-api/actions/workflows/openapi_docs.yml/badge.svg?branch=main" />
 <object data="https://img.shields.io/badge/Docs-OpenAPI-blue?logo=github&labelColor=24292E&link=https%3A%2F%2Flambda-feedback.github.io%2Fevaluation-function-api%2F" type="image/svg+xml"></object>
</p>

This Repository contains the specification and validation schemas for the
Lambda Feedback Evaluation Function API.

## Overview

The Evaluation Function API uses an RPC-like approach via HTTP, handling commands in the command HTTP header. It evaluates student responses with the eval command. For more complex cases, the optional preview command allows to perform lightweight checks without full evaluation.
