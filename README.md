# BEATs 音频事件识别 · ONNX

上游模型权重的 ONNX 转换分发，供 HiTi_code 的「设置 → 本地模型」页按需下载。**非官方渠道**，与上游项目及 HiTi_code 项目均无隶属关系。

- 上游：<https://github.com/microsoft/unilm/tree/master/beats>
- 模型卡：<https://huggingface.co/microsoft/beats>
- 许可证：MIT，全文见 LICENSE；权利归属与修改说明见 NOTICE.md

## 下载

每个变体单独一个资产，只下要用的那一档：

| 变体 | 体积 | 直接下载 |
| --- | --- | --- |
| int4 | 70.5 MB | [beats-int4.zip](https://github.com/xixi3548942758-design/BEATs-ONNX-for-HiTi_code/releases/download/v1.0/beats-int4.zip) |
| int8 | 101.8 MB | [beats-int8.zip](https://github.com/xixi3548942758-design/BEATs-ONNX-for-HiTi_code/releases/download/v1.0/beats-int8.zip) |

## 目录结构

解压后目录名与 HiTi 的 AI_model 目录下同名目录一致，直接放进去即可：

```
BEATs/
  beats-int4.onnx 或 beats-int8.onnx
  beats_labels.json  beats_names.json  meta.json
```

## 使用与再分发

- 同一模型的不同量化档（int4 / int8）只选一个放进目录，不要同时放。
- 再分发时必须保留 LICENSE 与 NOTICE.md，保留模型名称，并注明上游出处。
