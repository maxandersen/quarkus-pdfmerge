# pdfmerge

jbang'ed version of https://github.com/geoand/quarkus-pdfmerge

## Run

```bash
./jbang pdfmerge src/MergeCommand.java --input=/location/f1.pdf --input=/location/f2.pdf
```

## Native

Install GraalVM first.

```bash
./jbang --native src/MergeCommand.java --input=/location/f1.pdf --input=/location/f2.pdf
```

## Install

```
./jbang app install --native pdfmerge
pdfmerge --input=/location/f1.pdf --input=/location/f2.pdf
```

