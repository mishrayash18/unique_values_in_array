# unique_values_in_array
// UNIQUE VALUES IN AN ARRAY
#include <iostream>
using namespace std;

int printunique(int arr[], int size) {
    for (int i=0; i<size; i++) {
        for (int j=0; j<size; j++) {
            if (i!=j && arr[i] == arr[j]) {
                cout << arr[j] << endl;
            }
        }
    }

}

int main() {
    int arr[] = {2,3,5,3,5,1};
    printunique(arr, 6);
    return 0;
}
