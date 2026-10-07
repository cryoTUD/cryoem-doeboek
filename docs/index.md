# CryoEM Playbook

Interactive practicals for the **High Resolution Imaging** course.

Each practical runs entirely in your browser via [JupyterLite](https://jupyterlite.readthedocs.io/) — no installation needed. Interactive code cells are embedded directly in each page. Click **Run All** (▶▶) in the toolbar of any embedded cell to start the kernel and execute the code.

---

## Practicals

!!! info "What are the different practicals?"

    The three practicals build on each other. We recommend working through them in this order, as the Fourier concepts from the first practical return in the other two.

    - **[Fourier analysis](fourier.md)** introduces the mathematical toolbox of the course. You explore waves, Fourier series and the 1D and 2D Fourier transform, use the convolution theorem for image filtering, and finish with the contrast transfer function (CTF) and how to correct for it.
    - **[Single-particle analysis](spa.md)** shows how a structure is recovered from many noisy projectin images of identical particles seen in different orientations. Using a simplified 2D model, you simulate particle images, align them to a reference, reconstruct, refine and classify them.
    - **[Tomography](tomo.md)** shows how a 3D volume is reconstructed from a tilt series of projections. You build a sinogram, compare backprojection with filtered backprojection, and see how the Fourier slice theorem, the missing wedge and the Crowther criterion limit the resolution.

---

> **Tip:** Each practical contains interactive widgets. Run the setup cell first, then explore the sliders and dropdowns.

---

*CryoEM Playbook is an open educational resource. The content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) and the code under the BSD 3-Clause license. See [About](about.md#open-educational-resource-and-licensing) for details and how to attribute.*
