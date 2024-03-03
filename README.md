# Triple-Doubles

triple_doubles(filename_in, filename_out) consumes two strings filename_in, corresponding to the non-empty CSV file created in the above format and a string filename_out that is the output file name, returns None and writes to the file name in filename_out each player's name and the number of triple-doubles they have accumulated in the following CSV format:

Name1,num_triple_doubles
Name2,num_triple_doubles
...
where each line ends in a newline character (including the last) and the names are in alphabetical order.
