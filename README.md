ailun
===
Creates launcher for AppImage apps. One-script solution.

# Prepare

Go to ailun directory:
```bash
cd ./path/to/ailun
```

Allow the script to be executed:
```bash
chmod +x ./ailun
```

# Test

Create Launcher for sample app:
```bash
./ailun \
   ~/my/space/for/spare/software/myprogram/MyProgram-1.0.0.AppImage \
   MyProgram \
   ~/my/space/for/spare/software/myprogram/MyProgramIcon.svg
```

# Install

```bash
cd ./path/to/ailun
echo "export PATH=`pwd`:\$PATH" >> ~/.bashrc
```

# After installation

```bash
cd ~/my/space/for/spare/software/myprogram
ailun ./MyProgram-1.0.0.AppImage MyProgram MyProgramIcon.svg
```
