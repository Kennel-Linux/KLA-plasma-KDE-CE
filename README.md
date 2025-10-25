<div align="center">

# *KLA-plasma-KDE-CE*


<img width="2000" height="1220" alt="laptop svg" src="https://github.com/user-attachments/assets/da120458-92a6-4e1d-8583-b03a528d4e7f" />



<br><div align="center"><img width="12%" src="https://github.com/user-attachments/assets/c67f5b61-74d2-44fe-ba83-ae973402ac0a"/><br></div>


<a id="installation"></a>  
<img src="https://github.com/user-attachments/assets/7e1e2fa0-ab50-4901-a024-fe731fb44ab3" width="200"/>
---

<div align="left">

1) Create a folder `KLA-plasma-KDE-CE` typing in the terminal `mkdir -p KLA-plasma-KDE-CE`

2) Open a terminal in the created folder `KLA-plasma-KDE-CE` or go to the folder by typing in the terminal

   - `cd KLA-plasma-KDE-CE`

3) Place the build script  `FR_minimal_KLA_plasma_desktop.sh` in the created folder.
   
4) Make it executable.`chmod +x FR_minimal_KLA_plasma_desktop.sh`

5) Enter in terminal `./FR_minimal_KLA_plasma_desktop.sh`

6) Wait for the build to finish.

7) After the build is complete to package `07firstrib_rootfs` into `07KLA-plasma-KDE-x.x.sfs` where x.x is your build number.

8) Type in terminal.

```
mksquashfs 07firstrib_rootfs 07KLA-plasma-KDE-x.x.sfs -noappend -comp xz -b 512k
```
  - where x.x is your build number.

9) Delete the `07firstrib_rootfs` folder.After it is packed into " 07KLA-plasma-KDE-x.x.sfs "


```
 git clone https://github.com/sofijacom/KLA-plasma-KDE-CE.git
```

---
