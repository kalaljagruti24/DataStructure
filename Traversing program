
#include <iostream>

using namespace std;

// function for Array Traversal

void display(int arr[] , int n) {
    for(int i = 0; i < n; i++) {
        cout<<arr[i]<<"\t";
    }
    cout<<"\n";
}


// function for Array Insertion

int Insertion(int arr[] , int n , int capacity , int element , int ind) {
    
    if(n >= capacity) {
        return -1;
    }
    for(int i = n; i >= ind; i--) {
       arr[i+1] = arr[i];
    }
    arr[ind] = element;
    cout<<"\n";
    return 0;
}



int main() {
    
    int arr[10] = {1 , 2 , 3 , 4 , 5};
    int n = 5;
    
    display(arr , n);
    
    Insertion(arr, n , 10 , 58 , 1);
    
     display(arr , n+1);
    
    return 0;
}
