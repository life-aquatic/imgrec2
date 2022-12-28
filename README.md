# imgrec2
A utility that analyzes a photo of a table covered with coins, and calculates the total value of all coins, based on the sample coin images. 

Compiled standalone executable for Windows: https://github.com/life-aquatic/imgrec2/tree/master/Releases

Usage: 
```
imgrec.exe path_to_config_file path_to_input_image path_to_output_image
```

Example: 
```
imgrec.exe c:\temp\imgrec\config.json c:\temp\imgrec\table.png c:\temp\imgrec\filtered_output.png
```


Config.json file specifies the value of each coin type, and where to find sample images for that coin type. 

Example of working config.json and a set of coin sample images: https://github.com/life-aquatic/imgrec2/tree/master/Resources

