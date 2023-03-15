# wliu
  <nospam+wliu@talend.com>

## <a href='./components/tFileInputVTDXML/readme.md'><img src='./components/tFileInputVTDXML/logo.jpg' width='40' height='40'> tFileInputVTDXML</a>
 :warning: Compatibility not known

1. use open source project vtd-xml to exact data from the xml file.

2. when the source file is larger than 2G, please tick the checkbox:Source file is larger than 2G(64bit machine). Besides, run it on a 64bit machine.

3. the family of the component is: file/input and xml.

4. you can drag a xml metadata directly to the designer and the component will show up.



<img src='./components/tFileInputVTDXML/sample.jpg'>

## <a href='./components/tWriteHeaderLineToFileWithBOM/readme.md'><img src='./components/tWriteHeaderLineToFileWithBOM/logo.jpg' width='40' height='40'> tWriteHeaderLineToFileWithBOM</a>
 :warning: Compatibility not known

1. the component tWriteHeaderLineToFileWithBOM is used to write a head line to the destination file with BOM
1). make sure the schema of the component is not empty and should be the same with the one in the following output component like tFileOutputDelimited.
2). the value in the parameter:"File Name" in the component should be the same with the one in the following output component like tFileOutputDelimited.
3). Encoding in the component should be the same with the one in the following output component like tFileOutputDelimited.
4). the following output component should have the checkbox:"append" ticked.

2. It is required for the bug:14305



<img src='./components/tWriteHeaderLineToFileWithBOM/sample.jpg'>
