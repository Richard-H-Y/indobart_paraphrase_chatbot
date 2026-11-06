# IndoBART Indonesian Paraphrase Chatbot: Diagnosing and Mitigating Extractive-Compression Bias

Code, and results for the paper **"Diagnosing and Mitigating Extractive-Compression Bias in an IndoBART-Based Indonesian Paraphrase Chatbot"**

> *Summary:* Fine-tuning IndoBART on an Indonesian paraphrase corpus tends to cause the model to shorten input sentences and copy them verbatim. This repository contains notebook for deploying the model as a Telegram chatbot.

## Authors

| | |
|---|---|
| **Name** | Viny Christanti Mawardi |
| **University** | Universitas Tarumanagara (UNTAR), Jakarta |
| **Email** |  `vinym@fti.untar.ac.id` |
| **Name** | Richard Harris Yuwono |
| **University** | Universitas Tarumanagara (UNTAR), Jakarta |
| **Email** |  `richard.535250058@stu.untar.ac.id` |
| **Name** | Khresnanda Putra Wirawan |
| **University** | Universitas Tarumanagara (UNTAR), Jakarta |
| **Email** |  `khresnanda.535250071@stu.untar.ac.id` |
| **Name** | Elysia Nyoman |
| **University** | Universitas Tarumanagara (UNTAR), Jakarta |
| **Email** |  `elysia.535250056@stu.untar.ac.id` |

## Data and model files

- The dataset `generated-par.full.id` and the trained checkpoints are **not** stored in this repo.

## Limitations

One corpus, one test set, one base architecture (IndoBART). Meaning-changing substitutions still pass the filters. The human evaluation is small (3 raters, 100 inputs, weak agreement). The chatbot handles single-turn requests only, and latency was measured on the model side only. See Section 4.7 of the paper.