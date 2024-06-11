# structure of student
 a program in which you have to make a structure of student to store name or marks of a student.
 #include<iostream>
using namespace std;
struct student
{
string name;
int math;
int english;
};
int main()
{
student s1;
cout<<"enter name:"<<endl;
cin>>s1.name;
cout<<"enter marks of maths or english:"<<endl;
cin>>s1.math>>s1.english;
cout<<"student 1:"<<endl<<s1.name<<endl<<s1.math<<endl<<s1.english;
}
