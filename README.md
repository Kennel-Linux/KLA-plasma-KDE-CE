# *KLA-plasma-KDE-CE*

![Снимок экрана_20241102_173019](https://github.com/user-attachments/assets/6be91245-ee57-4aa2-a827-62bf3e5be7c3)


![Снимок экрана_20241102_173416](https://github.com/user-attachments/assets/fa9b2c3f-7af8-4da0-9f67-4b533898cac4)

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

9) Delete the `07firstrib_rootfs` folder.


```
 git clone https://github.com/sofijacom/KLA-plasma-KDE-CE.git
```
