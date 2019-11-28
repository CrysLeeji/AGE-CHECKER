#include<iostream>

using namespace std;

int main(){
    
    cout<<"****************************************************************************************************************"<<endl;
    cout<<"                     "<<endl;
    cout<<"A G E   C H E C K E R | A G E   C H E C K E R | A G E   C H E C K E R | A G E   C H E C K E R | A G E    C H E"<<endl;
    cout<<"                     "<<endl;
    cout<<"****************************************************************************************************************"<<endl;
    
    int userAge;
    
    cout<<"                      "<<endl;;
    cout<<"Please enter your age:";
    cin>>userAge;
    
    if(userAge==18)
        cout<<"Here's a wristband"<<endl;
    
    else if(userAge==19)
        cout<<"Here's a wristband"<<endl;
    
    else if(userAge==20)
        cout<<"Here's a wristband"<<endl;
    
    else if(userAge<18)
        cout<<"Please leave!"<<endl;
    
    else{
        cout<<"Welcome user!"<<endl;
    }
    
    return 0;
}
