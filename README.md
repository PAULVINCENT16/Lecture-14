# Lecture-14
 #include #include #include using namespace std; int main(){

int random[1000];
int six=0;
for (int i = 0; i < 1000; i++) {
	random[i] = rand() % 100;
	cout << random[i] << " | ";
	if ((random[i] ==6)) {
		six++;
	}
}
cout << "\n\nNumber 6 appears: " << six << " times ";

return 0;
}

//Print largest number 
#include <iostream>
#include <string>
#include <array>
using namespace std;
int main(){

int User[10];
int i;
int max = User[0];
for (i = 0; i < 10; i++) {
	cin >> User[i];
	if (User[i] > max) {
		max = User[i];
	}
}
cout << "Largest Number inserted: " << max;
return 0;
}

//Print smallest number #include #include #include using namespace std; int main(){

int User[10];
int i;
int max;
for (i = 0; i < 10; i++) {
	cin >> User[i];
        max = User[0];
}
for (i = 0; i < 10; i++) {
	if (User[i] < max) {
		max = User[i];
	}
}
cout << "smallest Number inserted: " << max;
return 0;
}
