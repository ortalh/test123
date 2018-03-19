# test123
It doesn’t get much simpler than this: ```cpp #include “argh.h”

int main(int, char* argv[]) { argh::parser cmdl(argv);

if (cmdl[{ "-v", "--verbose" }])
    std::cout << "Verbose, I am.\n";

return EXIT_SUCCESS; } ```  ## Ph
