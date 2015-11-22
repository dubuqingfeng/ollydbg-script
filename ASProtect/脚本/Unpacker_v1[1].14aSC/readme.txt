                                    **使用前的修改**

把压缩包中的 Asprvm8s.bin 放在一个你指定的地方, 然后用记事本修改脚本中的这里


lab78_1:
log VMcodeloc
lm VMcodeloc, 4000, "d:\Asprvm8s.bin"         ---> 修改这句


如你是把 Asprvm8s.bin 放在 c:\script 的目录下则把上面这句改成


lm VMcodeloc, 4000, "C:\script\Asprvm8s.bin"


然后存档.



                            **Modification needed before usage**

Copy the Asprvm8s.bin into a folder you want , then use text editor to modify this part of the script


lab78_1:
log VMcodeloc
lm VMcodeloc, 4000, "d:\Asprvm8s.bin"         ---> modify this line


if Asprvm8s.bin is copied under the folder c:\script the above command should be chnaged as


lm VMcodeloc, 4000, "C:\script\Asprvm8s.bin"



