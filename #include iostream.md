#include <iostream>  
using namespace std;  
  
int main() {  
    string ad;  
    cout << "Adinizi daxil edin: ";  
    cin >> ad;  
    cout << "Salam, " << ad << "!" << endl;  
    return 0;  
}  
  
  
  
#include <iostream>  
using namespace std;  
  
int main() {  
    int a, b;  
    cout << "Iki eded daxil edin: ";  
    cin >> a >> b;  
  
    cout << "Cem: " << a + b << endl;  
    cout << "Ferq: " << a - b << endl;  
    cout << "Hasil: " << a * b << endl;  
    if (b != 0)  
        cout << "Nisbət: " << a / b << endl;  
    else  
        cout << "Nisbət: 0-a bolmek olmaz!" << endl;  
  
    return 0;  
}  
  
  
#include <iostream>  
using namespace std;  
  
int main() {  
    int x;  
    cout << "Bir eded daxil edin: ";  
    cin >> x;  
  
    cout << "Kvadrati: " << x * x << endl;  
    cout << "Kubu: " << x * x * x << endl;  
  
    return 0;  
}  
  
  
#include <iostream>  
using namespace std;  
  
int main() {  
    int r;  
    int pi = 3;  
  
    cout << "Radiusu daxil edin: ";  
    cin >> r;  
  
    cout << "Sahesi: " <<  pi * r * r << endl;  
    cout << "Cevresi: " << 2 * pi * r << endl;  
  
    return 0;  
}  
  
  
#include <iostream>  
using namespace std;  
  
int main() {  
    int c;  
    cout << "Selsi derecesini daxil edin: ";  
    cin >> c;  
  
    int f = (c * 9 / 5) + 32;  
    cout << "Farenheyt: " << f << endl;  
  
    return 0;  
}  
  
  
#include <iostream>  
using namespace std;  
  
int main() {  
    int a, b, c;  
    cout << "Uc eded daxil edin: ";  
    cin >> a >> b >> c;  
  
    cout << "Ortalama: " << (a + b + c) / 3 << endl;  
  
    return 0;  
}  
  
  
  
#include <iostream>  
using namespace std;  
  
int main() {  
    int a, b;  
    cout << "Iki eded daxil edin: ";  
    cin >> a >> b;  
  
    a = a + b;  
    b = a - b;  
    a = a - b;  
  
    cout << "a = " << a << ", b = " << b << endl;  
  
    return 0;  
}  
  
  
  
  
#include <iostream>  
using namespace std;  
  
int main() {  
    int a;  
    cout << "Kvadratin terefini daxil edin: ";  
    cin >> a;  
  
    cout << "Sahesi: " << a * a << endl;  
    cout << "Perimetri: " << 4 * a << endl;  
  
    return 0;  
}  
  
  
#include <iostream>  
using namespace std;  
  
int main() {  
    int a;  
    cout << "Saniyeni daxil edin: ";  
    cin >> a ;  
  
    int b = a / 3600;  
    int c = a % 3600;  
    int d = c / 60;  
    int e = c % 60;  
  
    cout << b << " saat, " << d << " deqiqe, " << e << " saniye" << endl;  
  
    return 0;  
}  
  
