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


###### exercise2(2018.4.17)

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
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
