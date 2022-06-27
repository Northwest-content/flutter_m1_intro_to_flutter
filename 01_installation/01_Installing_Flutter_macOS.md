1. Open https://flutter.dev/docs/get-started/install.

2. Choose **macOS**.

![screenshot](https://lh6.googleusercontent.com/4JKAn2qqi-tspNzl-Wvz0dGxeH7PX9U_68-_fFMBgWta2OmOI9gAqyM9gfFuMx6Ab_V-sAC_cPQemp5XDbWkHVs3BY6QLUn7EmYe3SrZA-aIbz0v2QG54jsc6c8g_jn_CmGET4XQ)

3. Download the following installation bundle.

![screenshot](https://lh3.googleusercontent.com/AVcOs5tWRDvNYsa6-gu2cVq7NKsNKd62UFElAfppmGeXsu95y5NrRoHFxIRNfrhtXyDnR8-3Zz48JrxcNFfGMFghSMNVN74Ppf17SgFPZyTss6_rRlHF2LmEbcfVEx1_1qckxRSp)

4. Extract the zip file.

5. Move the **flutter** folder to the **Documents** folder.

6. Right-click on the flutter folder, hold the **option** key, then choose **Copy “flutter” as Pathname**.
<!-- the default shell doesn't have to be bash, they can set it up with z as well => code .zshrc and they paste the path -->
7. Open **System Preferences** >> **Users & Groups** to check if **bash** is the default shell.

![screenshot](https://lh4.googleusercontent.com/waEM9qtZI_wU0CtJWZN03DHJlGMpWEJRnn5eYocuUAnDJIkT_qP0pYzUPcL-sEpqZlmjswPib1g7GffqGBNemwfwgOwyip0SAQbj7_HBKwBZ1s6rGhPHO8P1qlLP018IU_k80dG4)

8. Click the lock icon button, and type the password of your device to unlock the key.

9. Right-click on the user admin, then click **Advanced Options**.

![screenshot](https://lh3.googleusercontent.com/qyHOJGyleXlHsdNs0P6sMdxTaZVZB969mXYV6A5BRh1xb75wec42MWxyJ-4KNejE9-hbD759SAsYtQvGCruD80VOwJThx-8XOhWBZ4VbSKBDBBedhvqEfSiTpFz_ukPHPjTJXV5z)

10. Choose **/bin/bash** for **Login shell**

![screenshot](https://lh4.googleusercontent.com/eDdkjMAyDmIXNI-U-LL1ZDRIDbTqnCh65y5hBR3FyB_iOWYgMrXc44jT-BDYAE5lJwPcjX43rk1q1D5EQslkAH-wSuTR7fmFaZaQyCm-kx_2wfDz7anA76oap32VtMklW1SCWlA-)

11. Open **Terminal**.

![screenshot](https://lh3.googleusercontent.com/cynJO7JvqQUxTNSJUr2zCF_QLvUS-FPUYqDxJ2rNLbhcERS9wFhf0EPZKzpa9Duwr_4Vay1bMTVKrajNgmkn3Ewvuo8DhiN2SycStPYa_nWS-rVHCNZFDeJ056JgsGk_0Gu7jyp_)

12. Run the following command:

    ```shell
    open .bash_profile
    ```

    **Note:** If the **bash_profile** doesn't open, run the following command:

    ```shell
    touch ~/.bash_profile; open ~/.bash_profile
    ```

13. Inside **bash_profile**, paste the path of the **flutter** folder that you copied.

    ```
    export PATH="$PATH:[your path]/bin"
    ```

14. Replace **[your path]** with the **flutter** folder path.

    The final path will be the same as the example below, but with your **flutter path**.

![screenshot](https://lh5.googleusercontent.com/drK-jBdJH71dFTcmOgWUzECjmyoTJeBju2mTAWgycHmUl6SzZIpK8S08xDeEUcueq1IEEIfsI2RW_PBnRW8vZWzwRDZugFXD9RDPlxBgCjQwftBNUhOePpqP-7aEQ78ajTEdQgd2)

15. Save **.bash_profile**. Quit **Terminal**, and reopen it again.

16. Run the following code in your terminal.

    ```shell
    flutter --version
    ```

    Make sure that you see the **flutter version**, like the example below, but maybe with a different version - No Problem :)

![screenshot](https://lh3.googleusercontent.com/k-hu3OPmsvizSChjQJoj_HCsKRR4DazJsB9cMewyzEnZvR2rFNoyAv0fv0asEVCwHwvpw9JwgdledNYxQrIaKU_TWlZizFSmKhvg527SPuDYx2965WZi1OxRpaWzZLteRNFc-wYT)

​

​

​

​

​

​

​

​
