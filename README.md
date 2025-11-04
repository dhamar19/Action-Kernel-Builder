# Build Recovery using Github Actions

## ⚙️ Parameter Description
| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `DEVICE` | Codename of the device used for kernel build | Blossom |
| `KERNEL_SOURCE` | Kernel source Git repository URL | https://github.com/dhamar19/niigo_kernel_xiaomi_blossom.git |
| `KERNEL_SOURCE_BRANCH` | Branch name of the kernel source | fulmen |
| `DEFCONFIG` | Defconfig name (without `_defconfig` suffix) | blossom |
| `ANYKERNEL_URL` | AnyKernel3 repository URL | https://github.com/dhamar19/AnyKernel3.git |
| `ANYKERNEL_BRANCH` | Branch name for AnyKernel3 | blossom |
| `ENABLE_KERNELSU` | Enables KernelSU patch integration if set to true | true / false |
| `KERNELSU_URL` | Optional KernelSU setup command (only used if KernelSU enabled) | curl -LSs "https://raw.githubusercontent.com/rsuntk/KernelSU/main/kernel/setup.sh" \| bash -s main |
-----
