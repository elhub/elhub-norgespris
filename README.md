# Elhub - Norgespris

This is the external project repository for the Norgespris project @ Elhub. This repository contains OpenAPI
specifications and JSON schemas for interfaces to be used by external systems that need to read (and write)
data about Norgespris to the Elhub system.

The purpose of this repository is to facilitate early transparency and collaboration with Market Parties and
System vendors in the power market. By making the specifications publicly available, we invite developers,
vendors, and other stakeholders to begin integration planning, provide feedback, and help us shape the best
possible interfaces for the ecosystem.

## 📌 Status

> [!IMPORTANT]
> These specifications are under active development and subject to change. The purpose of releasing this at this
> early stage is to give opportunities for feedback and (if necessary) to iterate over the solution. We recommend
> syncing regularly to stay up to date with the latest changes.

Version: v0.1 (Pre-release)

> [!NOTE]
> Please note that this is a specification repository only. Implementation details and code are tracked separately.

## 📘 Contents

- `docs/schemas/` – JSON Schemas defining domain models and payload structures
- `docs/examples/` – Example request/response payloads
- `docs/openapi.yaml` - OpenAPI 3.x specification
- `docs/api-docs.yaml` - OpenAPI 3.x specification - bundled version

### Bundling

For bundling we use the npm package `@redocly/cli` and the command

```bash
redocly bundle openapi.yaml -o api-docs.yaml
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/elhub/elhub-norgespris.git
   ```
2. Navigate the specification files in the openapi/ and schemas/ directories.
3. Use an IDE or similar tool with Swagger UI support visualize and explore the OpenAPI spec locally.

## The Norgespris Life Cycle

Read more about the Norgespris Life Cycle [here](/docs/contracts/norgespris/README.md)

![Norgespris Life Cycle](/docs/contracts/norgespris/norgespris_status.png)

## 📢 Contributing

We welcome your feedback and contributions. Use:

- [Discussions](https://github.com/elhub/elhub-norgespris/discussions) – Please use the Discussions tab for open-ended feedback, questions and dialogue.
- E-mail (developers) - If you have technical questions that are not suited for Github, contact us at: ![Dev Email](/docs/assets/mail-norgespris.png)
- Other Requests - For other questions or requests, contact us using normal contact channels: ![Elhub Email](/docs/assets/mail-post.png)

See the
[Contributing](https://github.com/elhub/auth-grant-manager/blob/main/.github/CONTRIBUTING.md) file for general guidelines.

## License

This project is licensed under the MIT License - see the
[LICENSE](https://github.com/elhub/auth-grant-manager/blob/main/LICENSE) file for details.
