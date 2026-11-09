<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.png">
  <img src="assets/header-light.png" alt="Sarthak Verma. Multi-agent LLM systems, model routing and open-weight inference. Shipped in software, materials science and AR.">
</picture>

<p align="center"><samp>
<a href="https://www.linkedin.com/in/sarthak-verma-56b7061b9">linkedin</a> &nbsp;|&nbsp;
<a href="https://x.com/SarthakVeri1g2">x</a> &nbsp;|&nbsp;
<a href="https://devpost.com/vsarthak05">devpost</a> &nbsp;|&nbsp;
<a href="https://doi.org/10.1038/s42004-025-01800-y">paper</a>
</samp></p>

I build multi-agent LLM systems and the layer underneath them: orchestration, model routing, tool calling and inference on open-weight models. My main project, Stepswitch, sends each step of a coding task to the model that suits it, from small local models to large open-weight and hosted ones, and keeps a change only if your tests pass.

I don't stay in one field. So far I've built for software, materials science and augmented reality, and each project checks its output against something real: your tests, measured data, or the geometry of diffraction.

## Projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/sarthak-1111/stepswitch"><img src="assets/stepswitch.png" alt="A finished Stepswitch run in the terminal: each step names the model that ran it, and the tests pass"></a>
<p><b><a href="https://github.com/sarthak-1111/stepswitch">Stepswitch</a></b><br>
A multi-agent orchestrator for coding. Each step of a task goes to the model and harness that suit it, across local open-weight models and hosted APIs. Changes must pass your tests, and every claim in the README re-runs with <code>ssw prove</code>.</p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/sarthak-1111/concord"><img src="assets/concord.jpg" alt="Concord: plain x, y data in, a structural model out"></a>
<p><b><a href="https://github.com/sarthak-1111/concord">Concord</a></b><br>
Multi-agent analysis for materials science. AI agents read XRD, PDF and XAFS data from one sample and cross-check each other into one structural model. Tested on published measured data, not only simulations.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/sarthak-1111/braggs-room"><img src="assets/braggs-room.jpg" alt="Bragg's Room: a diffraction spot lit on the wall at its true angle"></a>
</td>
<td width="50%" valign="top">
<p><b><a href="https://github.com/sarthak-1111/braggs-room">Bragg's Room</a></b><br>
<sub>Built for Learn AR with SPECS</sub></p>
<p>X-ray diffraction at room scale. Turn a crystal on your desk and watch diffraction spots light up on your wall at their true angles, then work out whether a mystery crystal is simple cubic or face-centred cubic from which spots appear.</p>
<p><a href="https://youtu.be/9aPGQw05psg">Watch the video</a></p>
</td>
</tr>
</table>

## Publication

**Machine Learning-Guided Multimodal Synchrotron Analysis Workflow for Fuel Cell Electrocatalyst Discovery**<br>
*Communications Chemistry*, 2025

<a href="https://doi.org/10.1038/s42004-025-01800-y"><img alt="Paper DOI 10.1038/s42004-025-01800-y" src="https://img.shields.io/badge/DOI-10.1038%2Fs42004--025--01800--y-0f766e"></a>
<a href="https://doi.org/10.5281/zenodo.17538068"><img alt="Data and code on Zenodo, DOI 10.5281/zenodo.17538068" src="https://zenodo.org/badge/DOI/10.5281/zenodo.17538068.svg"></a>

From my day job as a research scientist in Japan: eight synchrotron measurements of 46 platinum catalysts combined into one model that predicts catalyst activity. I co-led the modelling.
