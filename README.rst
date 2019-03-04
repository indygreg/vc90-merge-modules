This repository contains the Visual C++ 9.0 (Visual Studio 2008)
Merge Modules.

The merge modules are typically only installed as part of
Visual Studio itself: the redistributable packages don't
install the merge modules.

In order to obtain these modules, the following was done:

1. Install Visual Studio 2008 SP1
   (https://www.microsoft.com/en-us/download/details.aspx?id=10986)
2. Install Visual C++ 2008 Service Pack 1 MFC Security Update
   (https://www.microsoft.com/en-us/download/details.aspx?id=26360)

The MFC Security Update provides version 9.0.30729.6161 of the
files. More information about this update is available at
https://support.microsoft.com/gl-es/help/2538241/ms11-025-description-of-the-security-update-for-visual-studio-2008-sp1.

The files in this repository are copied from
``%CommonProgramFiles%\Merge Modules`` without modification.
