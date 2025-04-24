# GPU Datasheet

## Blackwell
| Architecture | Name | GPU Memory | Memory Bandwidth | FP16 / BF16 | FB8 / INT8 | FP4 | Datasheet |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Blackwell | B200 | 1.44 TB | 64 TB/s | 36 PFLOPS | 72 PFLOPS | 144 PFLOPS | [Link](https://resources.nvidia.com/en-us-dgx-systems/dgx-b200-datasheet) |
| Blackwell | GB200 | 13.5 TB |  | 360 PFLOPS (FP16) | 720 PFLOPS (FP8) | 1440 PFLOPS | [Link](https://resources.nvidia.com/en-us-dgx-systems/dgx-superpod-gb200-datasheet) |

## Hopper
| Architecture | Name | GPU Memory | Memory Bandwidth | FP16 / BF16 | FB8 / INT8 | Datasheet |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Hopper | H100 | 80 GB | 3.35 TB/s | 1979 TFLOPS (BF16 / FP16) | 3958 TFLOPS (FP8) | [Link](https://resources.nvidia.com/en-us-tensor-core/nvidia-tensor-core-gpu-datasheet) |
| Hopper | H200 | 141 GB | 4.8 TB/s | 1979 TFLOPS (BF16 / FP16) | 3958 TFLOPS (FP8) | [Link](https://resources.nvidia.com/en-us-data-center-overview-mc/en-us-data-center-overview/hpc-datasheet-sc23-h200) |
| Hopper | H800 | 80 GB | 3.35 TB/s | 1979 TFLOPS (BF16 / FP16) | 3958 TFLOPS (FP8) | [Link](https://chaoqing-i.com/upload/20231128/NVIDIA%20H800%20GPU%20Datasheet.pdf) |

## Ampere
| Architecture | Name | GPU Memory | Memory Bandwidth | FP16 / BF16 | FB8 / INT8 | Datasheet |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Ampere | A100 | 40 GB | 1.55 TB/s | 312 TFLOPS (FP16) | 624 TOPS (INT8) | [Link](https://www.nvidia.com/content/dam/en-zz/Solutions/Data-Center/a100/pdf/nvidia-a100-datasheet-us-nvidia-1758950-r4-web.pdf) |
| Ampere | A100 | 80 GB | 1.94 TB/s | 312 TFLOPS (FP16) | 624 TOPS (INT8) | [Link](https://www.nvidia.com/content/dam/en-zz/Solutions/Data-Center/a100/pdf/nvidia-a100-datasheet-us-nvidia-1758950-r4-web.pdf) |
| Ampere | A10 | 24 GB | 600 GB/s | 125 TFLOPS (FP16) | 250 TOPS (INT8) | [Link](https://www.nvidia.com/content/dam/en-zz/Solutions/Data-Center/a10/pdf/a10-datasheet.pdf) |
| Ampere | A40 | 48 GB | 696 GB/s | 149.7 TFLOPS (BF16 / FP16) | 299.3 TOPS (INT8) | [Link](https://images.nvidia.cn/content/Solutions/data-center/a40/nvidia-a40-datasheet.pdf) |

## Ada Lovelace
| Architecture | Name | GPU Memory | Memory Bandwidth | FP16 / BF16 | FB8 / INT8 | Datasheet |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Ada Lovelace | L40 | 48 GB | 864 GB/s | 181.05 TFLOPS (BF16 / FP16) | 362 TFLOPS (FP8) | [Link](https://images.nvidia.com/content/Solutions/data-center/vgpu-L40-datasheet.pdf) |
| Ada Lovelace | L40s | 48 GB | 864 GB/s | 362.05 TFLOPS | 733 TFLOPS (FP8) | [Link](https://resources.nvidia.com/en-us-l40s/l40s-datasheet-28413?ncid=no-ncid) |

## GeForce
| Architecture | Name | GPU Memory | Memory Bandwidth | TOPS | Datasheet |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Ampere | GeForce RTX 3090 | 24 GB | 936 GB/s | 285 TOPS | [Link](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5090/#specs) |
| Ada Lovelace | GeForce RTX 4090 | 24 GB | 1 TB/s | 1321 TOPS | [Link](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5090/#specs) |
| Blackwell | GeForce RTX 5090 | 32 GB | 1.79 TB/s | 3352 TOPS | [Link1](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5090/#specs) | [link2](https://images.nvidia.com/aem-dam/Solutions/geforce/blackwell/nvidia-rtx-blackwell-gpu-architecture.pdf)|

## NVLink
| Generation | Architecture | Connection each | Links per GPU | Total Bandwidth |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| NVLink1 | Pascal | 40 GB/s | 4 | 160 GB/s |
| NVLink2 | Volta | 50 GB/s | 6 | 300 GB/s |
| NVLink3 | Ampere | 50 GB/s | 12 | 600 GB/s |
| NVLink4 | Hopper | 50 GB/s | 18 | 900 GB/s |
| NVLink5 | Blackwell | 100 GB/s | 18 | 1.8 TB/s |

- Note
    - H800: 400 GB/s, [Link](https://chaoqing-i.com/upload/20231128/NVIDIA%20H800%20GPU%20Datasheet.pdf)

## References
[NVLink NVSwitch](https://hc34.hotchips.org/assets/program/conference/day2/Network%20and%20Switches/NVSwitch%20HotChips%202022%20r5.pdf)
[NVLink and NVLink Switch (Cloud & Data Center)](https://www.nvidia.com/en-us/data-center/nvlink/)