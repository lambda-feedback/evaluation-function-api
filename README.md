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

The Evaluation Function API uses an RPC-like approach via HTTP, handling commands in the command HTTP header. It evaluates student responses with the eval command. For more complex cases, the optional preview command allows to perform lightweight checks without full evaluation.
