# Src

The primary source code for this repo.

## Software Environment

### Installed via NI Package Manager

- LabVIEW 2024 Q3
- LabVIEW 2024 Q3 FPGA Module
- Vivado Tools 2021.1
- LV IDL for High Speed 2026 Q2

### Installed via VIPM

- QuickDrop AlignElements by MNProjects
- Top Level Launcher by Gcentral
- Free Label To VI Description
- PaneRelief by Hope Harrison

## Host Files

| VI                               | Notes                                                                                                             | Source            |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ----------------- |
| Basic DMA.vi                     | Largely unchanged from source.                                                                                    | NI Example Finder |
| P2P High-Speed Stream to Disk.vi | Largely unchanged from source.                                                                                    | NI Example Finder |
| Basic DMA feat Freq Shift.vi     | Modified to point to a PXIe-7902 bitfile compiled from `PXIe-7902 Getting Started feat Frequency Shift (FPGA).vi` | Thetic            |

## FPGA Files

| VI                                                       | Notes                                                                                  | Source            |
| -------------------------------------------------------- | -------------------------------------------------------------------------------------- | ----------------- |
| PXIe-791X Getting Started.vi                             | Largely unchanged from source.                                                         | NI Example Finder |
| PXIe-7902 Getting Started.vi                             | The above VI modified to account for different DRAM Bank and size                      | Thetic            |
| PXIe-7902 Getting Started feat Frequency Shift (FPGA).vi | The above VI modified to have a frequency shift DSP as an example of inline processing | Thetic            |
