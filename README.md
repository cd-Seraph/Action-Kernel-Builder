# Action-Kernel-Builder
Github Action for Compiling Kernel from Source

## Notes
Make sure to edit `build` file to suits your need.

Change kernel source url with your own, with respective branch you wanna use (if theres a lot branches).

Change defconfig, you could find it in default directory `arch/arm64/configs/`, or in `arch/arm64/configs/vendor`. If your defconfig is in the vendor/ directory, make sure to add your defconfig as `vendor/name_defconfig`.

Change compiler and toolchain based on your preferred version, or based on what your kernel source needs. If you can extract ikconfig on your current kernel, you can check what version used in compiling your stock.

## Release
- You should be able to find Image, Image.gz, Image.gz-dtb or whatever name it has in release page.
- Pick one that you actually need.
