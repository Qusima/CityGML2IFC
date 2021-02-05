**Note:** This is a fork of https://github.com/nsalheb/CityGML2IFC
## Changes made
- Fixed non-defined `loop_string2` values.
- Added IFC units:
```    
"\n#120 = IFCSIUNIT (*, .AREAUNIT., $, .SQUARE_METRE.);"
"\n#121 = IFCSIUNIT (*, .LENGTHUNIT., $, .METRE.);"
"\n#122 = IFCSIUNIT (*, .VOLUMEUNIT., $, .CUBIC_METRE.);"
"\n#119 = IFCUNITASSIGNMENT ((#120, #121, #122));"
```
- Added custom  input/output filename arguments.

## Program Description
The main implementation part consists of a program named `CityGML2IFC.py` it is a script file written in Python 3. 
When compiled the program will convert a source file in CityGML to a destination file in IFC.

## Usage
*Note:* Python3 required
```
CityGML to IFC converter.

Usage:
  CityGML2IFC.py -i <ifile> -o <ofile>

Options:
  -h --help     Show this screen.
  -i --input    Input GML filename.
  -o --output   Output IFC filename.
```

Before running install dependency modules: `python3 -m pip install -r requirements.txt`

Example usage: `python CityGML2IFC.py -i Source.gml -o Output.ifc`
