# To run
```
cd pyext-myrustlib/
cargo build --release
cd ..
cp pyext-myrustlib/target/release/libmyrustlib.so myrustlib.so
pytest -- doubles.py
```
