## BCD to 7 segment display decoder :

BCD is a binary code, it stands for binary coded decimal , each decimal digit is encoded into 4-bit binary representation:

0 ==>  0000

1 ==>  0001

2 ==>  0100

3 ==>  0011

4 ==>  0100

5 ==>  0101

6 ==>  0110

7 ==>  0111

8 ==>  1000

9 ==>  1001


what about 7-segment display ?

![7segment!](BCD_to_7segment_decoder/Seven-segment-display.png "7segment")

![7segment display!](BCD_to_7segment_decoder/7segment.jpg "7segment display")

it is an electronic display device often used to display digits in digital counters , clock ...etc.

here we create a behavioral architecture for this decoder (i.e we build the system in terms of its function without specifying the gates and interconnection between them:

!Decoder!](BCD_to_7segment_decoder/decoder.png "Decoder")
