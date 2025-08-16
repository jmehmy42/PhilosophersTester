# Philosopher 42 Tester

This repository provides a tester for the **Philosopher 42** project. It automates the process of running tests on your compiled `philo` executable to ensure compliance with project requirements.

## 🚀 Getting Started

### 1. Clone the Tester

Clone this repository into a directory of your choice:

```bash
git clone https://github.com/jmehmy42/philosopher_42_tester.git
```

### 2. Placement

After cloning, **move the contents** of this tester into your `philos` project directory (the directory containing your compiled `philo` executable):

```bash
mv philosopher_42_tester/* /path/to/your/philos/
```

Alternatively, you can clone directly inside your `philos` directory.

### 3. Change Permissions

Some scripts may require executable permissions. Run:

```bash
chmod +x *.sh
```

This will make all shell scripts in the directory executable.

### 4. Compile Your `philo`

Before running the tester, **compile your `philo` project** so that the `philo` executable is present in the directory.

For example, if you use `Makefile`:

```bash
make
```

Ensure that `philo` is successfully built.

### 5. Run the Tester

Now, you can run the tester. Typically, the main script is named something like `test.sh` or similar:

```bash
./test.sh
```

Or, if there is a different entry point, follow the instructions in the script comments.

## 📝 Notes

- **Do not run the tester in a directory without your compiled `philo` executable.**
- **Make sure your `philo` is compiled and up-to-date before running the tests.**
- The tester may create log files or output result files in the directory.

## 📁 Project Structure

```
philos/
├── philo              # Your compiled executable
├── test.sh            # Entry point for tests
├── ...                # Other tester scripts/files
```

## 🛠️ Troubleshooting

- **Permission Denied:**  
  If you receive permission errors, double-check your permissions with `chmod +x`.
- **Command Not Found:**  
  Make sure you are executing the correct script and that your shell is in the correct directory.

## 🤝 Contributing

Feel free to open issues or pull requests for improvements or bug fixes.

## 📄 License

This repository is provided for educational and testing purposes for the Philosopher 42 project.

---

**Happy Testing!**
