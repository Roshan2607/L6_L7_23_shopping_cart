LAB 6 - CODE AND BRANCH COVERAGE
Repository: L6_L7_23_shopping_cart

FILES
- shopping_cart.py: original application; leave unchanged.
- test_shopping_cart.py: original starter tests; leave unchanged.
- CodeCoverageTest_23_shopping_cart.py: tests for line/code coverage.
- BranchCoverageTest_23_shopping_cart.py: tests for branch coverage.
- screenshots/: save your four terminal screenshots here.

INSTALL
    python -m pip install coverage pytest

STAGE 1 - CODE/LINE COVERAGE
    python -m coverage erase
    python -m coverage run -m pytest CodeCoverageTest_23_shopping_cart.py
    python -m coverage report -m

STAGE 2 - BRANCH COVERAGE
    python -m coverage erase
    python -m coverage run --branch -m pytest BranchCoverageTest_23_shopping_cart.py
    python -m coverage report -m

SCREENSHOTS TO ADD
- screenshots/code_coverage_test.png
- screenshots/code_coverage_report.png
- screenshots/branch_coverage_test.png
- screenshots/branch_coverage_report.png

GIT COMMITS
First commit after adding code coverage test + its two screenshots:
    git add CodeCoverageTest_23_shopping_cart.py screenshots/code_coverage_test.png screenshots/code_coverage_report.png
    git commit -m "Add code coverage test cases"

Second commit after adding branch coverage test + its two screenshots:
    git add BranchCoverageTest_23_shopping_cart.py screenshots/branch_coverage_test.png screenshots/branch_coverage_report.png
    git commit -m "Add branch coverage test cases"

Do not submit example/illustrative screenshots. Capture your actual terminal output.
