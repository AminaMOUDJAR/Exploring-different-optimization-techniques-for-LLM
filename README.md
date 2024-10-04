This repo presents the practical work of my Master's thesis that has explored the optimization of large language models for task-specific applications, with a
particular focus on Arabic-to-English machine translation. I have demonstrated that full fine-tuning offers
the best performance but comes at a high computational cost. By contrast, parameter-efficient techniques
such as LoRA, DoRA, and QLoRA provide more resource-friendly alternatives, striking a balance between
model performance and computational efficiency.
In the experiments on AraT5v2 Base and NLLB200-600M, I observed that LoRA and DoRA maintain
competitive translation quality while significantly reducing GPU memory usage and power consumption.
QLoRA, with its quantization approach, further minimizes memory usage but requires longer training times.
