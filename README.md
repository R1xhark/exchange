# Exchange Package Unit Test

This Python script is designed to test the functionality of the `exchangeable_value` function in the "Exchange Package." It uses the `unittest` library to perform unit tests on the function and logs the results to a file.

## Prerequisites

Before running the unit tests, make sure you have the following prerequisites:

- Python 3.x installed on your system.
- The `exchange.py` module containing the `exchangeable_value` function.

## Running the Tests

1. Clone or download the Exchange Package repository to your local machine.

2. Navigate to the directory containing the unit test script (`TestExchangeFunctions.py`).

3. Open the terminal or command prompt and run the following command to execute the tests:

```python TestExchangeFunctions.py```

This command will execute the unit tests, and the results will be displayed in the terminal.

## Log Files

The unit test script logs test results to log files located in the `TestLogs` directory. Each log file is named `exchange_test_<timestamp>.log`, where `<timestamp>` represents the date and time when the test was executed. The log files contain information about the test execution, including start and end times, test variants, and whether the tests passed or failed.

## Test Cases

The unit test script includes several test cases with different input parameters and expected output values. These test cases cover various scenarios to ensure the robustness of the `exchangeable_value` function.

## Modifying Tests

If you want to add more test cases or modify existing ones, you can do so by editing the `TestExchangeFunctions.py` script. Simply update the `inputs` and `output_data` lists with your desired test cases.

## License

This unit test script is provided under the [MIT License](LICENSE).
