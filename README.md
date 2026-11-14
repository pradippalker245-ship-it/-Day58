# -Day58
My c++ language daily practice 
#include <iostream>
using namespace std;

class Addition
{
public:
    int add(int a, int b)
    {
        return a + b;
    }

    int add(int a, int b, int c)
    {
        return a + b + c;
    }

    float add(float a, float b)
    {
        return a + b;
    }
};

int main()
{
    Addition obj;

    cout << obj.add(10, 20) << endl;
    cout << obj.add(10, 20, 30) << endl;
    cout << obj.add(2.5f, 3.5f) << endl;

    return 0;
}
