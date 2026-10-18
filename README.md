# sum-of-two-array-


#include <iostream>
using namespace std;

int main()
{
    int a[5], b[5], sum[5];
    int i, choice;

    cout << "Enter 5 elements of first array:\n";
    for (i = 0; i < 5; i++)
    {
        cin >> a[i];
    }

    cout << "Enter 5 elements of second array:\n";
    for (i = 0; i < 5; i++)
    {
        cin >> b[i];
    }

    cout << "\n1. Add two arrays";
    cout << "\nEnter your choice: ";
    cin >> choice;

    switch (choice)
    {
        case 1:
            for (i = 0; i < 5; i++)
            {
                sum[i] = a[i] + b[i];
            }

            cout << "Sum of two arrays:\n";
            for (i = 0; i < 5; i++)
            {
                cout << sum[i] << " ";
            }
            break;

        default:
            cout << "Invalid choice";
    }

    return 0;
}
