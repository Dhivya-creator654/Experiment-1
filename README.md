#include <stdio.h>

int find second-largest (int arr [], int size)
{
int largest = arr[0];

int second largest = -1;

for (int i = 1; i<size; i++)
{
if (arr (i] > largest)

second largest = largest;

largest = arr[i];
}
else if (arr[i]> second largest &&arr[i]=largest)
{
Second largest = arr[i];
}
}

return second largest;}
int main()

{

int size;

Printf ("Input the size of array");

Scanf( "%d", & size);

int arr[size];

for Cint i=0; i<size;i++)


{

Printf ("element>d:",i);

} ind second-largest = find second largest (arr,size);

Printf (" the second largest element array%d\n", second largest element);


return o;

}




