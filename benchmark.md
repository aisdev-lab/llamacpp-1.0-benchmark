# Performance

---

## engine 

llama-cpp • Vulkan • 0.9.0-dev (build 12169, commit 3ed7284f2)

## model

ISTA-DASLAB/Qwen3.8-27b-GSQ-IQ3-S



## Prefill — cold

Cold (cache_prompt: false), full prompt processing every round.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| prefill_512 | 512 | 662.8 | 663.5 | 665.2 |
| prefill_2k | 2k | 890.9 | 892.2 | 895.1 |
| prefill_8k | 8k | 981.3 | 981.8 | 984.3 |
| prefill_16k | 16k | 957.7 | 959.3 | 960.7 |
| prefill_32k | 32k | 883.7 | 885.1 | 886.3 |
| prefill_64k | 64k | 756.1 | 756.5 | 757.1 |
| prefill_128k | 128k | 583.1 | 583.3 | 583.4 |

## Prefill — warm KV reuse

Warm KV reuse (cache_prompt: true) on the same context.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| warm_512 | 512 | 4559.2 | 4696.3 | 4762.5 |
| warm_2k | 2k | 15666.4 | 15795.6 | 15941.6 |
| warm_8k | 8k | 59212.3 | 59736.5 | 60588.0 |
| warm_16k | 16k | 115899.1 | 117202.2 | 121379.8 |
| warm_32k | 32k | 224895.6 | 227763.1 | 228687.4 |
| warm_64k | 64k | 401091.3 | 406432.7 | 420195.3 |
| warm_128k | 128k | 680170.8 | 688979.2 | 697699.2 |

## Decode

Decode (cache_prompt: true) on the same context.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| decode_256 | 256 | 180.7 | 218.8 | 219.8 |
| decode_512 | 512 | 125.7 | 479.1 | 480.9 |
| decode_8k | 8k | 182.3 | 220.3 | 220.5 |
| decode_16k | 16k | 229.1 | 393.8 | 394.9 |
| decode_32k | 32k | 140.0 | 140.2 | 140.4 |


---

## engine 

llama-cpp • ROCm • 1.0.0-dev (build 12429, commit 9fba51d2c)

## model

ISTA-DASLAB/Qwen3.8-27b-GSQ-IQ3-S


## Prefill — cold

Cold (cache_prompt: false), full prompt processing every round.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| prefill_512 | 512 | 653.0 | 657.3 | 660.9 |
| prefill_2k | 2k | 886.6 | 887.1 | 887.5 |
| prefill_8k | 8k | 976.1 | 977.0 | 978.6 |
| prefill_16k | 16k | 952.7 | 953.9 | 954.4 |
| prefill_32k | 32k | 881.2 | 881.9 | 882.5 |
| prefill_64k | 64k | 759.0 | 759.2 | 759.3 |
| prefill_128k | 128k | 588.6 | 588.8 | 588.9 |

## Prefill — warm KV reuse

Warm KV reuse (cache_prompt: true) on the same context.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| warm_512 | 512 | 4584.1 | 4694.3 | 4715.8 |
| warm_2k | 2k | 15386.9 | 15698.4 | 16069.8 |
| warm_8k | 8k | 58875.8 | 60398.6 | 60923.1 |
| warm_16k | 16k | 116362.2 | 118120.0 | 119428.5 |
| warm_32k | 32k | 223181.8 | 227148.5 | 230436.8 |
| warm_64k | 64k | 403776.7 | 406796.2 | 414268.4 |
| warm_128k | 128k | 676572.6 | 679148.9 | 684643.2 |

## Decode

Decode (cache_prompt: true) on the same context.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| decode_256 | 256 | 219.1 | 219.2 | 220.0 |
| decode_512 | 512 | 125.2 | 475.3 | 476.2 |
| decode_8k | 8k | 181.7 | 219.3 | 219.5 |
| decode_16k | 16k | 227.2 | 390.8 | 391.6 |
| decode_32k | 32k | 139.7 | 139.7 | 139.8 |


---

## engine 

llama-cpp • Vulkan • 0.9.0-dev (build 12169, commit 3ed7284f2)

## model

ISTA-DASLAB/Qwen3.8-27b-GSQ-IQ3-S

## Prefill — cold

Cold (cache_prompt: false), full prompt processing every round.

| title | context size | median speed (tokens/s) |
| --- | --- | --- |
| prefill_512 | 512 | 536.8 |
| prefill_2k | 2k | 745.9 |
| prefill_8k | 8k | 826.5 |
| prefill_16k | 16k | 800.1 |
| prefill_32k | 32k | 719.1 |
| prefill_64k | 64k | 591.8 |
| prefill_128k | 128k | 440.5 |

## Prefill — warm KV reuse

Warm KV reuse (cache_prompt: true) on the same context.

| title | context size | median speed (tokens/s) |
| --- | --- | --- |
| warm_512 | 512 | 3456.8 |
| warm_2k | 2k | 11718.4 |
| warm_8k | 8k | 45162.7 |
| warm_16k | 16k | 89252.7 |
| warm_32k | 32k | 169836.8 |
| warm_64k | 64k | 314783.0 |
| warm_128k | 128k | 550715.0 |

## Decode

Decode (cache_prompt: true) on the same context.

| title | context size | median speed (tokens/s) |
| --- | --- | --- |
| decode_256 | 256 | 157.5 |
| decode_512 | 512 | 141.2 |
| decode_8k | 8k | 223.1 |
| decode_16k | 16k | 79.2 |
| decode_32k | 32k | 119.3 |


---

## engine 

llama-cpp • Vulkan • 1.0.0-dev (build 12429, commit 9fba51d2c)

## model

ISTA-DASLAB/Qwen3.8-27b-GSQ-IQ3-S

## Prefill — cold

Cold (cache_prompt: false), full prompt processing every round.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| prefill_512 | 512 | 549.3 | 550.6 | 551.6 |
| prefill_2k | 2k | 767.4 | 768.4 | 769.1 |
| prefill_8k | 8k | 851.0 | 851.1 | 852.7 |
| prefill_16k | 16k | 831.5 | 832.1 | 832.6 |
| prefill_32k | 32k | 761.3 | 762.1 | 762.7 |
| prefill_64k | 64k | 641.3 | 642.0 | 642.6 |
| prefill_128k | 128k | 452.0 | 452.4 | 452.7 |

## Prefill — warm KV reuse

Warm KV reuse (cache_prompt: true) on the same context.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| warm_512 | 512 | 3710.2 | 3733.1 | 3759.0 |
| warm_2k | 2k | 12653.5 | 12735.0 | 12800.1 |
| warm_8k | 8k | 48235.3 | 49448.6 | 49691.0 |
| warm_16k | 16k | 96661.8 | 96945.2 | 98484.2 |
| warm_32k | 32k | 182100.8 | 186326.7 | 187613.2 |
| warm_64k | 64k | 336410.1 | 338409.0 | 343402.0 |
| warm_128k | 128k | 586469.5 | 588084.9 | 595452.2 |

## Decode

Decode (cache_prompt: true) on the same context.

| title | context size | lowest speed (tokens/s) | median speed (tokens/s) | highest speed (tokens/s) |
| --- | --- | --- | --- | --- |
| decode_256 | 256 | 158.5 | 159.4 | 160.2 |
| decode_512 | 512 | 71.3 | 197.9 | 202.7 |
| decode_8k | 8k | 55.6 | 110.7 | 111.1 |
| decode_16k | 16k | 25.9 | 111.2 | 219.9 |
| decode_32k | 32k | 83.7 | 122.0 | 122.2 |
