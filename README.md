Smashing_The_Browser
====================

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f536a6393fc94232961120e7b8efbc8c)](https://www.codacy.com/app/harlamova/Smashing_The_Browser?utm_source=github.com&utm_medium=referral&utm_content=Elisabethar/Smashing_The_Browser&utm_campaign=badger)

Smashing The Browser: From Vulnerability Discovery To Exploit

Part 1: Browser Fuzzing Technology

This part will first introduce a fuzzer framework (StateFuzzer) developed by myself as well as the fuzzing strategies behind it.
Then conclude some effective fuzzing ideas and related vulnerabilities based on results of the fuzzer.

Part 2: Advance Browser Exploitation Techniques

This part will first brief introduce the security model of modern browsers as well as the combat between exploit and mitigation.
Then introduce all kinds of heap management mechanisms and their defects together with some exploit-friendly data structures of Google Chrome and IE 11.
After that, analyze the advance exploit technologies of these two browsers, including two new exploitation techniques, one of which is not limited by sandbox (Demo).
Finally conclude the dilemmas of Address Space Layout Randomization (ASLR), Data Execution Prevention (DEP) and Sandbox.

Part 3: IE 11 0day Exploit Development

After taking one of my IE 11 UAF vulnerabilities from StateFuzzer, I will share the whole exploit developing experience from the vulnerability trigger to arbitrary code execution, together with all related technologies and skills (Demo).

At last, I will bring a special, interesting and undisclosed IE 11 0day (not affected by isolated heap and protected free).
