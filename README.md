```cpp
// =======================================================
//  ZIANG WANG
// =======================================================
//
// Focus:
//   • C++ system design
//   • Backend development (Node.js, Java)
//
// Interests:
//   • Performance-oriented systems
//   • Ai Infra
//   • Quant dev
//

#include <string>
#include <vector>

namespace profile {

    constexpr const char* NAME  = "Ziang Wang";
    constexpr const char* ROLE  = "Software Engineer";
    constexpr const char* STACK = "C++, Node.js, Java";

}

// -------------------------------------------------------
// EXPERIENCE
// -------------------------------------------------------

namespace experience {

    struct Role {
        std::string title;
        std::string company;
    };

    const Role ERICSSON = {
        "Software Developer Co-Op",
        "Ericsson"
    };

    const Role FUEL_TRANSPORT = {
        "Developer Intern",
        "Fuel Transport"
    };

}

// -------------------------------------------------------
// AWARDS & COMPETITIONS
// -------------------------------------------------------

namespace awards {

    const std::vector<std::string> LIST = {
        "LeetCode Weekly Contests — Top 5%",
        "ICPC NENA (2025) — 5th in Quebec, 21st in Region",
        "Canadian Open Mathematics Challenge — QC Bronze & Silver (2019, 2021)"
    };

}

```

