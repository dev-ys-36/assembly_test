# assembly_test
=> c++
```c++
#include <iostream>

int main()
{
    std::cout << "Hello World!\n";

    return 0;
}
```
=> disassembly
```assembly
00007FF7873B22C0  push        rbp  
00007FF7873B22C2  push        rdi  
00007FF7873B22C3  sub         rsp,0E8h  
00007FF7873B22CA  lea         rbp,[rsp+20h]  
00007FF7873B22CF  lea         rcx,[__92AA849F_assemblyTest@cpp (07FF7873C3066h)]  
00007FF7873B22D6  call        __CheckForDebuggerJustMyCode (07FF7873B13CFh)  
00007FF7873B22DB  lea         rdx,[string "Hello World!\n" (07FF7873BAC28h)]  
00007FF7873B22E2  mov         rcx,qword ptr [__imp_std::cout (07FF7873C1198h)]  
00007FF7873B22E9  call        std::operator<<<std::char_traits<char> > (07FF7873B1087h)  
00007FF7873B22EE  xor         eax,eax  
00007FF7873B22F0  lea         rsp,[rbp+0C8h]  
00007FF7873B22F7  pop         rdi  
00007FF7873B22F8  pop         rbp  
00007FF7873B22F9  ret  
```
