PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_01
│   └── program01.cpp
#include <iostream>
using namespace std;
int main() {
    int a = 5, b = 10, c = 15;
    cout << a << " " << b << " " << c;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_02
│   └── program02.cpp

#include <iostream>
using namespace std;
int main() {
    cout << "C language is a powerful programming language.";
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_03
│   └── program03.cpp

#include <iostream>
using namespace std;
int main() {
    int a = 5, b = 10, temp;
    temp = a;
    a = b;
    b = temp;
    cout << a << " " << b;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_04
│   └── program04.cpp

#include <iostream>
using namespace std;
int main() {
    int year = 2;
    cout << "Months = " << year * 12;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_05
│   └── program05.cpp

#include <iostream>
using namespace std;
int main() {
    int a, b;
    cin >> a >> b;
    cout << "Sum = " << a + b << endl;
    cout << "Product = " << a * b;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_06 
│   └── program06.cpp

#include <iostream>
using namespace std;
int main() {
    int age;
    cin >> age;
    cout << "Age in months = " << age * 12;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_07
│   └── program07.cpp

#include <iostream>
using namespace std;
int main() {
    int roll, pf, ic, cg;
    cin >> roll >> pf >> ic >> cg;
    int total = pf + ic + cg;
    float avg = total / 3.0;
    cout << "Roll No = " << roll << endl;
    cout << "Total = " << total << endl;
    cout << "Average = " << avg;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_08
│   └── program08.cpp

#include <iostream>
using namespace std;
int main() {
    float f;
    cin >> f;
    float c = (5.0/9) * (f - 32);
    cout << "Celsius = " << c;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_09
│   └── program09.cpp

#include <iostream>
using namespace std;
int main() {
    int a, b, c, d;
    cin >> a >> b >> c >> d;
    int max = a;
    if(b > max) max = b;
    if(c > max) max = c;
    if(d > max) max = d;
    cout << "Maximum = " << max;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_10
│   └── program10.cpp

#include <iostream>
using namespace std;
int main() {
    float miles = 2.5;
    cout << "Kilometers = " << miles * 1.609;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_11
│   └── program11.cpp

#include <iostream>
using namespace std;
int main() {
    int a = 10, b = 20;
    float avg = (a + b) / 2.0;
    cout << "Average = " << avg;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_12
│   └── program12.cpp

#include <iostream>
using namespace std;
int main() {
    const float pi = 3.14;
    float r = 5, h = 10;
    float volume = pi * r * r * h;
    cout << "Volume = " << volume;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_13
│   └── program13.cpp

#include <iostream>
#define PI 3.14
using namespace std;
int main() {
    float r;
    cin >> r;
    cout << "Area = " << PI * r * r;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_14
│   └── program14.cpp

#include <iostream>
using namespace std;
int main() {
    float mm;
    cin >> mm;
    float inch = mm / 25.4;
    cout << "Inches = " << inch;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_15
│   └── program15.cpp

#include <iostream>
using namespace std;
int main() {
    int a, b, t;
    cin >> a >> b;
    t = a;
    a = b;
    b = t;
    cout << a << " " << b;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_16
│   └── program16.cpp

#include <iostream>
using namespace std;
int main() {
    int a = 3, b = 3, c = 3;
    int product = a * b * c;
    cout << "Product = " << product;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_17
│   └── program17.cpp

#include <iostream>
using namespace std;
int main() {
    float num = 15.58971;
    int integral = (int)num;
    float fractional = num - integral;
    cout << "Integral: " << integral << endl;
    cout << "Fractional: " << fractional;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_18
│   └── program18.cpp

#include <iostream>
using namespace std;
int main() {
    float vi, t, a;
    cin >> vi >> t >> a;
    float s = vi * t + 0.5 * a * t * t;
    cout << "s = " << s;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_19
│   └── program19.cpp

#include <iostream>
using namespace std;
int main() {
    int age;
    cin >> age;
    cout << "Months = " << age * 12 << endl;
    cout << "Days = " << age * 365;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_20
│   └── program20.cpp

#include <iostream>
using namespace std;
int main() {
    cout << "C:\\Windows>\n'P'\t'A'\t'K'\n\"Pakistan\"";
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_21
│   └── program21.cpp

#include <iostream>
using namespace std;
int main() {
    cout << "XXXXX\nXXXX\nXXX\nXX\nX";
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_22
│   └── program22.cpp

#include <iostream>
using namespace std;
int main() {
    string name, gender;
    int age;
    float height;

    cin >> name >> age >> height >> gender;

    cout << name << " " << age << " " << height << " " << gender;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_23
│   └── program23.cpp

#include <iostream>
using namespace std;
int main() {
    float r;
    cin >> r;
    float area = 3.14 * r * r;
    float circum = 2 * 3.14 * r;
    cout << "Area = " << area << endl;
    cout << "Circumference = " << circum;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_24
│   └── program24.cpp

#include <iostream>
using namespace std;
int main() {
    int a, b, c, d, e;
    cin >> a >> b >> c >> d >> e;
    int total = a + b + c + d + e;
    float avg = total / 5.0;
    cout << "Total = " << total << endl;
    cout << "Average = " << avg;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_25
│   └── program25.cpp

#include <iostream>
#include <cmath>
using namespace std;
int main() {
    float a, b, c;
    cin >> a >> b >> c;
    float s = (a + b + c) / 2;
    float area = sqrt(s * (s - a) * (s - b) * (s - c));
    cout << "Area = " << area;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_26
│   └── program26.cpp

#include <iostream>
using namespace std;
int main() {
    float rupees = 12000;
    float dollars = rupees / 60;
    cout << "Dollars = " << dollars;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_27
│   └── program27.cpp

#include <iostream>
using namespace std;
int main() {
    int h, m, s;
    cin >> h >> m >> s;
    int total = h * 3600 + m * 60 + s;
    cout << "Seconds = " << total;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_28
│   └── program28.cpp

#include <iostream>
using namespace std;
int main() {
    int a, b, c;
    cin >> a >> b >> c;
    int disc = b*b - 4*a*c;
    cout << "Discriminant = " << disc;
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_29
│   └── program29.cpp

#include <iostream>
using namespace std;
int main() {
    int n;
    cin >> n;
    if(n > 100)
        cout << "Greater than 100";
}

PF-Implementation-Assignment-Khuzaima Aleem
│
├── Program_30
│   └── program30.cpp

#include <iostream>
using namespace std;
int main() {
    int n;
    cin >> n;
    if(n % 2 == 0)
        cout << "Even";
    else
        cout << "Odd";
}
README.md
