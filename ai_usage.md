The AI I used for this project was Gemini. First of all, I gave it the file with the project so it could understand
the way the filter option is passed in the command line and how it needs to implement the functions properly. For the
parse_condition it used the sscanf function to parse the input, if it parsed all 3 fields succesfully it returns 1, otherwise it returns 0.
For the match_condition function, first it checked to see what field we are in, afterwards with multiple conditional clauses it determined the operand
op and it returns the result by making a comparison with the required value.
