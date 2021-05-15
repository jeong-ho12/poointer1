//# poointer1
#include<iostream>
  using namespace std;
  
  int main(void)
  {
  double x;
  cin>>x;
  double *y=&x;   //변수 x의 주소값->포인터 y
  
  cout<<x<<endl;
  cout<<*y<<endl;    //여기서의 *는 주소값을 의미하는 y의 공간 안에 있는 값 호출을 의미
  //위 둘의 값이 같게 나와야 함
  cout<<&x<<endl;
  cout<<y<<endl;
  //위 둘의 값이 같게 나와야 함
  
  return 0;
  }
  
  
  
  
  
  
