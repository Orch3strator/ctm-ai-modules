# ZZM7ZIP

Plug-In Name: ZZM 7Zip

Plug-In ID: ZZM7ZIP

Description: 7-Zip is a file archiver with a high compression ratio.

Operations:

- Add files to archive
- Benchmark
- Calculate hash
- Delete files from archive
- Extract without path
- Extract with full path
- Integrity Test
- List content
- Rename file
- Remove Archive

Runtime Parameters Attributes:

- Archive CRC Hash
- Archive MD5 Hash

Source: [**ZZM7ZIP.ctmai**](../src/7Zip/ZZM7ZIP.ctmai)

## Screenmshots

7-Zip options in Control-M Job

![ZZM File & Data Compression Options](images/zzm-7zip.png)


### Example

If the filesize if greater than 4096 Bytes, add the file to an archive. Using the "File Watcher" capability of the [File Transfer](../src/7Zip/ZZM7-Zip.json) job type.
Check the "OnDo" Actions to better understand the process logic.


![ZZM File & Data Compression Workflow](images/zzm-7zip-workflow.png)
