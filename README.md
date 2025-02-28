# Relion_5_install_in_WSL2_Ubuntu_24.04
## Parameters and their useful values

### Auto-picking
* I/O:
  Input micrographs- ../micrographs.star (imported all micrographs)
  Pixel size in micrographs- (Angstrom), ignored when CTF-corrected STAR is input
  Select one of the three methods- Use reference-based template matching / Laplacian-of-Gaussian / Topaz
    continue manually- in case of paused/halted run and continuing of splitted project segments
* Laplacian:
  Min. diameter for LoG filter (A) - smallest size of the particle (estimated)
  Max. diameter for LoG filter (A) - largest size of the particle
  Are the particles white - Yes/No
  Maximum res to consider (A) - 20 default
  Adjust default threshold (stddev) - # of stddev within which particles are picked. (-)neg number = lower threshold = more particles picked; (+)pos number = higher threshold = few particles picked
  
