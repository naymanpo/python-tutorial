python list គឺជា compound data type
list ផ្ទុក item ជាច្រើនខណ្ឌចែកដោយ (,) នៅចន្លោះ ([])
list ដូច array ក្នុង c តែ item ក្នុង list អាចមានប្រភេទទិន្នន័យខុសគ្នា


តម្លៃដែលរក្សាទុកក្នុង List អាច access ដោយប្រើ slice operator ([] និង [:])
ដែលចាប់ផ្តើមដោយ ០ និងបញ្ចប់ដោយ -1


(+) សញ្ញា list concatenation operator, និង asterisk (*) គឺ repetition operator
#!/usr/bin/python

list = [ 'abcd', 786 , 2.23, 'john', 70.2 ]
tinylist = [123, 'john']

print list          # Prints complete list
print list[0]       # Prints first element of the list
print list[1:3]     # Prints elements starting from 2nd till 3rd 
print list[2:]      # Prints elements starting from 3rd element
print tinylist * 2  # Prints list two times
print list + tinylist # Prints concatenated lists