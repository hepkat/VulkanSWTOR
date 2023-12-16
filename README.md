# VulkanSWTOR
Just a tutorial to setup Vulkan in SWTOR.

Game seems to run better under a Vulkan translation for DX than DirectX 9 itself.
https://github.com/doitsujin/dxvk
GitHub
GitHub - doitsujin/dxvk: Vulkan-based implementation of D3D9, D3D10...
Vulkan-based implementation of D3D9, D3D10 and D3D11 for Linux / Wine - GitHub - doitsujin/dxvk: Vulkan-based implementation of D3D9, D3D10 and D3D11 for Linux / Wine
GitHub - doitsujin/dxvk: Vulkan-based implementation of D3D9, D3D10...
Download from here:
https://github.com/doitsujin/dxvk/releases
GitHub
Releases · doitsujin/dxvk
Vulkan-based implementation of D3D9, D3D10 and D3D11 for Linux / Wine - doitsujin/dxvk
Releases · doitsujin/dxvk
Image
Image
Download this one:
Image
If you need something to extract a Tarball (tar.gz) you can use 7-zip
https://www.7-zip.org/a/7z2301-x64.msi
that's the direct link to install 7zip from this download page:
https://www.7-zip.org/download.html
Open the dxvk-2.3.tar.gz file you downloaded (it should open with 7zip) or you can tell it to open with 7zip.
Image
double click the dxvk-2.3.tar
Image
now open the folder
Image
open the x64 folder
Image
should look like this now
Image
Darth Bu'ru — 12/10/2023 8:35 PM
Open another explorer window (Folder icon) and go to C:\Program Files (x86)\Steam\steamapps\common\Star Wars - The Old Republic\swtor\retailclient
Or wherever it's installed if not the steam version
Image
basically just get to the Star Wars - The Old Republic\swtor\retailclient directory
drag and drop the d3d9.dll in the Z-zip window to this folder 
Image
Close and relaunch the game if you already have it open. But now the game should launch in Vulkan and run quite a bit better.
