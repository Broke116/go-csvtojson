# CSV > JSON converter
The application converts csv files to json formatted files.

CSV file inside the root directory are being tracked and processed concurrently. In addition to the previous version of this project,
multiple CSV file can be processed at the same time.

## Future task
- File converter for any type of a file

# How to build
CSV files should be added to the root directory for conversion
```
$ go build -o converter.exe
```