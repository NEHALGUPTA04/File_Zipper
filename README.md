# File_Zipper

Huffman Algorithm is an efficient way for file Compression and Decompression. This program exactly follows huffman algorithm. It reads frequent characters from input file and replace it with shorter binary codeword. The original file can be produced again without loosing any bit.


The huffman algorithm encodes the input as a string of bits. The script included takes a file as input and writes the encoded(compressed) result to a file as well. We cannot write individual bits to a file using node. It would also be unwise to write the sequence of 1's and 0's as characters to a file because each number would be represented by a byte on disk which would inflate the file size rather than compress it. We will have to use a different representation to store the encoded sequence.

Efficient for file compression and decompression. It reads frequent character from input file and replace it with shorter binary codeword. The original file can be produces again without loosing any bit.
