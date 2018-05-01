# cpp
###### exercise1:陣列存取與基本運算(2018.4.7)
```
 #include <iostream>
using namespace std;

int main()
{
  const int NUMBER_OF_ELEMENTS = 2;
  double numbers[NUMBER_OF_ELEMENTS];
  double numbers_squared[NUMBER_OF_ELEMENTS];
  double sum = 0;

  for (int i = 0; i < NUMBER_OF_ELEMENTS; i++)
  {
    cout << "Enter a new number: ";
    cin >> numbers[i];
    sum += numbers[i];
    numbers_squared[i]=numbers[i]*numbers[i];
  }
  cout << "numbers[1] is " << numbers[1] << endl;
  cout << "numbers_squared[1] is " << numbers_squared[1] << endl;
  
  double average = sum / NUMBER_OF_ELEMENTS;

  int count = 0; // The number of elements above average
  for (int i = 0; i < NUMBER_OF_ELEMENTS; i++)
    if (numbers[i] > average)
      count++;

  cout << "Average is " << average << endl;
  cout << "Number of elements above the average " << count << endl;
  system("pause"); 
  return 0;
}

```
###### exercise2陣列(2018.4.17)

```
#include <iostream>
#include <iomanip>
using namespace std;
int fun(int array[3][3])
{
	int i,j,t;
	for(i=0;i<3;i++)
		for(j=0;j<i;j++)
		{
			t=array[i][j];
			array[i][j]=array[j][i];
			array[j][i]=t;
		}
		return 0;
}
int main()
{
	int i,j;
	int array[3][3]={{1,2,3},{4,5,6},{7,8,9}};
	cout << "Converted Front" <<endl;
	for(i=0;i<3;i++)
	{
		for(j=0;j<3;j++)
			cout << setw(7) << array[i][j] ;
		cout<< endl;
	}
	fun(array);
	cout << "Converted result" <<endl;
	for(i=0;i<3;i++)
	{
		for(j=0;j<3;j++)
			cout << setw(7) << array[i][j] ;
		cout<< endl;
	}
    return 0;
}

```
###### exercise3球

```
#include <cstdlib>
#include <iostream>

using namespace std;
float sarea(float pi, int r){
      return 4*pi*r*r;
      }
float svolumn(float pi, int r){
      return 4*pi*r*r*r/3;
      }
int main(int argc, char *argv[])
{
    float pi = 3.14;
    int q = 1;
    int w = 2;
    int e = 3;
    int r = 4;
    int t = 5;
    int y = 6;
    int u = 7;
    int i = 8;
    int o = 9;
    int p = 10;
    
    
    cout << "表面積: " << sarea(pi,q) << endl;
    cout << "體積: " << svolumn(pi,q) << endl;
    cout << "表面積: " << sarea(pi,w) << endl;
    cout << "體積: " << svolumn(pi,w) << endl;
    cout << "表面積: " << sarea(pi,e) << endl;
    cout << "體積: " << svolumn(pi,e) << endl;
    cout << "表面積: " << sarea(pi,r) << endl;
    cout << "體積: " << svolumn(pi,r) << endl;
    cout << "表面積: " << sarea(pi,t) << endl;
    cout << "體積: " << svolumn(pi,t) << endl;
    cout << "表面積: " << sarea(pi,y) << endl;
    cout << "體積: " << svolumn(pi,y) << endl;
    cout << "表面積: " << sarea(pi,u) << endl;
    cout << "體積: " << svolumn(pi,u) << endl;
    cout << "表面積: " << sarea(pi,i) << endl;
    cout << "體積: " << svolumn(pi,i) << endl;
    cout << "表面積: " << sarea(pi,o) << endl;
    cout << "體積: " << svolumn(pi,o) << endl;
    cout << "表面積: " << sarea(pi,p) << endl;
    cout << "體積: " << svolumn(pi,p) << endl;
     
    
    system("PAUSE");
    return EXIT_SUCCESS;
}

```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
