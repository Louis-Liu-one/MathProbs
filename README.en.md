# Math Problems Collection

This project is a collection of mathematical problems, aiming to organize and share various math problems and their solutions. It is suitable for teachers, students, and math enthusiasts to reference and study.

## Project Structure

- **probs/**: Contains TeX files for all mathematical problems; each file corresponds to one math problem.
- **images/**: Contains image resources related to the problems, usually provided in TeX or PDF format.
- **covers/**: Files related to the project cover.
- **makefile**: Script file used to automate building the entire project.
- **preamble.tex**: TeX preamble file defining the basic format and style of the document.
- **problist.tex**: Problem list file, potentially containing an index or summary of all problems.
- **.gitignore**: Git configuration file to prevent certain files from being committed to version control.

## Technologies Used

This project uses [LaTeX](https://www.latex-project.org/) to write mathematical problems and solutions. Image resources are also in TeX or PDF format to ensure high-quality mathematical formula rendering.

## Installation and Building

Please ensure you have installed [TeX Live](https://www.tug.org/texlive/) or another compatible TeX distribution.

### Building the Project

Run the following command in the project directory to build the document:

```bash
make
```

If `make` is not available, you can compile the TeX files manually:

```bash
pdflatex your_file.tex
```

## How to Contribute

New math problems or improvements to existing solutions are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b new-problem`.
3. Add or modify TeX files.
4. Commit your changes: `git commit -m "Add new problem or fix existing problem"`.
5. Push to the branch: `git push origin new-problem`.
6. Create a Pull Request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). For details, please refer to the [License File](LICENSE).

## Contact the Author

If you have any questions or suggestions, please contact the repository maintainer [Louis-Liu-one](https://gitee.com/Louis-Liu-one).

---

This structured repository is ideal for math education scenarios, making it easy to expand and reference.