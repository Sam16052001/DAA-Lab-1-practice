# Saddam Hussein
#20BCE0298
#A program that will return the nth smallest element in the array data. 

#include <algorithm>
#include <iostream>
using namespace std;

int kthSmallest(int arr[], int n, int k)
{
    sort(arr, arr + n);
    return arr[k - 1];
}

int main()
{
    int arr[] = {30,20,10,50,60,40};
    int n = sizeof(arr) / sizeof(arr[0]), k = 3;
    cout << "K'th smallest element is " << kthSmallest(arr, n, k);
    return 0;
}
