# BEATs 音频事件识别  BEATs 音频事件识别模型（ONNX）。HiTi 仅内置最基础模型，此仓库提供按需下载的高阶模型。  ## 下载（每个变体单独一个资产）  | 变体 | 体积 | 直接下载 | | --- | --- | --- |
| int4 | 70.5 MB | [beats-int4.zip](upload beats-int4.zip -> hiti-model-beats (70.5 MB)   ok https://github.com/xixi3548942758-design/hiti-model-beats/releases/download/v1.0/beats-int4.zip https://github.com/xixi3548942758-design/hiti-model-beats/releases/download/v1.0/beats-int4.zip) |
| int8 | 101.8 MB | [beats-int8.zip](upload beats-int8.zip -> hiti-model-beats (101.8 MB)   ok https://github.com/xixi3548942758-design/hiti-model-beats/releases/download/v1.0/beats-int8.zip https://github.com/xixi3548942758-design/hiti-model-beats/releases/download/v1.0/beats-int8.zip) |

## 目录结构

解压后与 HiTi `AI_model` 下同名目录一致，直接放入即可：

```
BEATs/
  beats-int4.onnx 或 beats-int8.onnx
  beats_labels.json  beats_names.json  meta.json
```

模型来源：PaddlePaddle / SenseVoice / BEATs 官方发布，仅做 ONNX 量化转换，遵循各自原始许可证。