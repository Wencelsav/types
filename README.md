#include <iostream>
#include <limits>

using namespace std;


int main() {
    cout << "bool  "<< sizeof(bool)
         << "("
         << numeric_limits<bool>::min()
         <<","
         << numeric_limits<bool>::max()
         <<")\n";

    cout <<"signed char  " << sizeof(signed char)
            << "("
            << (int)numeric_limits<signed char>::min()
            <<","
            << (int)numeric_limits<signed char>::max()
            <<")\n";
    cout << "unsigned char  "<< sizeof(unsigned char)
                             << "("
                             << (int)numeric_limits<unsigned char>::min()
                             <<","
                             << (int)numeric_limits<unsigned char>::max()
                             <<")\n";
    cout <<"char16_t  " << sizeof(char16_t)
            << "("
            << numeric_limits<char16_t>::min()
            <<","
            << numeric_limits<char16_t>::max()
            <<")\n";
    cout << "char32_t  "<< sizeof(char32_t)
            << "("
            << numeric_limits<char32_t>::min()
            <<","
            << numeric_limits<char32_t>::max()
            <<")\n";
    cout << "wchar_t  "<< sizeof(wchar_t)
            << "("
            << numeric_limits<wchar_t>::min()
            <<","
            << numeric_limits<wchar_t>::max()
            <<")\n";

    cout <<"int  " << sizeof(int)
            << "("
            << numeric_limits<int>::min()
            <<","
            << numeric_limits<int>::max()
            <<")\n";
    cout << "unsigned int  "<< sizeof(unsigned int)
                            << "("
                            << numeric_limits<unsigned int>::min()
                            <<","
                            << numeric_limits<unsigned int>::max()
                            <<")\n";
    cout <<"short  " << sizeof(short)
                     << "("
                     << numeric_limits<short>::min()
                     <<","
                     << numeric_limits<short>::max()
                     <<")\n";
    cout <<"unsigned short  " << sizeof(unsigned short)
            << "("
            << numeric_limits<unsigned short>::min()
            <<","
            << numeric_limits<unsigned short>::max()
            <<")\n";
    cout << "long  "<< sizeof(long)
                    << "("
                    << numeric_limits<long>::min()
                    <<","
                    << numeric_limits<long>::max()
                    <<")\n";
    cout <<"unsigned long  " << sizeof(unsigned long)
                             << "("
                             << numeric_limits<unsigned long>::min()
                             <<","
                             << numeric_limits<unsigned long>::max()
                             <<")\n";
    cout <<"long long  " << sizeof(long long)
                         << "("
                         << numeric_limits<long long>::min()
                         <<","
                         << numeric_limits<long long>::max()
                         <<")\n";
    cout << "unsigned long long  " << sizeof(unsigned long long)
                                   << "("
                                   << numeric_limits<unsigned long long>::min()
                                   <<","
                                   << numeric_limits<unsigned long long>::max()
                                   <<")\n";

    cout << "\nfloat  "<< sizeof(float)
                     << "("
                     << numeric_limits<float>::min()
                     <<","
                     << numeric_limits<float>::max()
                     <<")\n";
    cout << "double  "<< sizeof(double)
            << "("
            << numeric_limits<double>::min()
            <<","
            << numeric_limits<double>::max()
            <<")\n";
    cout <<"long double  " << sizeof(long double)
                           << "("
                           << numeric_limits<long double>::min()
                           <<","
                           << numeric_limits<long double>::max()
                           <<")\n";
                           
    cout <<"\nvoid  " <<endl;

    cout <<"nullptr_t  " <<endl;






    cin.get();

}
