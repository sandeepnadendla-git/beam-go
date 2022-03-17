# BEAM-GO
## Sandeep Nadendla


### Steps followed to build this

1. Install go using link [https://go.dev](https://go.dev/)
2. Open poweshell in administation mode
3. Check go version using command
 ```go version```
4. Get Apache Beam Go SDK using command
```$ go get -u github.com/apache/beam/sdks/v2/go/pkg/beam```
5. Create beam.go directory
``` mkdir beam.go```
6. Go to directory
```cd beam.go```
6. Get a wordcount.go from examples
7. create sample.txt and place some text
8. install package of beam filesystem using
```go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0```
9. Buid wordcount.go 
```go build wordcount.go```
10. Execute wordcount passing sample.txt
```.\wordcount --input sample.txt --output out1.txt```
11. check the outputfile
```Get-Content out1.txt```