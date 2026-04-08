# Structured Output Learning (LangChain + Pydantic + TypedDict)

This repository contains my learning notebook where I experimented with **structured outputs using LLMs**.

The notebook demonstrates how to use:

- `TypedDict`
- `Pydantic BaseModel`
- `Literal`
- `LangChain structured outputs`
- `Gemini / LLM integration`

## Notebook

`output_parser.ipynb`

The notebook includes examples such as:

### 1. TypedDict Basics
Creating structured dictionary schemas using `typing.TypedDict`.

Example:

```python
class Design(TypedDict):
    name: str
    age: int
    height: float
    hobbies: list[str]
