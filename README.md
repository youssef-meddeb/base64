1. Copy target/Base64.class in your localhost
2. check if java 8 is installed : java -version
3. to encode execute  : java Base64 -e filePathForFileToBeEncoded EncodedFilePath
to decode you should  use : java Base64 -d EncodedFilePath DecodedFilePath

if you have an older version of Java, you can recompile Base64.java : javac Base64.java
