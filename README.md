# Sheet Music Code

## What is it?

A domain-specific language for musicians to compose and notate music through a simplified syntax thatgenerates the sheet music output as PDF documents.

# Architecture

1. Evaluator (Visitor Pattern)
  * Evaluator **APP_EVALUATOR.py** (and **APP_VISITOR.py**) follow the visitor pattern described in class (UBC CPSC 410)

2. Tokenizer
  * Tokenizer class in **tokenizer.py** follows the Tokenizer taught in class (UBC CPSC 410).
