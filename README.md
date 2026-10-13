

# Feiyu Jia

**Homepage: [fjia-xu.github.io](https://fjia-xu.github.io/)** · [CV (PDF)](https://fjia-xu.github.io/assets/FeiyuJia_CV.pdf)

I am a research assistant in the [Systems and Artificial Intelligence (SAI) Lab](https://www.saiqianzhang.com/Lab/)
at New York University, working with [Prof. Sai Qian Zhang](https://www.saiqianzhang.com/) on efficient large
language models: post-training quantization at very low bit widths, and efficient multi-node serving with
speculative decoding.

I received my M.S. in Computer Engineering from NYU (2026) and my B.Sc. in Data Science and Technology from
HKUST (2024). I am applying to Ph.D. programs for Fall 2027.

**Research interests:** low-bit quantization · model compression · efficient LLM inference and serving ·
speculative decoding · algorithm–hardware co-design

## Publications

- **CoBIT: Unified Optimization of Codebooks, Assignments, and Activation Composition for Extreme Low-Bit LLM Quantization**<br>
  Xiangyang Yin, **Feiyu Jia**, Henry Kam, Tianhua Xia, Qi Sun, Sai Qian Zhang<br>
  *Under review at ICLR 2027* · [OpenReview](https://openreview.net/forum?id=nEuM4oO9hI)
- **DSD-Sim: A Simulation Framework for Distributed Speculative Decoding in Multi-Node LLM Serving**<br>
  Leshu Li, Fengze Yu, Yifei Feng, **Feiyu Jia**, Jian Li, Hao Wang, Bradley McDanel, Sai Qian Zhang<br>
  *Under review at AAAI 2027*
- **Video Face Swap with DeepFaceLab**<br>
  **Feiyu Jia**\*, Sihan Yang\* (\*equal contribution)<br>
  *Proc. SPIE 12168 (ICCAID 2021), 2022* · [DOI](https://doi.org/10.1117/12.2631297)

## Contact

- Email: fj2182@nyu.edu · fjiaqwer@gmail.com
- GitHub: [@fjia-xu](https://github.com/fjia-xu)
- LinkedIn: [Feiyu Jia](https://www.linkedin.com/in/feiyu-jia-a90322334)

## About this repository

This repository holds the source of the homepage above. It is a single static page served by GitHub Pages
from the `main` branch, with no framework and no build step.

```
index.html               the page: text, styles (light and dark themes) and a small copy-to-clipboard script
assets/photo.jpg         portrait
assets/FeiyuJia_CV.pdf   CV
```

Fonts (Newsreader, IBM Plex Sans and IBM Plex Mono) load from Google Fonts. The paper thumbnails are small
inline SVG drawings.

- **Preview locally:** run `python3 -m http.server` in this folder and open <http://localhost:8000>.
- **Update:** edit `index.html`, or replace a file in `assets/` under the same name, and commit to `main`.
  GitHub Pages republishes the site within a minute or two.

You are welcome to reuse the layout and code. Please replace the personal content (text, photo and CV)
with your own.
