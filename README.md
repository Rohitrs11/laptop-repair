# laptop-repair
using c++


#include<iostream>
#include<fstream>
using namespace std;
int main()
{
	ofstream out("Laptop_repair_service and retail");
	ofstream out1("register1");
	char name[40],email[60],countryofthelaptoppurchase[30],city[30],state[20],namelap[20],model[40],a[20],b[20];
	int s;
	int pincode;
	long long int mobile;
	cout<<"                                     Royal laptop repair service and retail"<<endl;
	out<<"                                     Royal Laptop repair service and retail"<<endl;
	out<<"                                      Register"<<endl;
	cout<<"Hi sir!"<<endl;
	cin>>a;
	cout<<"How may i help you?"<<endl;
	cin>>b;
	cout<<"enter your details in the register"<<endl;
	cout<<"Name : ";
	cin>>name;
	out<<"Name : ";
	out1<<"Name : ";
	out1<<name<<endl;
	out<<name<<endl;
	cout<<"Email : ";
	cin>>email;
	out<<"Email : ";
	out1<<"Email : ";
	out1<<email<<endl;
	out<<email<<endl;
	cout<<"City : ";
	cin>>city;
	out<<"City : ";
	out1<<"City : ";
	out1<<city<<endl;
	out<<city<<endl;
	cout<<"State : ";
	cin>>state;
	out1<<"State : ";
	out<<"State : ";
	out1<<state<<endl;
	out<<state<<endl;
	cout<<"Pincode : ";
	cin>>pincode;
	out<<"Pincode : ";
	out1<<"Pincode : ";
	out1<<pincode<<endl;
	out<<pincode<<endl;
	cout<<"Mobile : ";
	cin>>mobile;
	out<<"Mobile : ";
	out1<<"Mobile : ";
	out1<<mobile<<endl;
	out<<mobile<<endl;
	cout<<"country of the laptop purchase: ";
	cin>>countryofthelaptoppurchase;
	out<<"country of the laptop purchase : ";
	out1<<"country of the laptop purchase : ";
	out1<<countryofthelaptoppurchase<<endl;
	out<<countryofthelaptoppurchase<<endl;
	cout<<"name of laptop : ";
	cin>>namelap;
	out<<"name of laptop  : ";
	out1<<"name of laptop : ";
	out1<<namelap<<endl;
	out<<namelap<<endl;
	cout<<"Model : ";
	cin>>model;
	out<<"Model : ";
	out1<<"Model : ";
	out1<<model<<endl;
	out<<model<<endl;
	cout<<"Enter 1 for operating system installations issues"<<endl;
	cout<<"Enter 2 for battery related problems"<<endl;
	cout<<"Enter 3 for display related issues"<<endl;
	cin>>s;
	switch(s)
		{
			case 1:
			out<<"Purpose of visit : Os Installation"<<endl;
			int a1;
			cout<<"enter 1 for windows installation"<<endl;
			cout<<"enter 2 for ios installation"<<endl;
			cin>>a1;
			switch(a1)
			{
				case 1:
					int d1;
					out<<"Type of operating system: Windows"<<endl;
					cout<<"enter window 7 or 8.1 or 10"<<endl;
					cin>>d1;
					if(d1==7)
					{
						int c;
						out<<"Software type : Windows 7"<<endl;
						cout<<"cost of software : 1000"<<endl;
						out<<"cost of software : 1000"<<endl;
						c=(5*1000)/100;
						cout<<"service charge : "<<c<<endl;
						out<<"service charge : "<<c<<endl;
						c=c+1000;
						cout<<"total amount to be charged : "<<c;
						out<<"total amount to be charged : "<<c;
					}
					if(d1==8)
					{
						int c;
						out<<"Software type : Windows 8.1"<<endl;
						cout<<"cost of software : 1500"<<endl;
						out<<"cost of software : 1500"<<endl;
						c=(5*1500)/100;
						cout<<"service charge : "<<c<<endl;
						out<<"service charge : "<<c<<endl;
						c=c+1500;
						cout<<"total amount to be charged : "<<c;
						out<<"total amount to be charged : "<<c;
					}
					if(d1==10)
					{
						int c;
						out<<"Software type : Windows 10"<<endl;
						cout<<"cost of software : 2000"<<endl;
						out<<"cost of software : 2000"<<endl;
						c=(5*2000)/100;
						cout<<"service charge : "<<c<<endl;
						out<<"service charge : "<<c<<endl;
						c=c+2000;
						cout<<"total amount to be charged : "<<c;
						out<<"total amount to be charged : "<<c;
					}
					break;
				case 2:
					int c;
					out<<"Type of operating system : IOS"<<endl;
					out<<"Software type : IOS"<<endl;
						cout<<"cost of software : 3000"<<endl;
						out<<"cost of software : 3000"<<endl;
						c=(5*3000)/100;
						cout<<"service charge : "<<c<<endl;
						out<<"service charge : "<<c<<endl;
						c=c+3000;
						cout<<"total amount to be charged : "<<c;
						out<<"total amount to be charged : "<<c;
					break;
			}
		case 2:
			out<<"Purpose of Visiting : Battery Repair"<<endl;
			int a,b,c,d;
			cout<<"How many hours backup is coming"<<endl;
			cin>>a;
			cout<<"within how many days u want ur laptop to be repaired"<<endl;
			cin>>b;
			if(b<2)
			{
				out<<"Delivery time : Within 2 days"<<endl;
				cout<<"cost of Battery : 2000"<<endl;
				out<<"cost of Battery  : 2000"<<endl;
				c=(2000*10)/100;
				cout<<"Service Charge : "<<c<<endl;
				out<<"Service Charge : "<<c<<endl;
				c=c+2000;
				cout<<"Total Amount to be charged : "<<c<<endl;
				out<<"Total Amount to be charged : "<<c<<endl;		
			}
			if(b>=2 && b<6)
			{
				out<<"Delivery time : Within 2 days"<<endl;
				cout<<"cost of Battery  : 2000"<<endl;
				out<<"cost of Battery  : 2000"<<endl;
				c=(1700*10)/100;
				cout<<"Service Charge : "<<c<<endl;
				out<<"Service Charge : "<<c<<endl;
				c=c+1700;
				cout<<"Total Amount to be charged : "<<c<<endl;
				out<<"Total Amount to be charged : "<<c<<endl;		
			}
			if(b>=6)
			{
				out<<"Delivery time : Within 2 days"<<endl;
				cout<<"cost of Battery  : 2000"<<endl;
				out<<"cost of Battery : 2000"<<endl;
				c=(1500*10)/100;
				cout<<"Service Charge : "<<c<<endl;
				out<<"Service Charge : "<<c<<endl;
				c=c+1500;
				cout<<"Total Amount to be charged : "<<c<<endl;
				out<<"Total Amount to be charged : "<<c<<endl;		
			}
			break;
		case 3:
			out<<"Purpose of Visit : Screen issue"<<endl;
			float a2;
			int b2,b3;
			cout<<"size of your screen"<<endl;
			cin>>a2;
			out<<"size of your screen : "<<a2<<endl;
			if(a2<10)
			{
				cout<<"enter 1 for oled screen"<<endl;
				cout<<"enter 2 for normal screen"<<endl;
				cin>>b2;
				switch(b2)
				{
					case 1:
						int c1,d1;
						c1=14*400;
						cout<<"Your screen cost : "<<c1<<endl;
						out<<"Your screen cost : "<<c1<<endl;
						d1=(5*c1)/100;
						cout<<"Service charge : "<<d1<<endl;
						out<<"Service charge : "<<d1<<endl;
						c1=c1+d1;
						cout<<"total amount that is charged : "<<c1<<endl;
						out<<"total amount that is charged: "<<c1<<endl;
						break;
					case 2:
						
						c1=14*200;
						cout<<"Your screen cost : "<<c1<<endl;
						out<<"Your screen cost : "<<c1<<endl;
						d1=(5*c1)/100;
						cout<<"Service charge : "<<d1<<endl;
						out<<"Service charge : "<<d1<<endl;
						c1=c1+d1;
						cout<<"total amount that is charged : "<<c1<<endl;
						out<<"total amount that is charged : "<<c1<<endl;
						break;
				}
				
			}
			if(a2>=10 && a2<14)
			{
				cout<<"enter 1 for oled screen"<<endl;
				cout<<"enter 2 for normal screen"<<endl;
				cin>>b2;
				switch(b2)
				{
					case 1:
						int c1,d1;
						c1=15*600;
						cout<<"Your screen cost : "<<c1<<endl;
						out<<"Your screen cost : "<<c1<<endl;
						d1=(5*c1)/100;
						cout<<"Service charge : "<<d1<<endl;
						out<<"Service charge : "<<d1<<endl;
						c1=c1+d1;
						cout<<"total amount that is charged : "<<c1<<endl;
						out<<"total amount that is charged : "<<c1<<endl;
						break;
					case 2:
						
						c1=15*400;
						cout<<"Your screen cost : "<<c1<<endl;
						out<<"Your screen cost : "<<c1<<endl;
						d1=(5*c1)/100;
						cout<<"Service charge : "<<d1<<endl;
						out<<"Service charge : "<<d1<<endl;
						c1=c1+d1;
						cout<<"total amount that is charged : "<<c1<<endl;
						out<<"total amount that is charged : "<<c1<<endl;
						break;
				}
				
			}
				if(a2>=14)
			{
				cout<<"enter 1 for oled screen"<<endl;
				cout<<"enter 2 for normal screen"<<endl;
				cin>>b2;
				switch(b2)
				{
					case 1:
						int c1,d1;
						c1=16*650;
						cout<<"Your screen cost : "<<c1<<endl;
						out<<"Your screen cost : "<<c1<<endl;
						d1=(5*c1)/100;
						cout<<"Service charge : "<<d1<<endl;
						out<<"Service charge : "<<d1<<endl;
						c1=c1+d1;
						cout<<"total amount that is charged: "<<c1<<endl;
						out<<"total amount that is charged : "<<c1<<endl;
						break;
					case 2:
						
						c1=16*350;
						cout<<"Your screen cost : "<<c1<<endl;
						out<<"Your screen cost : "<<c1<<endl;
						d1=(5*c1)/100;
						cout<<"Service charge : "<<d1<<endl;
						out<<"Service charge : "<<d1<<endl;
						c1=c1+d1;
						cout<<"total amount that is charged : "<<c1<<endl;
						out<<"total amount that is charged: "<<c1<<endl;
						break;
				}
				
			}	
	}
	out.close();
	out1.close();	
}
