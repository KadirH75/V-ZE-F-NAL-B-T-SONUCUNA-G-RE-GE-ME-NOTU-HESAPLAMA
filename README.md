#include <iostream>
using namespace std;
int main()
{
int v, f, b, s1, s2;
cout << "lütfen vize ve final notunuzu giriniz :";
cin >> v >> f;
s1 = v * 0.5 + f * 0.5;
if (s1 < 60) {
	cout << s1 << ": puan ile büte kaldınız lütfen büt sonucunu giriniz :";
	cin >> b;
	s2 = v * 0.5 + b * 0.5;
	if (s2 < 60) {
		cout << s2 << ": puan ile dersten kaldınız lütfen bir dahaki sefere daha çok çalışın!";
	}
	else {
		cout << s2 << ": puan ile dersi büt ile geçtiniz tebrikler!";
	}
}
else {
	cout << s1 << ": puan ile dersi büt e kalmadan geçtiniz afein!";
}
return 0;
}
