# Ch-Alli-chodry
/* This example scans various types of data  */ #include &lt;stdio.h>  int main(void) {    int i;    float fp;    char c, s[81];     printf("Enter an integer, a real number, a character "           "and a string : \n");    if (scanf("%d %f %c %s", &amp;i, &amp;fp, &amp;c, s) != 4)       printf("Not all of the fields were assigned\n");    else    {       printf("i
