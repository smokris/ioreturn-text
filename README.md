# IOReturn → Text converter

C function for converting IOReturn values to text

## Example

    int main(void)
    {
        IOReturn ret = -536870203;
        printf("%08x  %s\n", ret, getIOReturnText(ret));
    }

Output:

    e00002c5  IOKit Common: exclusive access and device already open
