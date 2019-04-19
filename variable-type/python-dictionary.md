python dictionary គឺ hash table type.
វាប្រើ Key-pair-value
key អាចជាប្រភេទទិន្នណាក៏ដោយតែគេនិយមប្រើ លេខ និង string
value នៃ items នីមួយអាចជា Object ណាមួយ ឬ object ដែលមានប្រភេទខុសគ្នាក៏បាន

#!/usr/bin/python

dict = {}
dict['one'] = "This is one"
dict[2]     = "This is two"

tinydict = {'name': 'john','code':6734, 'dept': 'sales'}


print dict['one']       # Prints value for 'one' key
print dict[2]           # Prints value for 2 key
print tinydict          # Prints complete dictionary
print tinydict.keys()   # Prints all the keys
print tinydict.values() # Prints all the values