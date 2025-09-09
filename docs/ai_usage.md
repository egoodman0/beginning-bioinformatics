# AI Use Log

Tool/model & version: Used exclusively Gemini 

Prompt: How do I insert an item at index 1 in the list?
Given code: fruits.insert(1, 'grape')
What I changed before committing: I changed grape to banana 

Prompt: If I have the text file imported into colab, how would I return only the even numbers?
Given code:
  even_numbers = [n for n in all_numbers if n % 2 == 0]
  print(even_numbers)
What I changed before committing: changed to  
  if number % 2 != 0:
  total_sum += number

Prompt: If I have the text file imported into colab, how would I return only the even lines of text?
Given code:
  even_lines = [line.strip() for index, line in enumerate(lines) if index % 2 == 0]
What I changed before committing: I didn't change anything 

Prompt: How to loop over a file, getting words one at a time
Given code: 
  for line in file:
  words = line.split()
What I changed before committing:
  line=data.read()
  for word in line.split():

A lot of the code was autofilled from the gemini that is embedded. I did ask for a specific prompt or change anything other than the name of a file or dataset. It also caught several syntax mistakes and instructed me on how to fix them. 
