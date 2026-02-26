<div align="center">

# Facebook
### CSE 326 — Information System Design

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
![Course](https://img.shields.io/badge/Course-CSE%20326-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Academic%20Project-orange?style=flat-square)

</div>

---

A system design project for **CSE 326: Information System Design**, modelling a Facebook-like social media platform. The project covers the full design lifecycle — from business process modelling and use case analysis to class modelling, UI mockups, interaction diagrams, and a RESTful API specification.

---

## 🗂️ Design Artifacts

| # | Document | Description |
|---|---|---|
| 0 | [Proposal](0.Proposal.pdf) | Project scope & requirements |
| 1 | [BPMN Diagram](1.BPMN.svg) | Business Process Model & Notation |
| 2 | [Use Case Diagram](2.UsecaseDiagram.pdf) | Actors & system interactions |
| 3 | [Class Diagram](3.ClassDiagram.svg) | Object-oriented domain model |
| 4 | [Mock UI](4.MockUI.pdf) | UI/UX wireframes |
| 5 | [Collaboration Diagrams](5.CollaborationDiagrams/) | Object collaboration patterns |
| 6 | [Sequence Diagrams](6.SequenceDiagram.pdf) | Interaction flows |
| 7 | [State Diagrams](7.StateDiagrams/) | State machine models |

---

## 🔌 API Documentation

A complete **OpenAPI 3.0** specification is available in [`openapi.yaml`](openapi.yaml).

To view the interactive Swagger UI:

1. Go to [editor.swagger.io](https://editor.swagger.io)
2. **File → Import File** → select `openapi.yaml`

Or run locally with Docker:

```bash
docker run -p 8080:8080 \
  -e SWAGGER_JSON=/api/openapi.yaml \
  -v $(pwd):/api \
  swaggerapi/swagger-ui
```

Then open `http://localhost:8080`.

---

## 👥 Team

| Name               | GitHub |
|--------------------|--------|
| Dibbo Chowdhury    | [@RudraShivm](https://github.com/RudraShivm) |
| Nujhat Sadia       | [@nujhat-sadia](https://github.com/nujhat-sadia) |
| Sudip Kumar Saha   | [@SudipSaha00002](https://github.com/SudipSaha00002) |
| Navin Nawar        | [@navwar0](https://github.com/navwar0) |