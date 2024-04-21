<div align="center"> 
    <img src="gitworld/0x15.gif" width="400" height="400" align="center"/>

    ```c
        #include <stdio.h>
        void main() 
        { 
            printf("%s endian %d bit", (char)0b000000001 ? "Little" : "big", sizeof(char*) * 8);
        }
    ```
    
</div>

