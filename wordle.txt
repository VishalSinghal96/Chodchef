#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t;
	cin >> t;
	while(t--)
	{
	    string s;
	   string t;
	   cin >> s;
	   cin >> t;
	   string m ="";
	   for(int i=0;i<5;i++)
	   {
	       if(s[i]==t[i])
	       {
	           m += "G";
	       }
	       else
	       {
	           m += "B";
	       }
	   }
	       cout<< m << endl;
	   }
	
	return 0;
}