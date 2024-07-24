# Nugget Cases
**⚠️ This project is replaced by [DevKitty](https://devkitty.io) ⚠️**  
This repo contains old Nugget enclosures & design files.

## 📖 Contents
Each version contains the following subfolders:
- 📁 `src`: FreeCAD design files for Nugget cases
- 📁 `print`: Exported `stl` files ready to print

A Nugget case is comprised of:
- `Top`
- `Bottom`
- `D-Pad`
- `Bumper`

## 🗄 Versions
### `v2`
The `v2` design is comprised of a screen, microcontroller, breakout header, and a couple peripherals (buttons + NeoPixel).
The case design exposes the Microcontroller pin headers for easy access and features a window for the NeoPixel + Screen.

### `v3`
The `v3` design added a [Qwiic]() connector, and [JST Connector]() for LED strips.  The case was updated with a cutout for these interfaces, and also adds a bumper button for toggling the [Boot Button]() on the microcontroller, allowing for easy firmware updates.  This case is backwards compatible.

## 📝 Notes
- Original cases weren't designed with tolerances, so we recommend scaling the `stl` files in a slicer to `101%` in the `X`/`Y` dimensions before printing.
- For design requests, create a new issue on this repo.
