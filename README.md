#include<iostream>
using namespace std;
class employee
{
private:
int salary;
public:
void setS(int S){
salary=S;
}
int getS(){
return salary;
}
};
int main()
{
employee myobj;
int n;
cout<<"enter  salary of employ:";
cin>>n;
myobj.setS(n);
cout<<"my obj.getS";
return(0);
}
