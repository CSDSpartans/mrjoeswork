#   This reads and prints the whole document.
#           It does not prt a blank line after each line of the file

name_of_mydocument = 'mydocument.txt'
file_input = open(name_of_mydocument, 'r')     #open file for reading

line = file_input.readline()
line = file_input.readline()
line = file_input.readline()

line = file_input.readline()

line_counter = 0
stanza_counter = 1

while line != '':                      # while not end of file

    if line == '\n':
      stanza_counter += 1
      print ()
    else:
      line_counter += 1
      print(line_counter, line, end = '')              # don't print another new line
    line = file_input.readline()
    
print ()
print ()
print ("The number of stanzas is ",  stanza_counter)

file_input.close()
