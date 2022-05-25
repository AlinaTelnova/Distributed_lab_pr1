# Distributed_lab_pr1
Blockchain and Decentralized Technologies. Practical task №1

The code is created in Python

The program finds the keyspace of certain bit sequences, generates corresponding keys, then searchers for them using brute force and displays the amount of time spent

The program uses three modules: math, random and time

We choice function "random.randint" from module random to generate keys in a given range

Keys are generated in Hexadecimal system

Python displays generated keys in a decimal system, regardless of the range numeral system. So we use function "hex" additionally after generation to display the hexadecimal keys

The range of values is determined by calculating "1 byte corresponds to two symbols of the hexadecimal system"

Function "time.perf_counter_ns()" from module time returns the value in nanoseconds, therefore We divide the value by a million and got milliseconds
