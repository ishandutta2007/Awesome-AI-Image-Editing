# Awesome-AI-Image-Editing

## Top AI Image Editing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Inpainting, Background Removal & Agent-Driven Image Generation*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Image Editing**. These tools enable creators, marketers, and developers to remove objects, swap backgrounds, retouch portraits, expand canvases, and generate entirely new images—using diffusion models, segmentation, and agentic editing workflows.



**Examples** include Adobe Photoshop (Generative Fill), Photoroom, Canva, Remove.bg, Clipdrop, Pixlr, Luminar Neo, Topaz Labs, Pixelcut, and Photopea (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, inpainting, and agent-driven editing—ideal for photographers, designers, and developers seeking transparent, vendor-independent image editing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Adobe Photoshop (Generative Fill)](https://www.adobe.com/products/photoshop.html)**  

  Industry-standard image editor with **Generative Fill** powered by Adobe Firefly. Add, remove, or expand content with text prompts. **Content Credentials** for AI provenance tracking.



- **[Photoroom](https://www.photoroom.com/)**  

  AI photo editing for e-commerce. Features background removal, AI backgrounds, object removal, and batch editing. **The most e-commerce-focused managed editor.**



- **[Canva](https://www.canva.com/)**  

  Design platform with Magic Studio AI features. Background remover, Magic Eraser, Magic Edit, and text-to-image generation integrated into template-based design.



- **[Remove.bg](https://www.remove.bg/)**  

  **The most widely used background removal service.** One-click background removal with API access. Free for low-resolution, paid for HD and batch processing.



- **[Clipdrop (Jasper)](https://clipdrop.co/)**  

  AI image editing suite. Features Cleanup (object removal), Uncrop (image expansion), Relight, and background removal. API available.



- **[Pixlr](https://pixlr.com/)**  

  Browser-based photo editor with AI tools. Features AI image generation, background removal, and object removal.



- **[Luminar Neo](https://skylum.com/luminar)**  

  AI-powered photo editor for desktop. Features sky replacement, portrait enhancement, and generative tools.



- **[Topaz Labs](https://www.topazlabs.com/)**  

  AI-powered image enhancement. Features Gigapixel (upscaling), Photo AI (denoising, sharpening), and Video AI.



- **[Pixelcut](https://www.pixelcut.ai/)**  

  AI photo editing for e-commerce. Background removal, product staging, and batch editing.



- **[Photopea](https://www.photopea.com/)**  

  **Free browser-based Photoshop alternative.** Supports PSD, XCF, Sketch, XD, and Figma formats. **The most feature-complete free browser editor.**



## Open-Source GitHub Projects



- **[PhotoCraft (storytold)](https://github.com/storytold/photocraft)**  

  **Agent-driven, open-source AI image editing and generation** (open-source, TypeScript/Next.js). **The most agent-native open-source image editing platform available.** Features **conversational editing** (describe changes in natural language), **multi-provider AI** (Google Gemini, OpenAI, Anthropic), **background removal**, **image generation**, **batch processing**, and **project management** . **The emerging pattern for agent-augmented creative workflows.**



- **[IOPaint](https://github.com/Sanster/IOPaint)**  

  **The leading open-source inpainting tool** (Apache-2.0) powered by SOTA AI models. **20,000+ GitHub stars.** Features **multiple inpainting models** (LaMa, MAT, FcF, Manga, PIOPaint), **interactive web UI**, **CLI and API access**, **batch processing**, and support for **NVIDIA GPU, Apple Silicon, and CPU**. Can run as a plugin for Photoshop, GIMP, and other editors . **The most widely used open-source object removal and inpainting tool.**



- **[LaMa (Large Mask Inpainting)](https://github.com/advimman/lama)**  

  **Resolution-robust large mask inpainting model** (Apache-2.0) from Samsung AI. **10,000+ GitHub stars.** Uses **Fourier convolutions** for high-quality inpainting on large masks. **Foundation model behind many watermark removal tools including IOPaint.** Trained on Places2 and CelebA-HQ datasets .



- **[MAT (Mask-Aware Transformer)](https://github.com/fenglinglwb/MAT)**  

  Mask-aware transformer for high-resolution image inpainting (license varies). Uses transformer architecture for handling large missing regions with high fidelity. **Available in IOPaint model selection.**



- **[Stable Diffusion Inpainting](https://github.com/runwayml/stable-diffusion)**  

  Diffusion-based inpainting model (CreativeML Open RAIL-M). Uses Stable Diffusion with inpainting-specific training for high-quality content reconstruction. **Available via Hugging Face Diffusers.**



- **[ZITS (Zero-Shot Inpainting)](https://github.com/DQiaole/ZITS_inpainting)**  

  Zero-shot inpainting via incremental transformer structure (MIT). **1,000+ GitHub stars.** Uses pretrained transformer for inpainting without task-specific training. Handles complex structures and textures .



- **[GFPGAN](https://github.com/TencentARC/GFPGAN)**  

  **GAN-based face restoration** (Apache-2.0) for recovering faces after editing or degradation. **35,000+ GitHub stars.** **The standard open-source face restoration model.**



- **[CodeFormer](https://github.com/sczhou/CodeFormer)**  

  **Transformer-based face restoration** (NTU S-Lab License) for post-editing enhancement. **10,000+ GitHub stars.** **The most advanced open-source face restoration model.**



- **[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)**  

  **Practical super-resolution** (BSD-3-Clause) for upscaling edited images. **36,000+ GitHub stars.** **The standard open-source upscaling model.**



- **[Rembg](https://github.com/danielgatis/rembg)**  

  **Open-source background removal library** (MIT). **10,000+ GitHub stars.** Features multiple models (U2-Net, ISNet, SAM) for different use cases. **The most widely used open-source background removal tool.**



- **[Stable Diffusion WebUI (AUTOMATIC1111)](https://github.com/AUTOMATIC1111/stable-diffusion-webui)**  

  **Full UI for Stable Diffusion including inpainting** (AGPL-3.0). **150,000+ GitHub stars.** **The most widely used open-source image generation and editing interface.**



- **[ComfyUI](https://github.com/comfyanonymous/ComfyUI)**  

  **Node-based Stable Diffusion UI** (GPL-3.0) with inpainting workflows. **60,000+ GitHub stars.** **The most powerful open-source interface for chained image editing operations.**



- **[InvokeAI](https://github.com/invoke-ai/InvokeAI)**  

  **Professional Stable Diffusion toolkit** (Apache-2.0) with inpainting canvas. **25,000+ GitHub stars.** **The most polished open-source image generation interface.**



- **[U2-Net](https://github.com/xuebinqin/U-2-Net)**  

  **Salient object detection** (Apache-2.0) — foundation for background removal. **8,000+ GitHub stars.** The model behind many background removal tools.



- **[Segment Anything (SAM)](https://github.com/facebookresearch/segment-anything)**  

  **Meta's segmentation model** (Apache-2.0) for precise object selection. **50,000+ GitHub stars.** **The standard for interactive segmentation** —click once to select any object.



### Additional Strong Open-Source Options



- **[Migan](https://github.com/migan)** — MIGAN (Masked Image Generative Adversarial Network) for image inpainting (license varies). Transformer-based GAN for high-quality inpainting. Integrated into some open-source editors .

- **[pix2pix](https://github.com/phillipi/pix2pix)** — Image-to-image translation with conditional GANs (BSD-3-Clause). **8,000+ GitHub stars.** Early foundation for inpainting and object removal .

- **[DIP (Deep Image Prior)](https://github.com/DmitryUlyanov/deep-image-prior)** — Untrained neural network for image restoration (MIT). **6,000+ GitHub stars.** Uses network architecture as prior for inpainting without training data .

- **[Manga Inpainting](https://github.com/Sanster/IOPaint)** — Specialized model for manga and anime inpainting (Apache-2.0). Handles screentones, line art, and speech bubbles. Available as model option in IOPaint .

- **[ONNX Runtime](https://github.com/microsoft/onnxruntime)** — Cross-platform inference for optimized model deployment (MIT). Essential for edge deployment of image editing models.

- **[OpenCV](https://github.com/opencv/opencv)** — The most widely used computer vision library (Apache-2.0). **80,000+ GitHub stars.** Foundation for image processing pipelines.

- Community **n8n** workflows for batch image editing automation and asset pipeline integration.



**Frameworks for building custom systems**: Combine **IOPaint** for inpainting with **Rembg** for background removal, **Real-ESRGAN** for upscaling, **GFPGAN** or **CodeFormer** for face restoration, **Stable Diffusion WebUI** or **ComfyUI** for diffusion-based editing, and **PhotoCraft** for agent-driven workflows—creating a fully self-hosted, enterprise-grade image editing platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI image editing tools handling copyrighted material and personal likenesses must comply with copyright law, right of publicity, and data protection regulations. **AI-generated content may require disclosure** (EU AI Act Article 50, Adobe Content Credentials).

- **Open-source image editing is mature and production-ready.** IOPaint (20K+ stars) handles inpainting and object removal . Rembg (10K+ stars) handles background removal . Real-ESRGAN (36K+ stars) handles upscaling . **These are genuine alternatives to Clipdrop and Remove.bg.**

- **Model licensing varies significantly.** LaMa, IOPaint, Real-ESRGAN, and GFPGAN use permissive licenses (Apache-2.0/BSD). Stable Diffusion models carry CreativeML Open RAIL-M restrictions. **CodeFormer carries NTU S-Lab License with non-commercial restrictions.** **Check the LICENSE file before commercial deployment.**

- **Agent-driven editing is the emerging paradigm.** PhotoCraft and conversational editing represent a shift from "click tool, apply effect" to "describe outcome, agent orchestrates tools." **This is the new interaction model for creative software.**

- **Face restoration requires ethical consideration.** GFPGAN and CodeFormer can generate plausible facial detail that may not accurately reflect the original subject. **Never use face restoration to misrepresent identity in forensic, journalistic, or evidentiary contexts.**

- Self-hosted open-source solutions require proper GPU provisioning, model management, and ongoing maintenance. **Generated content may inadvertently reproduce training data—validate outputs for copyright compliance before commercial use.**



---



**Made for photographers, designers, and developers building transparent AI image editing solutions.**  

Let's make AI Image Editing more open, data-driven, and agent-driven.
