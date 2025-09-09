# File Modes in Python
## Read ("r")
-Opens an existing file for reading.
-❌ If the file does not exist, you getFileNotFoundError.
-✅ If it exists, you can read it.
-🚫 Does not create a new file.

## Write ("w")
-Opens a file for writing.
-✅ If the file exists, it truncates (deletes) its content.
-✅ If the file does not exist, it creates a new one.
-🚫 Be cautious: existing content will be lost

## Append ("a")
-Opens a file for appending.
-✅ If the file exists, new data is added to the end.
-✅ If the file does not exist, it creates a new one.
-🚫 Existing content remains intact
.

## Read & Write ("r+")
-Opens an existing file for both reading and writing.
-❌ If the file does not exist, you get FileNotFoundError.
-✅ If it exists, you can read and write.
-🚫 Does not create a new file
.

## Write & Read ("w+")
-Opens a file for both writing and reading.
-✅ If the file exists, it truncates (deletes) its content.
-✅ If the file does not exist, it creates a new one.
-🚫 Be cautious: existing content will be lost

## Append & Read ("a+")
-Opens a file for both appending and reading.
-✅ If the file exists, new data is added to the end.
-✅ If the file does not exist, it creates a new one.
-🚫 Existing content remains intact
