# HiT: Human Inertial Transformer — project page

Static page (`index.html`, `static/`), no build step. The lab website serves a copy at https://spice-lab.org/projects/HiT/
(`static/projects/HiT/` in the spice-lab.org repository); canonical and link-card URLs point there.

- Paper and code buttons: set `LINKS.arxiv` and `LINKS.code` at the top of `static/js/main.js`; while a link is empty the button shows "soon".
- BibTeX: edit the `<pre id="bibText">` block in `index.html` once the arXiv identifier exists.
- Media in `static/video` and `static/img` are generated from the paper's figures and renders.
- Interactive demos replay stored outputs of the paper's runs: SMPL videos of IMUPoser test recordings (Fig. 4 and three more,
  `static/video/pose`) with the per-frame MPJPE in `static/demo/pose/index.json` (`static/js/posevid.js`), and the Ego-Exo4D
  caption examples in `static/demo/captions.json` (`static/js/captions.js`).
