# inheritance-cmake
inheritance cmake

A demo of: https://kubasejdak.com/modern-cmake-is-like-inheritance

.
├── CMakeLists.txt <br />
├── libA <br />
│   ├── include <br />
│   │   └── libA <br />
│   │       └── sourceA.h <br />
│   ├── privateHeaderA1.h <br />
│   ├── privateHeaderA2.h <br />
│   └── sourceA.cpp <br />
├── libB <br />
│   ├── include <br />
│   │   └── libB <br />
│   │       └── sourceB.h <br />
│   ├── privateHeaderB1.h <br />
│   ├── privateHeaderB2.h <br />
│   ├── sourceB.cpp <br />
│   └── submodule <br />
│       ├── submodule.cpp <br />
│       └── submodule.h <br />
├── libC <br />
│   ├── include <br />
│   │   └── libC <br />
│   │       └── sourceC.h <br />
│   ├── privateHeaderC1.h <br />
│   ├── privateHeaderC2.h <br />
│   └── sourceC.cpp <br />
├── libD <br />
│   └── include <br />
│       └── libD <br />
│           └── sourceD.h <br />
└── main.cpp <br />
