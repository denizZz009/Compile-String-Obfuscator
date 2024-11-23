ref: https://github.com/andrivet/ADVobfuscator

How to use
just include source codes in directory "include".
Wrap your raw string literal with "OBFUSCATE" macro.
#include <iostream>
#include "obfuscator.hpp"

int main(void) { 
	std::cout << OBFUSCATE("Private Key") << std::endl;
	return 0;
}
