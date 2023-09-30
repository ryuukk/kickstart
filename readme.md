- to run all the tests

    `dub test`

- to run a specific test
    `dub test -- -i "test1"`

    ```
    ✗ mytests test1
        core.exception.AssertError thrown from source\mytests.d on line 6: fail
        --- Stack trace ---
        0x00007FF6F127D4D7 in d_throwc
        0x00007FF6F1284B4A in d_unittest_msg
        0x00007FF6F11D6E48 in mytests.__unittest_L5_C1 at C:\tmp\kickstart\source\mytests.d(6)
    ```

- to run the program
    `dub run`

You can't have tests in the main module
