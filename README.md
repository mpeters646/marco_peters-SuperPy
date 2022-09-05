# Readme project Assignment SuperPy

A large supermarket chain has asked you to write a command-line tool that is able to keep track of their inventory: they want to call it SuperPy. The core functionality is about keeping track and producing reports on various kinds of data:

- Which products the supermarket offers;
- How many of each type of product the supermarket holds currently;
- How much each product was bought for, and what its expiry date is;
- How much each product was sold for or if it expired, the fact that it did;

All data must be saved in CSV files.

## Requirements

### Code

Be creative with your implementation! We intentionally keep the specification open to encourage you to be creative with this project. However, to obtain a passing grade, you will at least need to satisfy the following requirements:

- Well-structured and documented code, including:
  - Clear and effective variable and function names;
  - Use of comments where the code does not speak for itself;
  - Clear and effective separation of code into separate functions and possibly files.
- Use of modules to the extent that it shows you were able to independently read and understand the documentation, and apply the techniques within:

  - **csv**
  - **argparse**
  - **datetime**, including in particular the `date` object, `strftime`
    and `strptime` functions and datetime arithmetic using `timedelta`.

- Use of external text files (CSV) to read and write data.
- A well-structured and user friendly command-line interface with clear descriptions of each argument in the `--help` section.
- A text file containing a usage guide aimed with peers as the target audience. The usage guide should include plenty of examples.
- The application must support:
  - Setting and advancing the date that the application perceives as 'today';
  - Recording the buying and selling of products on certain dates;
  - Reporting revenue and profit over specified time periods;
  - Exporting selections of data to CSV files;
  - Two other additional non-trivial features of your choice, for example:
    - The use of an external module Rich to improve the application.
    - The ability to import/export reports from/to formats other than CSV (in addition to CSV)
    - The ability to visualize some statistics using Matplotlib
    - Another feature that you thought of.

### Report

Please include a short, 300-word report that highlights three technical elements of your implementation that you find notable, explain what problem they solve and why you chose to implement it in this way. Include this in your repository as a `report.md` file.

- You may use Markdown for your report, but it is not required.
- To assist your explanation you may use code snippets.
