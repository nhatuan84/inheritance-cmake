# inheritance-cmake
inheritance cmake

A demo of: https://kubasejdak.com/modern-cmake-is-like-inheritance

.
├── CMakeLists.txt
├── libA
│   ├── include
│   │   └── libA
│   │       └── sourceA.h
│   ├── privateHeaderA1.h
│   ├── privateHeaderA2.h
│   └── sourceA.cpp
├── libB
│   ├── include
│   │   └── libB
│   │       └── sourceB.h
│   ├── privateHeaderB1.h
│   ├── privateHeaderB2.h
│   ├── sourceB.cpp
│   └── submodule
│       ├── submodule.cpp
│       └── submodule.h
├── libC
│   ├── include
│   │   └── libC
│   │       └── sourceC.h
│   ├── privateHeaderC1.h
│   ├── privateHeaderC2.h
│   └── sourceC.cpp
├── libD
│   └── include
│       └── libD
│           └── sourceD.h
└── main.cpp
