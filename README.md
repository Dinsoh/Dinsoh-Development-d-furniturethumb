# d-furniturethumb

**A FiveM Furniture & Prop Thumbnail Capture Utility**

Developed by **Dinsoh Development**

A lightweight developer tool designed to simplify the process of generating furniture and prop thumbnail images for FiveM servers.

Instead of manually positioning cameras and taking screenshots of individual objects, d-furniturethumb provides a dedicated workflow for capturing clean, consistent furniture images.

---

## Features

- Furniture and prop thumbnail capturing
- Configurable camera framing
- Adjustable capture settings
- Screenshot exporting
- Support for custom GTA V props
- Lightweight developer-focused resource
- Integration with `screenshot-basic`
- Suitable for creating furniture inventory and catalog images

## Preview

*Add a screenshot or demonstration GIF of the tool here.*

## Requirements

- FiveM Server
- `screenshot-basic`
- Access to the resource's capture commands
- Appropriate filesystem permissions for image exporting

## Installation

1. Download the latest release from GitHub.
2. Extract the resource into your server's `resources` directory.
3. Rename the folder to `d-furniturethumb` if necessary.
4. Install and start `screenshot-basic`.
5. Configure the settings in `config.lua`.
6. Add the following to your `server.cfg`:

```cfg
ensure screenshot-basic
ensure d-furniturethumb
```

7. Restart your server or start the resource manually.

## Configuration

The resource includes a `config.lua` file for managing supported capture settings.

Review the configuration before running the thumbnail capture process.

## Usage

Start the resource, follow its configured capture workflow, and export the resulting images.

For best results, review exported thumbnails to ensure objects are correctly positioned, centered, and visible.

**Note:** Very large or unusually shaped objects may require framing adjustments.

## Intended Use

This resource is intended primarily for FiveM server developers who need thumbnail images for:

- Housing furniture catalogs
- Furniture placement menus
- Inventory images
- Custom prop collections
- Development and testing workflows

## Known Limitations

Certain oversized, irregularly shaped, or unusually positioned props may require additional camera adjustments.

## Support & Feedback

Found a bug or have a suggestion?

Open a GitHub Issue with a description of the problem, relevant console logs, and steps to reproduce it.

## Credits

**Dinsoh Development**

Built for the FiveM development community.

## License

See the `LICENSE` file for permissions and restrictions.
