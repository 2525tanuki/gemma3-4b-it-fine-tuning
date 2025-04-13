# gemma3-4b-it-fine-tuning

## ディレクトリ構造

```bash
├── gemma # gemma3 4b itのベンチマークによる評価
│   ├── ja_vg_vqa_500.ipynb
│   ├── ja_vlm_bench_in_the_wild.ipynb
│   └── japanese_heron_bench.ipynb
├── gemma_sft # fine-tuningのコードと、ベンチマークによる評価
│   ├── ja_vg_vqa_500_py.ipynb
│   ├── ja_vlm_bench_in_the_wild_py.ipynb
│   ├── japanese_heron_bench.ipynb
│   └── sft_latest.ipynb
├── README.md
└── upload_hf.ipynb # HFのuploadのコード

```

## ベンチマークによる評価

### gemma3-jicvqa-sft 評価結果

| Benchmark                   | ROUGE-L            |
|-----------------------------|--------------------|
| japanese-heron-bench        | 31.956091217206772 |
| ja-vlm-bench-in-the-wild    | 29.21825823674845  |
| ja-vg-vqa-500               | 8.497517725345373  |

### gemma3-4b-it 評価結果

| Benchmark                   | ROUGE-L            |
|-----------------------------|--------------------|
| japanese-heron-bench        | 29.086823873934478 |
| ja-vlm-bench-in-the-wild    | 23.63929335578921  |
| ja-vg-vqa-500               | 7.244518172773382  |

## hugging face

[2525tanuki/gemma3-jicvqa-sft](https://huggingface.co/2525tanuki/gemma3-jicvqa-sft/blob/main/README.md)


## reference

- [turing-motors/Japanese-Heron-Bench](https://huggingface.co/datasets/turing-motors/Japanese-Heron-Bench)
- [SakanaAI/JA-VLM-Bench-In-the-Wild](https://huggingface.co/datasets/SakanaAI/JA-VLM-Bench-In-the-Wild/tree/main)
- [SakanaAI/JA-VG-VQA-500](https://huggingface.co/datasets/SakanaAI/JA-VG-VQA-500)
- [llm-jp-eval-mm](https://github.com/llm-jp/llm-jp-eval-mm/tree/master)
