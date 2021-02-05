# avro-tools
Avro tool needed to convert AVRO IDL (.avdl) files into .avsc or .avpr

## Get the Jar file
run this in the terminal
``` bash
cat avro-tools-1.9.2.jar_1 avro-tools-1.9.2.jar_2 > avro-tools-1.9.2.jar
```

## Usage
1. Generate `.avsc` file as following:
``` bash
java -jar avro-tools-1.9.2.jar idl2schemata <path to .avdl> <path to .avsc>
```

1. Generate `.avpr` file as following:
``` bash
java -jar avro-tools-1.9.2.jar idl <path to .avdl> <path to .avpr>
```
