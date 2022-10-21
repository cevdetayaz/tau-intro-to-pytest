### Intro to Pytest
Pytest is a testing framework for Python. It allows you to write tests. It also allows you to run them, and view the results. It is a very powerful tool, and is used by many Python projects.

### Installation and Setup
pytest requires: Python 3.7+ or PyPy3.

1. Run the following command in your command line:

        pip install -U pytest

2. Check that you installed the correct version:

        $ pytest --version
        pytest 7.1.3


### Running Tests
Pytest will run all files of the form test_*.py or *_test.py in the current directory and its subdirectories.

I have included a sample test file in this repository. To run it, run the following command in your command line:

        python -m pytest


### Writing Tests
Pytest uses the standard Python assert statement to check for test failures. For example, the following test will fail:

    def test_fail():
        assert (1, 2, 3) == (3, 2, 1)

The test will fail because the two tuples are not equal. The test will pass if the two tuples are equal.

### Resources
- [Pytest Documentation](https://docs.pytest.org/en/stable/)
- [Pytest Tutorial](https://testautomationu.applitools.com/pytest-tutorial/)
