# Dark Flare — BBH merger emission in AGN disks

Interactive visualization of the electromagnetic counterpart ("Dark Flare") of a
stellar-mass binary black hole merger inside an AGN accretion disk, with live
LSST g/r/i light curves of the McKernan et al. (2019) kicked-remnant /
ram-stripped Hill-sphere model.

The merger itself emits only gravitational waves — the sole optical emission is
the delayed off-center hot spot left by the kicked remnant.

Developed by **P. Darc**, based on:

> P. Darc, C. R. Bom, C. D. Kilpatrick, A. Souza Santos, B. Fraga,
> J. C. Rodríguez-Ramírez, D. A. Coulter, C. Mendes de Oliveira, A. Kanaan,
> T. Ribeiro, W. Schoenell, E. A. D. Lacerda (2025),
> *Long-Term Optical Follow Up of S231206cc: Multi-Model Constraints on BBH
> Merger Emission in AGN Disks*, [arXiv:2506.02224](https://arxiv.org/abs/2506.02224)

Model: McKernan, Ford, Bartos et al. 2019, ApJL 884, L50; light-curve shape per
Graham et al. 2020 (ZTF19abanrhr).

## Deploy on GitHub Pages

The whole site is one self-contained file (`index.html`) — no build step, no
dependencies (fonts load from Google Fonts; everything else is embedded).

1. Create a repository, e.g. `darkflare` (or `<username>.github.io` for a root site).
2. Add `index.html` and this `README.md` to the repository root and push.
3. On GitHub: **Settings → Pages → Build and deployment** — Source: *Deploy from
   a branch*; Branch: `main`, folder `/ (root)`. Save.
4. After ~1 minute the page is live at `https://<username>.github.io/darkflare/`.

## Citation

```bibtex
@misc{darc2025longtermopticalfollows231206cc,
      title={Long-Term Optical Follow Up of S231206cc: Multi-Model Constraints on BBH Merger Emission in AGN Disks},
      author={P. Darc and C. R. Bom and C. D. Kilpatrick and A. Souza Santos and B. Fraga and J. C. Rodríguez-Ramírez and D. A. Coulter and C. Mendes de Oliveira and A. Kanaan and T. Ribeiro and W. Schoenell and E. A. D. Lacerda},
      year={2025},
      eprint={2506.02224},
      archivePrefix={arXiv},
      primaryClass={astro-ph.HE},
      url={https://arxiv.org/abs/2506.02224},
}
```
