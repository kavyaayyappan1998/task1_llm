# Part 1 Results

## Architecture
- Character-level GPT-style language model built from scratch
- Transformer blocks: 4
- Hidden size: 256
- Attention heads: 8
- Context length: 128
- Dropout: 0.1
- Parameters: 3,270,815

## Training
- Epochs: 10
- Batch size: 64
- Steps per epoch: 10936
- Validation steps per epoch: 1097
- Optimizer: AdamW
- Initial learning rate: 0.0003
- Warm-up steps: 500
- Device: NVIDIA GeForce RTX 4090
- Total training time (s): 3911.65

## Final Metrics
- Training loss: 0.695788
- Validation loss: 0.663736
- Perplexity: 1.942035
- Bits/character: 0.957569
- Generalization gap: -0.032051
- Top-1 next-character accuracy: 0.787781
- Distinct-1: 0.035484
- Distinct-2: 0.221953
- Distinct-3: 0.466074
- Repeated 4-gram rate: 0.553759
- Peak gradient norm: 7.064823
- NaN count: 0
- Training tokens/sec: 243356.89
- Generation tokens/sec: 467.92
- Peak GPU memory (MB): 940.81

## Files
- Checkpoint: `checkpoints/full/model.pt`
- Metrics: `metrics_report.csv`
- Failure analysis: `failure_analysis.md`
- Outputs: `outputs/`
