# study
  2018.8.10 <br>
Ya-Di Ma:  https://en.cppreference.com/w/cpp/language/const_cast <br>
    Pointers to functions and pointers to member functions are not subject to const_cast

    const_cast makes it possible to form a reference or pointer to non-const type that is actually referring to a const object or a reference or pointer to non-volatile type that is actually referring to a volatile object. Modifying a const object through a non-const access path and referring to a volatile object through a non-volatile glvalue results in undefined behavior.
  2018.8.9 <br>
Ya-Di Ma: constants, pointer in C++.
