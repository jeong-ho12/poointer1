//# poointer1
#include<iostream>
  using namespace std;
 
 /*
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
  */
  
  
  
 void swapvalue(double &a,double &b)            //함수의 선언 및 구현(정의)
 {
  double t;
  t=a;
  a=b;
  b=t;
  }
  
  int main(void)
  {
  double x,y;
   cin>>x;
   cin>>y;
   
   cout<<"before swapvalue"<<x<<','<<y<<endl;
   
   swapvalue(x,y);
   
   cout<<"after swapvalue"<<x<<','<<y<<endl;
   
   return 0;
   }
   
 
  //추가 설명: 그냥 value만 사용했을 경우 함수 안에서 return 시 2개의 값을 동시에 return 불가 -> 함수 밖에도 영향을 줄 수 있는 참조자나 주소 사용.
  
  
  
  
  
