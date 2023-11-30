Title: Command Line
Description: Displays the runner command-line options.
Order: 4
---
**TestCentric** is invoked from the command line as follows:

```
TESTCENTRIC [inputfiles] [options]
```

For example,

```
TESTCENTRIC mytests.dll
TESTCENTRIC onetest.dll anothertest.dll --run
TESTCENTRIC myproject.nunit
```

If **TestCentric** is started without any files specified, it automatically loads the most recently loaded test file. Alternatively, you may specify one or more assemblies or supported project types. 

**NOTE:** The types of projects supported depends on the project loader extensions that are installed. Without any extensions installed, only assemblies (`.dll` or `.exe`) are permitted.

### Options Supported

Option            | Action
------------------|--------
--config=CONFIG   | Specify the CONFIG to use for any project files loaded
--noload          | Suppress loading of the most recent test file.
--run             | Automatically run the loaded tests.
--unattended      | In conjunction with --run, causes the GUI to exit immediately after running
--full-gui        | Use the standard (full) GUI interface.
--mini-gui        | Use the mini-GUI interface.
--x86             | Run tests in an X86 process on 64-bit systems.
--agents=NUMBER   | Specify the maximum NUMBER of test assembly agents to run at one time. If not specified, there is no limit.
--work=PATH       | PATH to directory used for any output files by default.
--trace=LEVEL     | Set internal trace level. Valid values are `Off`, `Error`, `Warning`, `Info` or `Debug`. `Verbose` is a synonym for `Debug`.
--param=PARAM     | Specify a parameter to pass to the tests. PARAM is in the format KEY=VALUE.
--help            | Display the help message and exit.
