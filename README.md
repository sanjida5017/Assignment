# Assignment
Programming Language And Structure

# the comparison between C++ and Java array structures are given below :

# In C++ :
Arrays can be allocated either on the stack or the heap. Fixed-size arrays declared like int arr[5]; are stack-allocated and have a size known at compile time. For runtime-determined sizes, C++ allows heap allocation using dynamic memory (new), as in int* arr = new int[n];, with manual deallocation using delete[]. Although some compilers support variable-length arrays (VLAs) on the stack (int arr[n];), this is non-standard in C++. For dynamic resizing, C++ provides the std::vector class from the Standard Template Library, which allows flexible array manipulation, supports primitive types directly, and requires explicit inclusion and initialization.

# In Java :
All arrays are heap-allocated regardless of when or how they are declared. Even fixed-size arrays like int[] arr = new int[5]; are allocated on the heap. Java does not support VLAs or true stack-dynamic arrays. For resizable arrays, Java uses ArrayList<Integer>, which is part of the java.util package. Unlike C++, Java does not allow pointer arithmetic and enforces array bounds checking at runtime, making it safer but less flexible in certain low-level operations. Additionally, Java collections like ArrayList require objects, so primitive types like int must be boxed into Integer, which can introduce slight overhead.

