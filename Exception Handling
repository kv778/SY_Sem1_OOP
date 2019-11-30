/*This is a program that uses exception handling when incorrect or inappropriate data is entered by the
user*/

#include<iostream>

using namespace std;

int main()
{
    string city;
    int vehicle;
    cout<<"Please enter the city : ";
    cin>>city;

    try                         //trying to check for incorrect data
    {
        if(city=="Pune" || city=="Mumbai" || city=="Bangalore" || city=="Chennai")
        {
        }
        else
        {
            throw city;        //throwing an exception if incorrect data is found
        }
    }

    catch(string city)          //catching the exception, and displaying error message
    {
        cout<<"Invalid city!"<<endl;
    }

    cout<<endl<<"Please enter 2 for 2 Wheeler and 4 for 4 Wheeler : ";
    cin>>vehicle;

    try                     //trying to check for incorrect data
    {
        if(vehicle!=4)
            throw vehicle;  //throwing an exception if incorrect data is found
    }

    catch(int vehicle)          //catching the exception, and displaying error message
    {
        cout<<"Invalid vehicle type!"<<endl;
    }

    return 0;
}
