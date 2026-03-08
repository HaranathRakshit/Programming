Install C++ Compiler (g++)
    sudo apt update
    sudo apt install build-essential -y

Check g++ Version
    g++ --version

Compile and Run a C++ Program
    Create file:
        nano hello.cpp

Sample code:
    #include <iostream>
    using namespace std;

    int main() {
        cout << "Hello from C++!" << endl;
        return 0;
    }

Compile:
    g++ hello.cpp -o hello

Run:
    ./hello
