# DP4+ App - User Guides

The **DP4+ Application** provides various modes of operation to facilitate NMR calculations and geometry optimizations. User interface (UI) is divided into different **tabs**, each corresponding to a specific mode. Below is an overview of each functionality:

# Available Modes

## 0. DP4+
This mode offers **three different methods** for handling NMR calculations and geometry optimizations. It is designed for B3LYP/6-31+G geometry optimizations and NMR calculations at **24 levels**.

- **Single NMR Calculation**: Utilizes a single file to extract tensors and conformer energies.
- **NMR + Gibbs Free Energy**: Uses NMR calculations for tensors and frequency calculations for Gibbs free energies.
- **NMR + Single Point Energy**: Uses NMR calculations for tensors and single-point calculations for conformer energies.

## 1. MM-DP4+
This mode has **one method**. It is designed for molecular mechanics (MM) geometry optimizations using **MMFF** and NMR calculations at **36 levels**. 

## 2. HALO DP4+ (extension)
This mode is an extension that automatically detects the presence of chlorine and bromine atoms in molecules. Its use allows for a multi-standard reference method, meaning that for atoms neighboring halogens, a specific reference standard (not TMS) is used. This improves the certainty of the prediction.

## 3. Custom DP4+
This mode allows the user to create a **custom DP4+ level** based on their specific requirements. The user can configure the settings for NMR and geometry optimizations according to their needs.

## User Manuals and Examples

Each mode described above has its own dedicated user manual and example cases. You can find these resources in the corresponding folders within this repository.

These documents will guide you through the setup, examples, and step-by-step instructions for utilizing each mode.

