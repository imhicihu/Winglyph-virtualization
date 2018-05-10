# Rationale #

Virtualization of Winglyph ([deprecated](https://en.wikipedia.org/wiki/Deprecation)) on recent operating systems, mainly Windows OS's.
In behalf of trueness, firstly the virtualization was done on a Macbook. 
Then, it was ported to the Windows ecosystem.

## What is this repository for? ##

* Virtualization of Winglyph on recent operating systems
* 1.1

## Requirements: ##

### Operating systems: ###
* Windows 98 16 bits-32 bits
* Windows 98 Second Edition 16/32 bits
* Windows XP 32/64 bits
* Windows Vista 32/64 bits
* Windows 7 32/64 bits
* Windows 8 64 bits (Professional, Enterprise version)
* Windows 8.1 64 bits (Professional, Enterprise version)
* Windows 10 64 bits (Education, Professional, Enterprise version)

###Software [dependencies](http://www.ibm.com/support/knowledgecenter/SS2GNX_5.1.1/com.ibm.tivoli.tpm.sft.doc/software/csfm_reqcap.html):###
* [SecurAble](https://www.grc.com/securable.htm)
* [Hardware-assisted virtualization detection tool](https://www.microsoft.com/en-us/download/details.aspx?id=592)
* [Intel® Processor Identification Utility](https://downloadcenter.intel.com/download/7838)
* [AMD Virtualization™ Technology and Microsoft® Hyper-V™ System Compatibility Check Utility](http://download.amd.com/techdownloads/AMD-VwithRVI_Hyper-V_CompatibilityUtility.zip)
* [Windows XP Mode](https://www.microsoft.com/es-ar/download/details.aspx?id=8002)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [VirtualBox VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads)
* Winglyph
* [Rufus](https://rufus.akeo.ie/#ref2)


### Legal ###

* All trademarks are the property of their respective owners.
### Procedures - checklist ###
* Install [SecurAble](https://www.grc.com/securable.htm). Run it. Verify that your processor provides virtualization functions. 
* Install [Hardware-assisted virtualization detection tool](https://www.microsoft.com/en-us/download/details.aspx?id=592). Verify that your operating system meets the mandatory [needed](https://bitbucket.org/imhicihu/virtualization-winglyph/issues/13/software-workflow-hardware-assisted). Run it. Test that your processor provides virtualization features. 
* Plus, install this utilities to analyze the *architecture / possibilities* of virtualization: 
    - for [Intel](https://downloadcenter.intel.com/download/7838) processors 
    - for [AMD](http://download.amd.com/techdownloads/AMD-V_Hyper-V_Compatibility_Check_Utility.zip) processors, .
* Once verified that your processor provides virtualization features: 
    - If `Yes`, go on. 
    - If `No`, your pc / notebook hardware is *too* old for virtualization modes.
* Enable on BIOS system the virtualization feature (on Intel it's called *HyperV* and in AMD processors: *AMD-V*); at boot time, press [usually](https://www.lifewire.com/bios-setup-utility-access-keys-for-popular-motherboards-2624462) `Del` or `F2` to access the [BIOS](http://www.pcworld.com/article/241032/how_to_enter_your_pcs_bios.html). `F10` saves this changes.
![screen_capture.png](https://bitbucket.org/repo/ekyaeEE/images/4279029375-screen_capture.png)
![blue-screen.png](https://bitbucket.org/repo/ekyaeEE/images/3041964421-blue-screen.png)
![virtualization.png](https://bitbucket.org/repo/ekyaeEE/images/1477597896-virtualization.png)
![enable-vt-x-in-bios-2.png](https://bitbucket.org/repo/ekyaeEE/images/2769097956-enable-vt-x-in-bios-2.png)
* Install [Rufus](https://rufus.akeo.ie/#ref2) in case of a mandatory installation of a bootable operating system in a USB disk drive.
* Install a printer driver, even a [virtual](https://en.wikipedia.org/wiki/List_of_virtual_printer_software) one (ie: PDF Writer). This is to avoid further and subsequent error messages.
* Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads). Plus, install the VirtualBox 5.1.18 Oracle VM [VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads).
* If your operating system is Windows 7, run VirtualBox. Create a [virtual machine](https://bitbucket.org/imhicihu/winglyph-virtualization/issues/24/workflow-software-creation-and). Then install Winglyph.
* If your operating system is Windows 8, verify that [your version is compatible](https://bitbucket.org/imhicihu/winglyph-virtualization/issues/22/software-workflow-operating-systems) with Hyper-V. If `Yes`, enable Hyper-V. Then [create a virtual machine](https://bitbucket.org/imhicihu/virtualization-winglyph/issues/23/workflow-creation-of-a-virtual-machine). Inside of it, install [Windows XP](https://bitbucket.org/imhicihu/virtualization-winglyph/issues/6/workflow-deprecated-windows-xp-testing). Then install Winglyph.
* If your operating system is Windows 8.1, verify that [your version is compatible](https://bitbucket.org/imhicihu/winglyph-virtualization/issues/22/software-workflow-operating-systems) with Hyper-V. If `Yes`, enable Hyper-V. Then [create a virtual machine](https://bitbucket.org/imhicihu/virtualization-winglyph/issues/23/workflow-creation-of-a-virtual-machine). Inside of it, install [Windows XP](https://bitbucket.org/imhicihu/virtualization-winglyph/issues/6/workflow-deprecated-windows-xp-testing). Then install Winglyph.
* If your operating system is Windows 10, verify that [your version is compatible](https://bitbucket.org/imhicihu/winglyph-virtualization/issues/22/software-workflow-operating-systems) with Hyper-V. If `Yes`, enable Hyper-V. Then [create a virtual machine](https://bitbucket.org/imhicihu/virtualization-winglyph/issues/23/workflow-creation-of-a-virtual-machine). Inside of it, install [Windows XP](https://bitbucket.org/imhicihu/virtualization-winglyph/issues/6/workflow-deprecated-windows-xp-testing). Then install Winglyph.
![windows10-virtualized.png](https://bitbucket.org/repo/ekyaeEE/images/1502602213-windows10-virtualized.png)