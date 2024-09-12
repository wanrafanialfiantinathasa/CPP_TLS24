# CPP_TLS24


#include <iostream>
#include <cstdio>

int main() {
    // Variables for base length and side length
    double base, side;
    
    // Ask the user to input the base length and side length
    std::cout << "Enter the base length of the parallelogram: ";
    std::scanf("%lf", &base);
    
    std::cout << "Enter the side length of the parallelogram: ";
    std::scanf("%lf", &side);
    
    // Using one conditional statement to check if inputs are valid
    if (base > 0 && side > 0) {
        // Calculate the perimeter of the parallelogram
        double perimeter = 2 * (base + side);
        
        // Output the result
        std::printf("The perimeter of the parallelogram is: %.2lf\n", perimeter);
    } else {
        std::printf("Base length and side length must be positive.\n");
    }
    
    return 0;
}


