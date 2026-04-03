#include <iostream>
using namespace std;

int main() {
    int x;
    cin >> x;
    
    switch (x) {
        case 1:
            cout << "Один";
            break;
        case 2:
            cout << "Два";
            break;
        case 3:
            cout << "Три";
            break;
        default:
            cout << "Ошибка";
    }
    
    return 0;
}
