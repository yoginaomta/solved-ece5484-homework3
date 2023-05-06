Download Link: https://assignmentchef.com/product/solved-ece5484-homework3
<br>
<ol>

 <li>How many bits are required to address a 4M × 16 main memory if

  <ol>

   <li>Main memory is byte-addressable?</li>

   <li>Main memory is word-addressable? (For part b, assume a 16-bit word.)</li>

  </ol></li>

 <li>You want to use 256 x 8 RAM chips to provide a memory capacity of 4096 bytes.

  <ol>

   <li>How many chips will you need?</li>

   <li>How many bits will each address contain?</li>

   <li>How many address lines must go to each chip?</li>

   <li>How many address lines must be decoded for the chip select inputs? In other words, specify the size of the decoder.</li>

  </ol></li>

 <li>A digital computer has a memory unit with 40 bits per word. The instruction set consists of 165 different operations. All instructions have an operation code part (opcode) and an address part (allowing for only one address). Each instruction is stored in one word of memory.

  <ol>

   <li>How many bits are needed for the opcode?</li>

   <li>How many bits are left for the address part of the instruction?</li>

   <li>What is the maximum allowable size for memory?</li>

  </ol></li>

</ol>

<ol>

 <li>What is the largest unsigned binary number that can be accommodated in one word of memory?</li>

</ol>

<ol start="4">

 <li>Section 4.10 of the text provides an example of the execution of a simple MARIE program. For this problem, you are to complete a similar example for a different program. In particular, for the MARIE program given below, you are to complete the equivalent of Figure 4.14, but for the program below. You do not need to show how the “Halt” instruction is executed. Specify values in PC, IR, MAR, MBR, and AC in hexadecimal. A template for your answer is provided as a Microsoft Word file that is included with this assignment on Canvas. You are to incorporate your answer for this problem into your submission for the homework assignment so that you submit only one PDF file for the entire assignment.</li>

</ol>

The program is as follows. Note that this table is the equivalent of Table 4.3 in the textbook, only for a different program.

<table width="591">

 <tbody>

  <tr>

   <td width="104"><strong>Hex</strong><strong>Address</strong></td>

   <td width="153"><strong>Instruction</strong></td>

   <td width="196"><strong>Binary Contents of</strong><strong>Memory Address</strong></td>

   <td width="138"><strong>Hex Contents of Memory</strong></td>

  </tr>

  <tr>

   <td width="104">100</td>

   <td width="153">Load 105</td>

   <td width="196">0001 0001 0000 0101</td>

   <td width="138">1105</td>

  </tr>

  <tr>

   <td width="104">101</td>

   <td width="153">Subt 104</td>

   <td width="196">0100 0001 0000 0100</td>

   <td width="138">4104</td>

  </tr>

  <tr>

   <td width="104">102</td>

   <td width="153">Store 104</td>

   <td width="196">0010 0001 0000 0100</td>

   <td width="138">2104</td>

  </tr>

  <tr>

   <td width="104">103</td>

   <td width="153">Halt</td>

   <td width="196">0111 0000 0000 0000</td>

   <td width="138">7000</td>

  </tr>

  <tr>

   <td width="104">104</td>

   <td width="153">00A3</td>

   <td width="196">0000 0000 1010 0011</td>

   <td width="138">00A3</td>

  </tr>

  <tr>

   <td width="104">105</td>

   <td width="153">00F3</td>

   <td width="196">0000 0000 1111 0011</td>

   <td width="138">00F3</td>

  </tr>

  <tr>

   <td colspan="4" width="591"></td>

  </tr>

 </tbody>

</table>

<ol start="5">

 <li><strong><sub>Scavenger Hunt: </sub></strong>Two pioneers of early computers and computer organization were Howard H. Aiken and John von Neumann. Answer the questions below regarding Aiken and von Neumann. <em><sub>Cite sources</sub></em></li>

</ol>

<em>used for your answers.</em>

<ol>

 <li>Is Aiken or is von Neumann associated with the so-called Princeton architecture?</li>

 <li>Is Aiken or is von Neumann associated with the so-called Harvard architecture?</li>

 <li>In your own words, what is the key feature of a Princeton architecture computer compared to the Harvard architecture?</li>

 <li>Does the MARIE architecture owe more to Aiken or von Neumann? In your own words, briefly justify your answer.</li>

</ol>