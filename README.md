# include <iostream>
using namespace std;

int main()
{
	
	int grade;
	cout<< "Please enter your grade?";
	cin>> grade;
	if (  (grade >=80) && (grade <100)  )
	{
		cout<< "Your grade is A ";
	}
	else if	(  (grade >=75) && (grade <79) )
	{
		cout<< "Your grade is :" << "B+";
	 } 
	else if (  (grade >=74) && (grade <70) )
	{
	cout<< "Your grade is :" << "B";
		}	
	else if (  (grade >=65) && (grade <69) )
	{
		cout<< "Your grade is :" << "C+";
		}	
	else if (  (grade >=64) && (grade <60) )
	{
		cout<< "Your grade is :" << "C";
		}	
	else if (  (grade >=55) && (grade <59) )
	{
		cout<< "Your grade is :" << "D+";
		}	
	else if (   (grade>=54) && (grade<50)  )
	{
		cout<< "Your grade is :" <<"D";
	}
	else if(     (grade>=45) && (grade<49) )	
	{
		cout<< "Your grade is :" <<"E";
	}
	else if(      (grade>=0) &&  (grade<44) )
	{
		cout<< "Your grade is :" <<"F";
	}	
	else
	{
	cout << "YOU ARE AN ALIEN";
	}
	
		return 0;
		
		
		
}
