# spoken_to_written
his is a Python module which can that can convert a paragraph of spoken english to written english.

For example, "two dollars" should be converted to $2. Abbreviations spoken as "C M" or "Triple A" should be written as "CM" and "AAA" respectively.

# Install

Please ensure that you have updated pip3 to the latest version before installing spoken2written.

You can install the module using Python Package Index using the below command.

>>python3 setup.py install

# Usage
 >>python3
 >>from spoken2written import sp2wr
 >>sp2wr.convert_sp_to_wr()
 >>
 [IN]:Enter Your paragraph of spoken english:
 
 Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 A M. I always come home after 7 P M. I earn hundred 		dollars per day. My contact number contains double 5, quadruple 8, single 9 and triple 4. Recently, My weight got double 	 the weight of my friend whom I call C M. 
 
 [OUT]:The input Spoken English Paragraph: 
 
 " Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 A M. I always come home after 7 P M. I earn hundred 	  dollars per day. My contact number contains double 5, quadruple 8, single 9 and triple 4. Recently, My weight got double    	       the weight of my friend whom I call C M. "
 	
  Converted Written English Paragraph: 
  
  " Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 AM. I always come home after 7 PM. I earn $100 per 	    day. My contact number contains 55, 8888, 9 and 444. Recently, My weight got double the weight of my friend whom I      	       call CM. "



# Possible of future functionalities that can be covered in the future versions :

If the paragraph contains a money figure e.g. two million three thousand nine hundred and eighty-four then we may convert it to numbers as 2003984.

Handling of both American number system and Indian number system e.g. million, lakhs.

Handling of Dates e.g. Today's Date is twenty-eight October two thousand twenty as Today's Date is 28-10-2020/2020-10-28.

Handling of Punctuation.

Handling of proper spaces after one sentance.

Please, Feel free to connect if you have some ideas
