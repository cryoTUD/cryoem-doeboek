# CryoEM Playbook

This is a collection of iInteractive notebooks for the **High Resolution Imaging** course at TU Delft. They introduce core concepts of cryo-EM image processing through hands-on examples and working through exercises and questions along the way.

**No installation needed.** Each notebook runs entirely in your browser via [JupyterLite](https://jupyterlite.readthedocs.io/) and is embedded directly in its page. Click **Run All** (⏭) in the toolbar to start the kernel and run the code. The first start can take a moment while Python loads. Then explore the results with the sliders and dropdowns.

---

## Notebooks

!!! info "What are the different notebooks?"

    The notebooks build on each other. We recommend working through them in this order, as the Fourier concepts from the first notebook return in the others. The last two notebooks are still under construction and will be added soon.

    - **[Fourier analysis](fourier.md)** introduces the mathematical toolbox of the course. You explore waves, Fourier series and the 1D and 2D Fourier transform, use the convolution theorem for image filtering, and finish with the contrast transfer function (CTF) and how to correct for it.
    - **[Single-particle analysis](spa.md)** *(under construction)* shows how a structure is recovered from many noisy projectin images of identical particles seen in different orientations. Using a simplified 2D model, you simulate particle images, align them to a reference, reconstruct, refine and classify them.
    - **[Tomography](tomo.md)** *(under construction)* shows how a 3D volume is reconstructed from a tilt series of projections. You build a sinogram, compare backprojection with filtered backprojection, and see how the Fourier slice theorem, the missing wedge and the Crowther criterion limit the resolution.

---

*CryoEM Playbook is an open educational resource. The content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) and the code under the BSD 3-Clause license. See [About](about.md#open-educational-resource-and-licensing) for details and how to attribute.*
