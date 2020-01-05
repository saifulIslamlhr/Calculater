#include <iostream>

using namespace std;

int
main()
{
    long user_input = 0;

    cout << " Please choose a option \n (1) Plus 5 numbers \n (2) Minus 5 numbers \n (3) Multiply 5 numbers \n (4) Divide 5 numbers \n (5) Exit" << endl;
    cin >> user_input;

    while (user_input != 5) {

        if (user_input == 1) {
            long first_number;
            long second_number;

            int third_number;
            int fourth_number;

            int fifth_number;
            int sum;

            cout << "Type first number" << endl;
            cin >> first_number;

            cout << "Type second number" << endl;
            cin >> second_number;

            cout << "Type third number" << endl;
            cin >> third_number;

            cout << "Type fourth number" << endl;
            cin >> fourth_number;

            cout << "Type fifth number" << endl;
            cin >> fifth_number;

            sum = (first_number + second_number) + third_number + fourth_number + fifth_number;
            cout << "The sum is " << sum << endl;

            cout << "Please select a option, (1), (2), (3), (4) or (5) " << endl;
            cin >> user_input;

         
        }

        if (user_input == 2) {

            long f;
            long s;

            int t;
            int fs;

            int fs2 = 0;
            int sum2;

            cout << "Type first number" << endl;
            cin >> f;

            cout << "Type second number" << endl;
            cin >> s;

            cout << "Type third number" << endl;
            cin >> t;

            cout << "Type fourth number" << endl;
            cin >> s;

            cout << "Type fifth number" << endl;
            cin >> fs;

            sum2 = (f - s) - t - fs - fs2;
            cout << "The sum is " << sum2 << endl;

            cout << "Please select a option, (1), (2), (3), (4) or (5) " << endl;
            cin >> user_input;

        }

        if (user_input == 3) {
            
            long first;
            long second;

            int third;
            int fourth;

            int fifth;
            int sum3;

            cout << "Type first number" << endl;
            cin >> first;

            cout << "Type second number" << endl;
            cin >> second;

            cout << "Type third number" << endl;
            cin >> third;

            cout << "Type fourth number" << endl;
            cin >> fourth;

            cout << "Type fifth number" << endl;
            cin >> fifth;

            sum3 = (first * second) * third * fourth * fifth;
            cout << "The sum is " << sum3 << endl;

            cout << "Please select a option, (1), (2), (3), (4) or (5) " << endl;
            cin >> user_input;
        }

        if (user_input == 4) {

            long firsts;
            long seconds;

            int thirds;
            int fourths;

            int fifths;
            int sum4;

            cout << "Type first number" << endl;
            cin >> firsts;

            cout << "Type second number" << endl;
            cin >> seconds;

            cout << "Type third number" << endl;
            cin >> thirds;

            cout << "Type fourth number" << endl;
            cin >> fourths;

            cout << "Type fifth number" << endl;
            cin >> fifths;

            sum4 = (firsts / seconds) / thirds / fourths / fifths;
            cout << "The sum is " << sum4 << endl;

            cout << "Please select a option, (1), (2), (3), (4) or (5) " << endl;
            cin >> user_input;

        }
    }

    return 0;
}
