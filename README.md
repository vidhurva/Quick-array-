
// A quick c++ array program 
  #include <iostream>
   using namespace std;
   
   int array[10];
   
   int main()
  {
          int i;
          i = 1;
  
  for(i = 0; i < 10; i++)
  {
          array[i] = i * 5;
          cout << array[i] << endl;
  }
  
  return 0;
  }
