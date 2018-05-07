////////////////////////////////////////////////////////////////////////
SIM52xx USB Serial Host Client Driver for Windows CE6.x.
////////////////////////////////////////////////////////////////////////
=============================================================
Setup:
============================================================= 
1. Add husbcom_sim52xx.reg to platform.reg, modify the registery settings if necessary.
2. Add husbcom_sim52xx.bib to platform.bib.
3. Copy .\target\%_TGTCPU%\%WINCEDEBUG%\husbcom_sim52xx.* to your BSP\Files directory.
4. Build your os.

=============================================================
Notes:
=============================================================
If you want to get sim5216 driver for example,just change all items contain sim52xx to sim5216.
Support CPU type: ARMV4I MIPSII x86
////////////////////////////////////////////////////////////////////////
