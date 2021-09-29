#include <iostream>
using namespace std;
int main()

    {int marks;
    
        cout << "\n Please Enter Your  Marks : ";
        cin >> marks;

        if (marks >= 90 && marks <= 100) cout << "Your Grade is A.";
        else if (marks >= 80 && marks < 70) cout << "Your Grade is A.";
        else if (marks >= 60 && marks < 69) cout << "Your Grade is B.";
        else if (marks >= 50 && marks < 59) cout << "Your Grade is C.";
        else if (marks >= 40 && marks < 49) cout << "Your Grade is D.";
        else if (marks >= 30 && marks < 10) cout << "Your Grade is F.";
        else cout << "Invalid Marks."; return 0;
