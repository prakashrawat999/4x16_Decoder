# 4x16_Decoder implement using 3x8_Decoder

## Abstract:
The decoder is a combinational circuit with n input lines and 2n maximum output lines. Depending on the input combination, one of these outputs will be high when the decoder is enabled. Therefore, a particular code is detected by a decoder. In electronic circuits, it is used to convert instructions into CPU control signals. In logical circuits and data transfer, they are mainly used. 

Let us use 3 to 8 decoders to implement 4 to 16 decoders. In 3 to 8 Decoder, there are three inputs, A2, A1, and A0, and eight outputs, Y7 to Y0. As opposed to 4 to 16 Decoder, which has four inputs A3, A2, A1 & A0 and sixteen outputs Y15 to Y0. Two 3 to 8 decoders required to implement 4 to 16 decoders. 
m2 = 16 m1 = 8 
Number of lower order decoders required 
= m2/m1   16/8 = 2 

## Circuit Diagram using ESIM Tool:
Implement a 4 to 16 decoder with 3 to 8 decoders in this section. In 3 to 8 Decoder, there are three inputs, Out2, Out1 and Out0, and eight outputs, D7 to D0. In contrast, the 4 to 16 Decoder has four inputs: Out3, Out2, Out1 & Out0, and sixteen outputs: D15 to D0.

To each 3 to 8 decoder, Out2, Out3 & Out4 are applied in parallel. Enable, E of lower 3 to 8 decoder is connected to complement of input, Out1, to get outputs, D7 to D0. This is the lower eight of the min terms. As a result of a direct connection between Out1 and Enable, E of the upper 3 to 8 decoder, outputs D15 to D8 are obtained. There are eight higher minimum terms in this list.

![image](https://user-images.githubusercontent.com/87818153/194718888-319e6ce2-90f6-42f0-a57c-48cae882376e.png)

## Plotting:
![image](https://user-images.githubusercontent.com/87818153/194718959-a7922b49-5907-416f-a52d-06488ec6aa0d.png)
![image](https://user-images.githubusercontent.com/87818153/194719028-9ca695fe-aca9-4030-a95b-df80d9274e73.png)
![image](https://user-images.githubusercontent.com/87818153/194719052-c862376a-8ebc-4821-ba48-06316a25d469.png)

## References:
```
https://www.youtube.com/watch?v=iM4J YA1il0Y 
https://www.tutorialspoint.com/digital_circuits/digital_circuits_decoders.htm 
https://www.javatpoint.com/decoder-digital-electronics#:~:text=The%203%20to%20 8%20line,an%20enable%20input%20'E
http://vlsigyan.com/verilog-code-of-decoder-3-to-8-decoder-verilog-code/
https://www.elprocus.com/designing-4-to-16-decoder-using-3-to-8-decoder/
https://www.youtube.com/watch?v=7rhQwNeEc4o
https://www.elprocus.com/designing-4-to-16-decoder-using-3-to-8-decoder/#:~:text=4%20to%2016%20decoder%20circuit%20is%20obtained%20from%20two%203,3%20to%208%20decoder%20circuit.
https://programmerbay.com/construct-3-to-8-decoder-with-truth-table-and-logic-gates/
```

