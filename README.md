# bash

## produceOutput

produce the output of a list of tests.

A sample run of `produceOutputs` would be as follows:
`./produceOutputs suite.txt ./myprogram`

The script will then run `./myprogram` three times, once for each test specified in `suite.txt`:
• The first time, it will run `./myprogram` with command line arguments provided to the program from `test1.args`.
The results, captured from standard output, will be stored in `test1.out`.
• The second time, it will run `./myprogram` with command line arguments provided to the program from `test2.args`.
The results, captured from standard output, will be stored in `test2.out`.
• The third time, it will run `./myprogram` with command line arguments provided to the program from
`reallyBigTest.args`. The results, captured from standard output, will be stored in `reallyBigTest.out`.

## runSuite

run a list of tests and give the feedback for each of case.

A sample run of `runSuite` would be as follows:
`./runSuite suite.txt ./myprogram`

The script will then run `./myprogram` three times, once for each test specified in `suite.txt`:
• The first time, it will run `./myprogram` with command line arguments provided to the program from `test1.args`.
The results, captured from standard output, will be compared with the contents of `test1.out`.
• The second time, it will run `./myprogram` with command line arguments provided to the program from `test2.args`.
The results, captured from standard output, will be compared with the contents of `test2.out`.
• The third time, it will run `./myprogram` with command line arguments provided to the program from
`reallyBigTest.args`. The results, captured from standard output, will be compared with the contents of
`reallyBigTest.out`.
