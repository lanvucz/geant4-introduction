### Compile code
mkdir build_w
cd build_w
cmake ../
cmake --build . --config Release
.\Release\task4.exe macros/basic.mac > basic.log

### Analyzing result
cp scripts/* build_w
cd build_w
#### root analysis
root calorimeter_histogram.C
#### csv analysis
python calorimeter_histogram.py


