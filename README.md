# ll_e05

```bash
cmake -H. -B_builds -DCMAKE_EXPORT_COMPILE_COMMANDS=ON
run-clang-tidy.py -header-filter='.*' -checks='-*,*' -p _builds/
cmake --build _builds/
./_builds/ll_e05
```
