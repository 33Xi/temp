# Checkpoint download

jiuge-fm9g-1p2b-s500-onepass / iter_0391225 / mp_rank_00

[Download the checkpoint from GitHub Releases](https://github.com/33Xi/temp/releases/tag/checkpoint-jiuge-fm9g-1p2b-s500-onepass-iter0391225).

The original `model_optim_rng.pt` is 16,993,884,244 bytes and is distributed in 9 ordered parts. Download all `model_optim_rng.pt.part*` assets and `SHA256SUMS` to one directory.

```bash
sha256sum -c SHA256SUMS
cat model_optim_rng.pt.part[0-9][0-9][0-9] > model_optim_rng.pt
echo '01b55aa8df394c9e37de96f3f8a843864976e25c8d96c8472fe71da32cdf709f  model_optim_rng.pt' | sha256sum -c -
```

The release also includes `manifest.json` and `RESTORE.md`.
