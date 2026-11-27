# Awesome-Image-Segmentation-Background-Removal

# Awesome-Image-Segmentation-Background-Removal

Top Image Segmentation Background Removal (Opensource) 🌟 Star if you like it! 🌟

A curated list of top image segmentation, automated background removal, alpha matting, interactive promptable segmentation (SAM), and video matting tools—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.

---

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)
  - [Automated Background Removal Libraries & CLIs](#automated-background-removal-libraries--clis)
  - [State-of-the-Art Segmentation & Matting Models](#state-of-the-art-segmentation--matting-models)
  - [Interactive & Promptable Foundation Models (SAM Ecosystem)](#interactive--promptable-foundation-models-sam-ecosystem)
  - [Browser-Based & WebGPU Client-Side Background Removers](#browser-based--webgpu-client-side-background-removers)
  - [Video Background Removal & Real-Time Matting](#video-background-removal--real-time-matting)
- [Contributing](#contributing)

---

## SaaS/Hosted Platforms

Commercial, cloud-hosted AI background removal services, online photo editors, and proprietary visual asset APIs.

* **[Remove.bg](https://remove.bg)** - Industry-standard commercial AI background removal web platform and high-throughput API for instant subject isolation.
* **[Photoroom](https://photoroom.com)** - AI-powered product photography and background removal SaaS platform featuring studio lighting, shadows, and batch editing.
* **[Clipdrop (Jasper)](https://clipdrop.co)** - Suite of cloud AI image editing tools offering high-precision background removal, relighting, and object cleanup.
* **[Slazzer](https://slazzer.com)** - Commercial automated background remover providing desktop apps, e-commerce plugins, and REST APIs.
* **[Adobe Express Background Remover](https://adobe.com)** - Adobe's cloud-hosted one-click background removal tool powered by Adobe Firefly and Photoshop masking technology.
* **[Canva Background Remover](https://canva.com)** - Integrated SaaS design tool enabling instant background extraction inside cloud graphic design workflows.
* **[Photopea](https://photopea.com)** - Proprietary browser-based raster and vector image editor offering magic cut and AI background removal tools.
* **[Pixlr](https://pixlr.com)** - Cloud-based photo editing suite featuring AI cutout, batch background removal, and smart selection tools.
* **[Cutout.pro](https://cutout.pro)** - Commercial visual design platform providing AI photo/video background removal, portrait cutouts, and face segmentation APIs.
* **[Erase.bg](https://erase.bg)** - Cloud-based AI background removal tool optimized for e-commerce product shots, logos, and portraits.

---

## Open-Source Equivalents & Tools

Free and open-source software (FOSS) background removal libraries, high-resolution dichotomous segmentation models, interactive matting tools, and local WebGPU apps.

### Automated Background Removal Libraries & CLIs

* **[Peel (tuguidragos)](https://github.com)** - Clean, fast, open-source background removal tool and pipeline engineered for effortless subject extraction.
* **[rembg](https://github.com)** - The most popular open-source Python library, CLI, and HTTP server for removing image backgrounds using multiple pretrained models (U2-Net, IS-Net, BiRefNet).
* **[transparent-background](https://github.com)** - Open-source command-line tool and Python package powered by InSPyReNet for high-resolution image and video background removal.
* **[CarveKit](https://github.com)** - Automated, high-quality open-source background removal framework combining Tracer-B7, U2-Net, and FBA Matting for crisp edges.
* **[WithoutBG](https://github.com)** - Open-source, privacy-first background removal toolkit designed for clean local inference and batch workflows.

### State-of-the-Art Segmentation & Matting Models

* **[BiRefNet (Bilateral Reference Network)](https://github.com)** - State-of-the-art open-source high-resolution dichotomous image segmentation model delivering razor-sharp hair and edge cutouts.
* **[RMBG-1.4 / RMBG-2.0 (BRIA AI Open Weights)](https://huggingface.co)** - High-precision open-weights background removal model trained on diverse commercial, product, and portrait datasets.
* **[IS-Net (DIS - Dichotomous Image Segmentation)](https://github.com)** - Highly accurate open-source segmentation network engineered for fine-grained object boundaries and intricate structures.
* **[U-2-Net](https://github.com)** - Lightweight, nested U-structure deep network widely used as the foundational backbone for fast salient object detection and background removal.
* **[MODNet](https://github.com)** - Real-time, trimap-free open-source portrait matting network capable of high-speed human cutout on consumer hardware.
* **[ViTMatte](https://github.com)** - Open-source Vision Transformer matting framework achieving fine alpha-matte detail around hair, fur, and translucent objects.

### Interactive & Promptable Foundation Models (SAM Ecosystem)

* **[Segment Anything Model 2 (SAM 2 - Meta)](https://github.com)** - Meta's unified open-source foundation model for promptable visual segmentation across both images and videos in real time.
* **[Grounded-SAM-2](https://github.com)** - Open-source pipeline combining Grounding DINO with SAM 2 to detect, segment, and remove backgrounds using text prompts.
* **[MobileSAM](https://github.com)** - Lightweight, mobile-friendly open-source implementation of Segment Anything running orders of magnitude faster on edge CPUs/GPUs.
* **[FastSAM](https://github.com)** - CNN-based real-time Segment Anything alternative achieving 50x faster inference speeds for interactive masking.
* **[X-AnyLabeling](https://github.com)** - Open-source desktop annotation and segmentation studio integrating SAM 2, BiRefNet, and YOLO for interactive masking.

### Browser-Based & WebGPU Client-Side Background Removers

* **[@imgly/background-removal-js](https://github.com)** - Open-source JavaScript library performing 100% client-side AI background removal directly in the browser via ONNX Runtime Web and WebGPU.
* **[Transformers.js (Hugging Face)](https://github.com)** - Run state-of-the-art segmentation models (RMBG, SegFormer, SAM) natively in the browser with WebGPU acceleration and zero server uploads.
* **[BgBye (Local WebUI)](https://github.com)** - Self-hosted, open-source web interface bundling top open-weights background removal models for side-by-side comparison and local batch processing.
* **[GIMP + BIMP / Rembg Plugins](https://gimp.org)** - Free and open-source raster graphics editor extensible with open-source AI segmentation and background removal plugins.

### Video Background Removal & Real-Time Matting

* **[Robust Video Matting (RVM)](https://github.com)** - Fast, temporally coherent open-source human video matting network running in real time at 4K/HD without green screens.
* **[BackgroundMattingV2](https://github.com)** - Real-time, high-resolution open-source video matting framework using a captured clean background plate for studio-grade separation.
* **[OBS Background Removal Plugin](https://github.com)** - Open-source OBS Studio plugin enabling real-time AI webcam background removal and portrait segmentation locally on CPU/GPU.
* **[MatAnyone](https://github.com)** - Open-source stable video matting framework maintaining consistent target assignment and crisp boundaries across long video sequences.

---

## Contributing

Contributions are welcome! Feel free to open a Pull Request to add more open-source image segmentation models, background removal tools, or matting pipelines.

1. Fork the repository.
2. Add your project under the appropriate category with a concise description.
3. Submit a Pull Request.
