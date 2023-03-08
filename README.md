# NVIDIA-VGPU-Driver-Archive

This repository contains history versions of NVIDIA vGPU drivers.  
这个仓库包含了 NVIDIA vGPU 驱动的历史版本.

| Tag       | #0                                                           | #1                                                           | #2                                                           | #3                                                           | #4                                                           | #5                                                           | #6                                                           |
| --------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **15.0+** | [15.0](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/15.0) | [15.1](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/15.1) |                                                              |                                                              |                                                              |                                                              |                                                              |
| **14.0+** | [14.0](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/14.0) | [14.1](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/14.1) | [14.2](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/14.2) | [14.3](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/14.3) | [14.4](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/14.4) |                                                              |                                                              |
| **13.0+** | [13.0](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/13.0) | [13.1](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/13.1) | [13.2](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/13.2) | [13.3](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/13.3) | [13.4](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/13.4) | [13.5](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/13.5) | [13.6](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/13.6) |
| **12.0+** | [12.0](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/12.0) | [12.1](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/12.1) | [12.2](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/12.2) | [12.3](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/12.3) | [12.4](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/12.4) |                                                              |                                                              |
| **11.0+** | [11.0](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/11.0) | [11.1](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/11.1) | [11.2](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/11.2) | [11.3](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/11.3) | [11.4](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/11.4) | [11.5](https://github.com/justin-himself/NV-VGPU-Driver-Archive/releases/tag/11.5) |                                                              |



## Download and Extract

Because of the Github Release 2GB size limit, for some larger files I had to upload them in splitted zip volumes,
So you need to download all `7z.00*` files to able to decompress.

## Preview

To get you a rough idea of what each zip contains, here's the `tree` output of fully extracted 15.0 branch.  

https://github.com/justin-himself/NV-VGPU-History-Driver/blob/master/preview.txt

## About Drivers

> Which driver version I should choose?

- Proxmox and most linux QEMU hypervisor: LINUX_KVM
- Windows and hyperV: Windwos
- ESXI (vSphere): vSphere

> Windows Driver

NVIDIA uses the same driver for both windows host and guest machines.

For example, if you search `527.41_grid_win10_win11_server2019_server2022_dch_64bit_international.exe` in [15.0](https://github.com/justin-himself/NV-VGPU-History-Driver/blob/master/preview.txt) branch, you will find multiple windows drivers scattered in different folders, and they are all same. 

So if you are on a windows host, want to use the card directly, or you are passing through the whole card to a windows virtual machine, just use any windows driver in the branch.

## Source

- NVIDIA Drivers - [NVIDIA Licensing - Software Downloads](https://ui.licensing.nvidia.com/software)



