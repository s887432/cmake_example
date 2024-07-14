# cmake_example
This is a template of cmake for application.<br>
The output(executable) file name will be as same as the project folder name.<br>

if adding -DARCH paramater, the compiler will be selected as the ARCH.<br>
For example: -DARCH-x86 <br>
if no ARCH defined, will use the default in CMakeFiles.txt. <br>

The output path will be created automatically.<br>
For x86 platform, the output path name is x86_bin.<br>
For Cortex series, the output path name is cortex_bin.<br>
For Arm9 series, the output path name is arm9_bin.<br>

Be noted that, you need to modify corss compiler in CMakeFiles.txt.br>

## usage
$ make build<br>
$ cmake ..<br>

$ make build<br>
$ cmake -DARCH=Cortex ..<br>

## 
Have fun!!!<br>
Patrick Lin, 2024/7/14 @ Taipei
