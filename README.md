# PXIe-7902 Getting Started

Modification of the `PXIe-791X Getting Started` from the NI LabVIEW Example Finder to be focused on the PXIe-7902.

## Why Modify the Example

The example project provided by National Instruments (NI\Emerson) is suited to the PXIe-791x family of FPGA co-processors.  A previous generation of co-processor, the PXIe-7902 could benefit from a similar example.  The original source code was used as inspiration to create a version of the same Gettin Started example.

### Key Differences between the PXIe-791x and the PXIe-7902

| Category                  | PXIe-791x           | PXIe-7902          |
| ------------------------- | ------------------- | ------------------ |
| DRAM                      | 4GB (2 Banks x 2GB) | 2GB (1 Bank x 2GB) |
| DRAM Max Data Width       | 256                 | 512                |
| Top-level clock (default) | 80 MHz              | 40 MHz             |
| PXIe_Clk100               | Present             | Not Present        |

### Original Project Location

#### PXIe-791X Getting Started.lvproj

C:\Program Files\NI\LVAddons\flexrioii\1\examples\FlexRIO\Coprocessor Modules

## Repo Layout

| Folder               | Purpose                                                           |
| :------------------- | ----------------------------------------------------------------- |
| [archive](/archive/) | Files for reference that should remain unchanged                  |
| [docs](/docs/)       | Documents and other files for background information              |
| [src](/src)          | The LabVIEW project used in this repo, in version LabVIEW 2024Q3. |
| [rsrc](/rsrc)        | Images and other files required to render markdown in this repo.  |

## How to Use this Repository

The default branch of this repo is `main` with the Thetic actively developing in `dev`. 

## About Thetic Engineering Ltd

Thetic Engineering Ltd. is a UK automated test consultancy that specializes in the validation, characterization, and production test of semiconductors and other materials.  Industry experience is used to produce highly targeted training courses for test engineers aimed at deep learning and effective, practical skills.

### Contact

Email: <hello@thetic.co>  
Website: <https://thetic.co>  
![thetic's logo](/rsrc/thetic_logo_web_xsmall.png)  

## Disclaimer

This sample code is provided by Thetic Engineering Ltd. "as-is" without warranty or guarantee of operation.  Original reference material from NI\Emerson follows their licenses.
