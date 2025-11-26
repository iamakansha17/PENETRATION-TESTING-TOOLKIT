# PENETRATION-TESTING-TOOLKIT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: AKANSHA JADHAV

*INTERN ID*: CT04DR1398

*DOMAIN*: CYBERSECURITY AND ETHICAL HACKING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH


## # TASK-3: PENETRATION TESTING TOOLKIT

A modular, beginner-friendly penetration testing toolkit with multiple modules:

## Module
#01: Port Scanner
This module uses Python's socket library to attempt TCP connections to a range of ports. If a connection is established (return code 0), the port is considered "OPEN".

#02: Brute Forcer
A brute force tool systematically attempts all possible combinations of characters to find the correct credential. This Python script uses itertools to generate combinations.

## How to Run
        python port_scanner.py
        python brute_forcer.py
                OR
        python toolkit.py *(to link your modules together.)*

----------------------------------------------------------------------------------------------------------------------------------------------------
# 1. Installation & Setup
Ensure you have Python installed on your machine. No external dependencies are required for the basic versions of these scripts as they use standard libraries (socket, itertools, sys).

        $ mkdir codtech_toolkit
        $ cd codtech_toolkit
        $ touch toolkit.py port_scanner.py brute_forcer.py

# 2. Modular Architecture
The toolkit follows a modular design pattern. Each tool is a separate Python module that can be imported into the main driver script.

        port_scanner.py: Handles networking and socket connections.
        brute_forcer.py: Handles logic for combinatorics and credential testing.
        toolkit.py: The central CLI interface that imports the above modules.

# 3. Main Interface Code:
        toolkit.py to link your modules together.

# 4. Usage Instructions:
        Run the toolkit from your terminal:
        user@kali:~/codtech_toolkit$ python3 toolkit.py

*Select option 1 to scan a local IP (e.g., 127.0.0.1) or option 2 to test the brute force algorithm.*



