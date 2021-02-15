# Lab-25.20-
/* _Flags_

Boolean variables are variables that can have only two possible values: true, and false. To declare a Boolean variable, we use the keyword bool.

A flag is a variable that signals a condition, commonly implemented as a bool variable. It could also be an integer where the value 0 is considered false and any nonzero value is considered true. As with other variables in functions, flags must be assigned an initial value before they are used.

Instructions: 
The following program has errors. Fix them so it works properly.  */

// This program averages 3 test scores.
// It uses the variable perfectScore as a flag.
#include <iostream>
using namespace std;

int main()
{
  bool perfectScore;
	cout << "Enter your 3 test scores and I will " << endl
	<< "average them:";
	int score1, score2, score3;
	cin >> score1 >> score2 >> score3;

	double average;
	average = (score1 + score2 + score3) / 3.0;

	if (average != 100) 
  {
	cout << "Your average is " << average << endl;
  }
	
	if (perfectScore)
	{
    perfectScore = true; // Set the flag variable
		cout << "Congratulations!\n";
		cout << "That's a perfect score.\n";
		cout << "You deserve a pat on the back!\n";
  }
}
