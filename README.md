# OpenCV Data format

## Vec, Point, Rec, etc...
There is a various range of type in openCV with a specific name representing a code. 
Here is the explanation. Each of them are composed as follow : Type + Tuple Size  + Encoding

Ex: Vec3d = Vector of tuple of 3 elements encoded as double

| Letter | Encoding |
| ------ | -------- |
| b      | uchar    |
| d      | double   |
| f      | float    |
| i      | int      |
| s      | short    |
| w      | ushort   |
| I 	 | int64 	|

## CV_XSCX
We can find data type for image encoding. There are splited in several parts as follow :
CV_ + size + Sign + C + n channels 

| Letter | Sign     |
| ------ | -------- |
| U      | Unsigned |
| S      | Signed   |
| F 	 | Floating |

Ex: CV_8UC3 = Matrix of 3 channels encoded on 8 bit, unsigned

The size are limited to these formats : **8**, **16**, **32** and **64**

The number of channel is unlimited however a number between **1 to 4** (included) is preferred. 


