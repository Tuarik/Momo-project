# Momo-project
#include <iostream>
 using namespace std;
int main() {
     const int defaultPIN=0000;
    int attempts=0;        
	int number;
	
   int pin;
   int num2;
    int num3;
   char Y;
   char N;
   int n1 ; 
   int n2 ;
   int num4;
  int number1;
  float amount;
	cout<<" Main Menu"<<endl;
	cout<<" 1. Checking balance"<<endl;
	cout<<" 2. Resetting/changing Pin"<<endl;
	cout<<" 3. Send MOMO"<<endl;
	cin>>number;
		
	
	if(number==1){
	cout << " Enter your 4 digit PIN" << endl;
	cin >> pin;
	attempts++;
	if(pin !=defaultPIN){cout<<"Incorrect PIN.Please try again"<<endl;
	}
	else if(pin == defaultPIN)
	{
	cout<<"your balance is:1000"<< endl; 
	} while (pin !=defaultPIN && attempts>3);
	if (attempts>3){cout <<"Maximum attempts reached.";
	cout <<"Exit program" <<endl;
	}
	switch (pin){
	break;
		} return 0; }

    if (number==2){
	cout<<"Are you sure you want change your PIN"<<endl;
	cout<<" 1. Yes"<<endl;
	cout <<" 2. No"<<endl;
    cin >>num3;
	}
	  if(num3==1 ){ 
	 cout <<"Enter old PIN "<<endl;
	 cin>>pin;


	attempts++;
	if(pin !=defaultPIN){cout<<"Incorrect PIN.Please try again"<<endl;
	}else if (pin ==defaultPIN){
		cout <<"Enter New PIN "<<endl;
		cin>>num3;
		cout<<"Comfrim the PIN"<<endl;
		cin>>num4;
		cout<<"PIN successful"<<endl;

	}}
	if (number==3){ 
	cout<<"Enter Mobile Number "<<endl;
	cin>> number1;
	cout <<"Comfrim Moblie Number"<<endl;
	cin>>number1;
	cout <<" Enter Amount To Transfer"<<endl;
	cin>>amount;
	cout<<"Transfer"<<" amount"<<" to"<<"0"<< number1<<endl;
	cout <<"Please enter your PIN:"<<endl;
	cin>>pin;
	do{
	 attempts++;
	 if (pin !=defaultPIN){
	 cout<<"Incorrect PIN.Please try again"<<endl;
	}
	else if (pin ==defaultPIN){cout <<"You have successfully sent "<<" amount"<<" to"<<"0"<<number1<<endl;
	}
	}while (pin !=defaultPIN && attempts>3);
	if (attempts>3){cout <<"Maximum attempts reached.";
	cout <<"Exit program" <<endl;
	}
	switch (pin){break;
	}
}



	

return 0; }
 
