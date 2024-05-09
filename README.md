<div> 

<pre>
#include &#60;stdio.h&#62;
char main() { 
    printf("%s endian %d bit", (char)0b000000001 ? "Little" : "big", sizeof(char*) * 8);
    return 0;
}
</pre>

</div>
