# read_comments_as_HDL
 using "AND" gate logic to test "read_comments_as_HDL" synthesis directive 


 A Verilog HDL synthesis directive that directs Analysis & Synthesis to perform logic synthesis on portions of the design code that are in comments. By commenting out code in the design and using this synthesis directive, you can direct Analysis & Synthesis to perform logic synthesis on code that is specific to logic synthesis, while also ensuring that the code does not affect design simulation.

To use the read_comments_as_HDL synthesis directive, you can specify the read_comments_as_HDL synthesis directive with the on keyword in a comment located immediately before the comments you want Analysis & Synthesis to process, and specify the read_comments_as_HDL synthesis directive with the off keyword in a comment located immediately after the comments you want Analysis & Synthesis to process. In the comment, precede the synthesis directive with the synthesis keyword.
