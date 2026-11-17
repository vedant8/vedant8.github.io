---
title: "Research"
permalink: /docs/research/
# layout: single
layout: custom-default
author_profile: true
---
<style>
  .research-card {
    display: flex;
    gap: 2rem;
    flex-wrap: wrap;
    align-items: center;
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 14px;
    padding: 1.75rem;
    margin-bottom: 2.25rem;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.04);
    transition: transform 0.25s ease, box-shadow 0.25s ease;
  }
  .research-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.07);
  }
  .research-card.reverse {
    flex-direction: row-reverse;
  }
  .research-pill {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.38rem 0.85rem;
    border-radius: 999px;
    font-size: 0.84rem;
    font-weight: 600;
    text-decoration: none !important;
    background: #f0f7f7;
    color: #157878 !important;
    border: 1px solid #cfe3e3;
    transition: background 0.2s ease, color 0.2s ease;
  }
  .research-pill:hover {
    background: #157878;
    color: #ffffff !important;
  }
  .spectrum-zoom {
    transition: transform 0.35s ease;
  }
  .spectrum-zoom:hover {
    transform: scale(1.025);
  }
</style>


I work on large-scale data analysis and instrumentation development in high-energy astrophysics, with a focus on particle detection and signal processing. My recent collaborations include work on the [IceCube](https://icecube.wisc.edu/) Neutrino Observatory at the South Pole and the Compact Muon Solenoid (CMS) at CERN, Geneva. I am particularly interested in measurements of the astrophysical neutrino spectrum and what this tells us about cosmic ray accelerators from a multimessenger perspective.

<!-- - [ Astroparticle Physics with Cosmic Neutrinos](#astroparticle)
- [ Instrumentation Development for IceCube Upgrade](#instrumentation)
- [ Calibration of South Pole ice using embedded cameras](#ice-calibration)
 -->
 <!-- Quick Jump Navigation -->
<div style="display: flex; flex-wrap: wrap; gap: 0.6rem; margin-bottom: 2rem;">
  <a href="#astroparticle" class="research-pill"><i class="fas fa-atom"></i> Cosmic Neutrino Spectrum</a>
  <a href="#upgrade" class="research-pill"><i class="fas fa-camera"></i> IceCube Upgrade Calibration</a>
  <a href="#gen2" class="research-pill"><i class="fas fa-solar-panel"></i> IceCube-Gen2 &amp; Polar Operations</a>
</div>
---

## Astroparticle Physics with Cosmic Neutrinos

<div id="astroparticle" class="research-card" data-aos="fade-up">
  <div style="flex: 1 1 280px; min-width: 240px;">
    <img class="spectrum-zoom" src="{{ '/assets/images/EnergySpectrum.png' | relative_url }}" alt=" CosmicNeutrino Energy Spectrum" style="max-width: 100%; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
  </div>
    <p style="margin-top: 0;">
      Neutrinos are almost massless neutral particles that interact only weakly with matter, traveling through the Universe unimpeded by dust and undeflected by magnetic fields to point directly back to extreme cosmic-ray accelerators. The IceCube Neutrino Observatory instruments a cubic kilometer of deep glacial ice at the South Pole to detect the Cherenkov radiation produced by these rare interactions.
    </p>
    <p>
      My research focuses on isolating astrophysical neutrino signals in IceCube data and precision-mapping their energy spectrum and origins. Using advanced selection and modeling techniques, including machine learning methods and multidimensional likelihood estimation, my collaborators and I uncovered evidence that the cosmic neutrino spectrum deviates from a simple power law, revealing spectral curvature that constrains the radiation fields and physical environments of their sources.
    </p>    
  <div style="flex: 2 1 380px;">
    <div style="display: flex; align-items: flex-start; gap: 0.85rem; border-left: 4px solid #c59b27; background: #fbfaf5; border-top: 1px solid #efe9d5; border-right: 1px solid #efe9d5; border-bottom: 1px solid #efe9d5; padding: 0.85rem 1.1rem; border-radius: 0 8px 8px 0; margin-bottom: 1.25rem; font-size: 0.95rem; line-height: 1.55;">
      <!-- Miniature Gold Nobel Medallion SVG -->
      <img src="{{ '/assets/images/Nobel_Prize.png' | relative_url }}" alt="Nobel Prize Medal" style="width: 40px; height: 40px; object-fit: contain; flex-shrink: 0; margin-top: 2px;">
      <div>
        <span style="display: inline-block; font-weight: 700; letter-spacing: 0.04em; text-transform: uppercase; font-size: 0.78rem; color: #9a7414; margin-bottom: 0.2rem;">
          2026 Nobel Prize in Physics &bull; IceCube Collaboration
        </span><br>
        Building on the Nobel-recognized discovery of high-energy astrophysical neutrinos, led by IceCube Principal Investigator Francis Halzen, my work maps the fine spectral structure of this cosmic flux to uncover its hidden engines.
      </div>
    </div>
    <div style="display: flex; flex-wrap: wrap; gap: 0.5rem; margin-top: 1rem;">
      <a href="https://icecube.wisc.edu/" target="_blank" rel="noopener" class="research-pill"><i class="fas fa-external-link-alt"></i> IceCube Collaboration</a>
    </div>
  </div>
</div>
<!-- ## Astroparticle Physics with Cosmic Neutrinos

<div id="astroparticle" data-aos="fade-right" style="display: flex; gap: 2rem; flex-wrap: wrap; align-items: center; margin-bottom: 3rem;">
 <div style="flex: 1 1 300px; min-width: 250px;">
    <img src="/assets/images/EnergySpectrum.png" alt="Neutrino Energy Spectrum" style="max-width: 100%; border-radius: 12px;">
  </div>
  <div style="flex: 2 1 400px;">
    <p>
      Neutrinos are almost massless neutral particles, which interact only weakly with matter as they travel through. This makes them both ideal cosmic messengers, as they travel through the Universe unimpeded by intervening matter and undeflected by any electromagnetic fields. As such, once detected, they point back toward their sources, which are theorized to be cosmic ray accelerators, some of the most extreme environments in the Universe. The same characteristics which make the neutrino an ideal messenger make it very difficult to detect. In fact, as a weakly interacting particle, neutrino interactions are very rare, requiring a large flux and a large volume of detection medium to observe. When they do interact, however, we observe a shower of charged particles, which in a transparent medium manifest as Cherenkov radiation. The IceCube Neutrino Observatory uses the glacial ice at the South Pole as a Cherenkov medium to observe these neutrino events.
      My research focuses on identifying astrophysical neutrino signals in IceCube data and constraining the energy spectrum and possible sources. I use machine learning and maximum likelihood estimation techniques to study event directions, energies, and flavors. My collaborators and I found evidence that the spectrum of cosmic neutrinos arriving at Earth has structure beyond a simple power law, an exciting result with numerous implications for the sources of astrophysical neutrinos.
    </p>
  </div>

</div> -->
---

## Instrumentation Development
<div id="instrumentation" data-aos="fade-left" style="margin-bottom: 2rem;">
  <div style="flex: 1 1 300px; min-width: 250px;">
    <img src="/assets/images/LOM_development.png" alt="LOM Deployment in Antarctica" style="max-width: 100%; border-radius: 12px;">
  </div>

  <div style="flex: 2 1 400px;">
  <p>
    I have been a lead member of a team developing new optical detector prototypes for IceCube-Gen2, a high-energy expansion to the current IceCube detector, aiming to boost sensitivity to PeV-scale neutrinos, along with a great enhancement to the neutrino source detection sensitivity. I have contributed to modelling, design, testing, and firmware development for the Long Optical Module (LOM), a candidate for IceCube-Gen2. Twelve prototypes were deployed during the upcoming 2025-26 IceCube Upgrade deployment season in a successful field test. We plan to develop these into 
  </p>
 </div>
</div>
---

## South Pole Ice Imaging and Calibration
<div id="ice-calibration" data-aos="fade-up" style="margin-bottom: 2rem;">
  <div style="flex: 1 1 280px; min-width: 240px;">
    <img class="spectrum-zoom" src="{{ '/assets/images/mDOM_descent.jpeg' | relative_url }}" alt="Module Deployment in Antarctica" style="max-width: 100%; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
  </div>
  <div style="flex: 2 1 400px;">
  <p>
    One of the major science goals of the <a href="https://icecube.wisc.edu/news/press-releases/2026/02/the-icecube-neutrino-observatory-gets-a-major-upgrade-beneath-the-ice/" target="_blank" rel="noopener">IceCube Upgrade</a>, a recent expansion of the current IceCube detector to study GeV-scale neutrino oscillation measurements
    I am currently focusing on the development of firmware for the Gen2-DOM, an expansion of the current IceCube detector to both improve sensitivity to PeV, and to better characterize the optical properties of the ice at the South Pole. I am leading the campaign to perform the optical calibration and modelling of South Pole ice using cameras incorporated into the ice. This involves firmware development tasks, optical bench testing, and the commissioning of a 3D laser scanning system to analyze instrument response.
  </p>
  <div style="display: flex; flex-wrap: wrap; gap: 0.5rem; margin-top: 1rem;">
      <a href="https://icecube.wisc.edu/news/press-releases/2026/02/the-icecube-neutrino-observatory-gets-a-major-upgrade-beneath-the-ice/" target="_blank" rel="noopener" class="research-pill"><i class="fas fa-newspaper"></i> IceCube Upgrade Press Release (Feb 2026)</a>
    </div>
</div>

## IceCube Upgrade Camera Calibration & Geometry

<div id="upgrade" class="research-card reverse" data-aos="fade-up">
  <div style="flex: 1 1 280px; min-width: 240px;">
    <img class="spectrum-zoom" src="{{ '/assets/images/UpgradeCamera.png' | relative_url }}" alt="IceCube Upgrade Camera Calibration" style="max-width: 100%; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
  </div>
  <div style="flex: 2 1 380px;">
    <p style="margin-top: 0;">
      Precision neutrino oscillation and low-energy reconstruction depend on knowing the exact positions, orientations, and optical properties of every sensor frozen deep into the South Pole ice. Following the deployment of the <a href="https://icecube.wisc.edu/news/press-releases/2026/02/the-icecube-neutrino-observatory-gets-a-major-upgrade-beneath-the-ice/" target="_blank" rel="noopener">IceCube Upgrade</a>, I led the image-based geometry calibration across 409 camera-equipped optical modules.
    </p>
    <p>
      By triangulating inter-string LED flashers and hole-ice refreeze features across multi-camera images, this pipeline independently constrains horizontal module coordinates, decouples vertical string-depth offsets from individual module tilts, and characterizes local ice scattering in the drill column.
    </p>
    <div style="display: flex; flex-wrap: wrap; gap: 0.5rem; margin-top: 1rem;">
      <a href="https://icecube.wisc.edu/news/press-releases/2026/02/the-icecube-neutrino-observatory-gets-a-major-upgrade-beneath-the-ice/" target="_blank" rel="noopener" class="research-pill"><i class="fas fa-newspaper"></i> IceCube Upgrade Press Release (Feb 2026)</a>
    </div>
  </div>
</div>

---
<div data-aos="zoom-in" style="background-color: #eee; padding: 2rem; border-radius: 10px;">
  <h3> This should zoom in when you scroll!</h3>
  <p>If this doesn't animate, AOS isn't loading. We'll fix it.</p>
</div>