## <img src='./logo.jpg' width='40' height='40'>tFileDigester

### Overview
Checksum of a file, obtained with the Java MessageDigest.

With a Sun JRE 6, theses digest method are supported :
- MD2
- MD5
- SHA-1
- SHA-256
- SHA-384
- SHA-512

With other JRE versions, you can get a runtime "NoSuchAlgorithmException".
### Images




#### Release Notes

##### 0.1 - 2009-03-27 16:02:36
First release.

You can choose the size of the input buffer (usefull to avoid memory exceptions on very large files).
##### 0.2 - 2009-03-30 13:19:21
A renamed output column :
- digest becomes digestHexaString (the hexa string does not begins with "0x" anymore)

Two new output columns :
- filename
- digestBytes (byte array containing the native output of digest method, before the transformation in an hexadecimal String)
##### 0.3 - 2009-05-06 10:46:21
- Family information added for 3.1.0 compatibility
- French translation of the component

This version is NOT compatible anymore with 3.0.X versions of Talend Open Studio
### Compatible
 -  3.0 (obsolete)
 -   3.1 (obsolete)
 -   3.2 (obsolete)