# CMPS 2200 Recitation 7
## Answers

**Name:** Joe Wagner and Luke Albright


Place all written answers from `recitation-07.md` here for easier grading.



- **d.**
  
File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
- f1.txt    |    1340  |        826  | 0.616:1
- alice29.txt    |   1039367     |      676374    | 0.651:1
- asyoulik.txt    |     876253   |   606448  | 0.692:1
- grammar.lsp    |   26047    |     17356   |  0.666:1
- fields.c    |  78050     |    56206      |  0.720:1
- The trend I noticed was that the Huffman cost was always less than the fixed length cost, and there were very similar values in the range of 0.6-0.7 for the cost ratio. This ratio remained similar regardless of the files length/total frequency counts.



- **e.** For an alphabet with all the frequencies equal to each other, the huffman cost would be the frequency shared by each character multiplied by the sum of all the encoding costs for each letter. This is because since the frequency is equal for each letter, we can bring the frequency term out the sum. For other documents, if the total amount of characters was the same then we would expect the same huffman cost. If the documents length changes though, then we would expect the huffman cost to change as the frquency we multiply by is now different. 


