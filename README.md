#include using namespace std;

int main() { int num;

cout << "Enter a number: ";
cin >> num;

// Check even or odd using modulus operator
if (num % 2 == 0) {
    cout << num << " is Even." << endl;
} else {
    cout << num << " is Odd." << endl;
}

return 0;
}
