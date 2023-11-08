---
title: 'Sub-THz Ruler: Spectral Bistability in a 235GHz Self-Injection-Locked Oscillator for Agile and Unambiguous Ranging'

# Authors
# If you created a profile for a user (e.g., the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - SM Hossein Naghavi
  - admin
  - Amirata Tababavakili
  - Ali Mostajeran
  - Andreia Cathelin
  - Ehsan Afshari

# Author notes (optional)
author_notes:
#  - 'Equal contribution'


date: '2024-07-01'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ISSCC 2024-IEEE International Solid-State Circuits Conference (ISSCC)*
# publication_short: In *ESSCIRC*

abstract: Sub-THz/THz radars are paramount technologies in scientific and industrial metrology, offering high-precision and fast-acquisition target ranging. Among sub-THz/THz radars, the FMCW and pulse radars are well-studied approaches, where they use interferometry and time-of-flight techniques, respectively, to measure the target range. Also, both utilize the Doppler effect to calculate the target velocity by estimating the frequency shift of the TX signal (fd=(2Vr)⁄lambda, where fd is the Doppler frequency, Vr is the radial velocity, and lambda is the wavelength). However, the fundamental challenge of these radars is the ambiguities that arise in the simultaneous measurement of the range and velocity, represented in the ambiguity diagram, which significantly constrains the accuracy of range and velocity measurements. For applications that require a wide range of target velocities, sub-THz/THz radars need a bank of Doppler filters to cover the expected range of Doppler frequencies, enormously increasing the complexity of the radar hardware. Furthermore, the processing time required to resolve the ambiguities slows down the radar operation, limiting the radar capability in determining the range and velocity of agile targets. To overcome these challenges, we propose the idea of a sub-THz ruler sensor that uses self-injection locking (SIL) nonlinearity in a sub-THz oscillator to discretize the free space with lambda⁄2 steps. The sub-THz ruler sensor can promptly and unambiguously determine the target’s relative range and velocity by counting the number and measuring the time intervals of a series of sharp polarized pulses at the sensor’s output. The proposed sensor is also equipped with an FMCW radar to find the initial range (R0) of the target needed for absolute ranging (R=R0+nlambda⁄2). Using these approaches, this paper demonstrates a 235GHz ruler sensor with lambda⁄2=638μm range accuracy and the capability to measure velocities up to 638m/s and 840m/s for receding and approaching targets, respectively. Also, the backup FMCW radar for initial ranging has 16GHz bandwidth from 230-to-246GHz. Across state-of-the-art, this is the first demonstration of the SIL technique in the sub-THz band for agile and unambiguous ranging and velocimetry.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
