# Message Encoder

A simple message encoder/decoder built in node.js. 



### Description

The purpose of this project is to analyze some cryptography fundamentals, in addition to the use of node.js modules.



### How to use

Install node.js and run the follow command lines:



To encode a message:

~~~javascript
$ node super-encoder.js encode
<your message>
~~~

To decode a message:

~~~~javascript
$ node super-encoder.js decode
<your encoded message>
~~~~



### Examples

Encoding a message

~~~~javascript
$ node super-encoder.js encode
//Enter the message you would like to encrypt...
$ Hello World
//zwwp$ 0wczh
~~~~

Decoding a message

~~~~javascript
$ node super-encoder.js decode
//Enter the message you would like to encrypt...
$ zwwp$ 0wczh
//Hello World
~~~~

