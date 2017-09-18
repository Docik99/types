#include <iostream>
#include <limits>

using namespace std;

int main()
{
    cout << "bool: " << sizeof(bool)
         << " byte   ("
         << numeric_limits<bool>::min()
         << "; "
         << numeric_limits<bool>::max()
         << ") \n\n";

    cout << "unsigned char: " << sizeof(unsigned char)
         << " byte   ("
         << (int)numeric_limits<unsigned char>::min()
         << "; "
         << (int)numeric_limits<unsigned char>::max()
         << ") \n\n";

    cout << "signed char: " << sizeof(signed char)
         << " byte   ("
         << (int)numeric_limits<signed char>::min()
         << "; "
         << (int)numeric_limits<signed char>::max()
         << ") \n\n";
    
    cout << "char: " << sizeof(char)
         << " byte   ("
         << (int)numeric_limits<char>::min()
         << "; "
         << (int)numeric_limits<char>::max()
         << ") \n\n";
    
    cout << "char16_t: " << sizeof(char16_t)
         << " byte   ("
         << (int)numeric_limits<char16_t>::min()
         << "; "
         << (int)numeric_limits<char16_t>::max()
         << ") \n\n";
    
    cout << "char32_t: " << sizeof(char32_t)
         << " byte   ("
         << (int)numeric_limits<char32_t>::min()
         << "; "
         << (int)numeric_limits<char32_t>::max()
         << ") \n\n";
    
    cout << "wchar_t: " << sizeof(wchar_t)
         << " byte   ("
         << (int)numeric_limits<wchar_t>::min()
         << "; "
         << (int)numeric_limits<wchar_t>::max()
         << ") \n\n";

    cout << "short: " << sizeof(short)
         << " byte   ("
         << numeric_limits<short>::min()
         << "; "
         << numeric_limits<short>::max()
         << ") \n\n";
    
    cout << "unsigned short: " << sizeof(unsigned short)
         << " byte   ("
         << numeric_limits<unsigned short>::min()
         << "; "
         << numeric_limits<unsigned short>::max()
         << ") \n\n";
    
    cout << "int: " << sizeof(int)
         << " byte   ("
         << numeric_limits<int>::min()
         << "; "
         << numeric_limits<int>::max()
         << ") \n\n";
    
    cout << "unsigned int: " << sizeof(unsigned int)
         << " byte   ("
         << numeric_limits<unsigned int>::min()
         << "; "
         << numeric_limits<unsigned int>::max()
         << ") \n\n";
    
    cout << "long: " << sizeof(long)
         << " byte   ("
         << numeric_limits<long>::min()
         << "; "
         << numeric_limits<long>::max()
         << ") \n\n";
    
    cout << "unsigned long: " << sizeof(unsigned long)
         << " byte   ("
         << numeric_limits<unsigned long>::min()
         << "; "
         << numeric_limits<unsigned long>::max()
         << ") \n\n";
    
    cout << "long long: " << sizeof(long long)
         << " byte   ("
         << numeric_limits<long long>::min()
         << "; "
         << numeric_limits<long long>::max()
         << ") \n\n";
    
    cout << "unsigned long long: " << sizeof(unsigned long long)
         << " byte   ("
         << numeric_limits<unsigned long long>::min()
         << "; "
         << numeric_limits<unsigned long long>::max()
         << ") \n\n";

    cout << "float: " << sizeof(float)
         << " byte   ("
         << numeric_limits<float>::min()
         << "; "
         << numeric_limits<float>::max()
         << ") \n\n";
    
    cout << "double: " << sizeof(double)
         << " byte   ("
         << numeric_limits<double>::min()
         << "; "
         << numeric_limits<double>::max()
         << ") \n\n";
    
    cout << "long double: " << sizeof(long double)
         << " byte   ("
         << numeric_limits<long double>::min()
         << "; "
         << numeric_limits<long double>::max()
         << ") ";

    cin.get();
}

'''
'''

bool: 1 byte   (0; 1) 

unsigned char: 1 byte   (0; 255) 

signed char: 1 byte   (-128; 127) 

char: 1 byte   (-128; 127) 

char16_t: 2 byte   (0; 65535) 

char32_t: 4 byte   (0; -1) 

wchar_t: 4 byte   (-2147483648; 2147483647) 

short: 2 byte   (-32768; 32767) 

unsigned short: 2 byte   (0; 65535) 

int: 4 byte   (-2147483648; 2147483647) 

unsigned int: 4 byte   (0; 4294967295) 

long: 8 byte   (-9223372036854775808; 9223372036854775807) 

unsigned long: 8 byte   (0; 18446744073709551615) 

long long: 8 byte   (-9223372036854775808; 9223372036854775807) 

unsigned long long: 8 byte   (0; 18446744073709551615) 

float: 4 byte   (1.17549e-38; 3.40282e+38) 

double: 8 byte   (2.22507e-308; 1.79769e+308) 

long double: 16 byte   (3.3621e-4932; 1.18973e+4932) 
