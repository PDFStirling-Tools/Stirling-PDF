# Stirling PDF

A complete open-source workspace for PDF documents. Use it as a desktop application, open it in your browser, or host it on your own server with a private API. Every file is processed locally, so your documents never leave your control.

## What It Can Do

- **Works on any setup** – install it on your computer, use it through a web interface, or run it as a server for your whole team.
- **Dozens of built-in tools** – edit text and pages, merge and split files, add signatures, hide sensitive data, convert between formats, recognize text in scans and shrink file size.
- **Automated processing** – build step-by-step workflows right in the interface without writing code, and handle large batches of documents automatically.
- **Ready for business** – single sign-on, activity logs and full control over where and how the platform is deployed.
- **Built for developers** – almost every tool is available through a REST API, so it fits easily into existing products and services.
- **Speaks your language** – the interface is translated into many languages.

## Getting Started

The quickest way to try it is with Docker:

    docker run -p 8080:8080 stirlingtools/stirling-pdf

When the container is running, open port 8080 on your machine in any browser and start working.

Desktop installers and other setup options are described in the project documentation.

## Help and Community

Have a question or want to share an idea? Join the community chat or open an issue in this repository. Bug reports with clear steps to reproduce are especially appreciated.

## Contributing

Pull requests are always welcome. Before you start, take a look at the contributing guidelines in this repository.

All common development tasks (building, running and testing) are handled by a single command runner. Run `task dev` to launch the editor in development mode, or just `task` to see the full list of available commands.

Want to add a new interface language? The repository includes a separate guide on adding translations.

## License

Stirling PDF follows an open-core model. The full license terms are in the LICENSE file of this repository.
