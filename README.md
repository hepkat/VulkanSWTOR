# VulkanSWTOR
Just a tutorial to setup Vulkan in SWTOR.

Basic Info link - SWTOR seems to run better under a Vulkan translation for DX than DirectX 9 itself.
https://github.com/doitsujin/dxvk
Vulkan-based implementation of D3D9, D3D10 and D3D11 for Linux / Wine - GitHub - doitsujin/dxvk: Vulkan-based implementation of D3D9, D3D10 and D3D11 for Linux / Wine

Download from here:
https://github.com/doitsujin/dxvk/releases

![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/2fe7e537-8a89-4f0c-903c-24b2b17657da)

![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/c34fd2d6-d110-4cf3-8f07-e77039b42684)

Download this one:
![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/17e4c15e-4f12-4932-b973-0553f8968f35)

If you need something to extract a Tarball (tar.gz) you can use 7-zip
https://www.7-zip.org/a/7z2301-x64.msi

that's the direct link to install 7zip from this download page:
https://www.7-zip.org/download.html


Open the dxvk-2.3.tar.gz file you downloaded (it should open with 7zip) or you can tell it to open with 7zip.
![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/76e81412-b566-4d8e-bbb9-5d3973a18b5c)

double click the dxvk-2.3.tar
![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/f57a86a4-7386-4399-a09d-177260b34364)

now open the folder
![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/d6f54bc2-fc06-4823-9ae4-327511473f04)

open the x64 folder
![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/094e427a-661a-4576-b1b5-6c6dccaf0757)

should look like this now
![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/e0e45ecc-3349-4f10-a4e7-b073e10ceeb2)

Open another explorer window (Folder icon) and go to `C:\Program Files (x86)\Steam\steamapps\common\Star Wars - The Old Republic\swtor\retailclient`
Or wherever it's installed if not the steam version
![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/3354bb72-5d3d-4f43-ba34-28ba72eac27e)


basically just get to the `Star Wars - The Old Republic\swtor\retailclient` directory
drag and drop the d3d9.dll in the Z-zip window to this folder 
![image](https://github.com/hepkat/VulkanSWTOR/assets/25138984/55a1344d-a707-4ddc-bbde-da15454bf59c)

Close and relaunch the game if you already have it open. But now the game should launch in Vulkan and run quite a bit better.
