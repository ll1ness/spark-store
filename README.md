# <img src="logo.png" width="32" height="32" style="border-radius:50%"> Spark Store

The official store of extensions for Spark Studio 18

A repository for hosting and distributing extensions and add-ons for the Spark Studio projects. It is an integral part of the Spark Studio ecosystem, allowing developers to extend the functionality of the application and share their work with the community.

## Review

Spark Store is a centralized catalog integrated into Spark Studio that provides users with an easy way to find, install, and update extensions for their IDE. The project is built on the principles of open source and is distributed under the GPLv3 license, which guarantees freedom of use, modification, and distribution.

## Opportunities

- Centralized extension catalog: A convenient repository for all available plugins and add-ons.
- IDE integration: Seamless installation and management of extensions directly from the Spark Studio interface.
- Community support: A developer platform that allows you to share your extensions with other users.
- Security and transparency: Open source and GPLv3 license ensure the verifiability and reliability of distributed components.

## Repository structure

| Directory/File | Description |
| :--- | :--- |
| `extensions/` | Contains the source code and extension files. Each extension is located in a separate subfolder. |
| `store/` (Planned) | Internal structure for the store, metadata, and indexes. |
| `version` | File containing the current version of the store or API for compatibility with the Spark Studio client. |
| `LICENSE` | Full text of the GNU General Public License v3.0. |

## Getting Started

### For users (installing extensions)

Extensions from the Spark Store are installed directly through the Spark Studio interface. To do this:

1. Open Spark Studio.
2. Go to the extension store section (Extensions menu or similar).
3. Browse the available catalog and select the desired extension.
4. Click the "Install" button. The IDE will automatically download and integrate the extension into your environment.

### For developers (adding your own extensions)

To make your extension available in the Spark Store, you need to:

1. Create an extension for Spark Studio by following the platform's documentation and API.
2. Make it a separate directory inside `extensions/` with the required manifest files.
3. Create a Pull Request in this repository with your extension added.

Please ensure that your extension:

- Is distributed under a license compatible with GPLv3.
- Contains a clear description, version, and author information.
- Does not contain malicious or destructive code.

## For whom this project is intended

- PHP/JavaFX developers using Spark Studio to create cross-platform applications.
- Extension creators who want to share their tools with the community.
- All Spark Studio users who want to expand the capabilities of their IDE.

## Authors

- **ll1ness** - Project initiator, integration with Spark Studio

## License

This project is distributed under the GNU General Public License v3.0. The full license text is available in the LICENSE.

---

© 2026 ll1ness. The project is part of the Spark Studio ecosystem.
