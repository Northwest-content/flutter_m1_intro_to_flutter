# Flutter installation macOS



1. Open https://flutter.dev/docs/get-started/install



2. Choose **macOS**

<img src="https://lh6.googleusercontent.com/4JKAn2qqi-tspNzl-Wvz0dGxeH7PX9U_68-_fFMBgWta2OmOI9gAqyM9gfFuMx6Ab_V-sAC_cPQemp5XDbWkHVs3BY6QLUn7EmYe3SrZA-aIbz0v2QG54jsc6c8g_jn_CmGET4XQ" alt="img" width="500" />





3. Download the following installation bundle 

<img src="https://lh3.googleusercontent.com/AVcOs5tWRDvNYsa6-gu2cVq7NKsNKd62UFElAfppmGeXsu95y5NrRoHFxIRNfrhtXyDnR8-3Zz48JrxcNFfGMFghSMNVN74Ppf17SgFPZyTss6_rRlHF2LmEbcfVEx1_1qckxRSp" alt="img" width="300" />





4. Extract the file

5. Move **flutter** folder to **Documents** folder

6. Hold the **option** key, then press **right click**, then choose **Copy “flutter” as Pathname**

7. Then, make sure that **bash** shell is the default one.   

8. Open **System Preferences**   

9. Open **Users & Groups**

   <img src="https://lh4.googleusercontent.com/waEM9qtZI_wU0CtJWZN03DHJlGMpWEJRnn5eYocuUAnDJIkT_qP0pYzUPcL-sEpqZlmjswPib1g7GffqGBNemwfwgOwyip0SAQbj7_HBKwBZ1s6rGhPHO8P1qlLP018IU_k80dG4" alt="img" width="300" />

10. Click the lock icon down, then type the password of your device.

11. After you unlock it, press right click Advanced Options

    <img src="https://lh3.googleusercontent.com/qyHOJGyleXlHsdNs0P6sMdxTaZVZB969mXYV6A5BRh1xb75wec42MWxyJ-4KNejE9-hbD759SAsYtQvGCruD80VOwJThx-8XOhWBZ4VbSKBDBBedhvqEfSiTpFz_ukPHPjTJXV5z" alt="img" width="300" />

12. Then make sure you choose **/bin/bash** in **Login shell**

    <img src="https://lh4.googleusercontent.com/eDdkjMAyDmIXNI-U-LL1ZDRIDbTqnCh65y5hBR3FyB_iOWYgMrXc44jT-BDYAE5lJwPcjX43rk1q1D5EQslkAH-wSuTR7fmFaZaQyCm-kx_2wfDz7anA76oap32VtMklW1SCWlA-" alt="img" width="300" />

13. After that open **Terminal** 

<img src="https://lh3.googleusercontent.com/cynJO7JvqQUxTNSJUr2zCF_QLvUS-FPUYqDxJ2rNLbhcERS9wFhf0EPZKzpa9Duwr_4Vay1bMTVKrajNgmkn3Ewvuo8DhiN2SycStPYa_nWS-rVHCNZFDeJ056JgsGk_0Gu7jyp_" alt="img" width="300" />

14. Run, 

```shell
open .bash_profile
```

**Note:** If the **bash_profile** does not open, run on **Terminal**

```shell
touch ~/.bash_profile; open ~/.bash_profile
```

15. Write the path that you copied for the **flutter** folder Inside the **bash_profile**

```
export PATH="$PATH:[your path]/bin"
```

Add the **flutter** folder path inside **[your path]**

The final example will be the same as this example but with your **flutter path folder**.

<img src="https://lh5.googleusercontent.com/drK-jBdJH71dFTcmOgWUzECjmyoTJeBju2mTAWgycHmUl6SzZIpK8S08xDeEUcueq1IEEIfsI2RW_PBnRW8vZWzwRDZugFXD9RDPlxBgCjQwftBNUhOePpqP-7aEQ78ajTEdQgd2" alt="img" width="300" />





16. Save **.bash_profile**, Then quit the **Terminal**, and reopen it again.



17. Run, 

```shell
flutter --version
```

Make sure that you will see the **flutter version**, same as this example but maybe with a different version - NP :)

<img src="https://lh3.googleusercontent.com/k-hu3OPmsvizSChjQJoj_HCsKRR4DazJsB9cMewyzEnZvR2rFNoyAv0fv0asEVCwHwvpw9JwgdledNYxQrIaKU_TWlZizFSmKhvg527SPuDYx2965WZi1OxRpaWzZLteRNFc-wYT" alt="img" width="500" />

​    

​    

​    

​    

​    

​    

​    

​    
