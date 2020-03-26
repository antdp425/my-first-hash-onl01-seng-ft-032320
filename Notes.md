Similar to arrays

array = ["dog","cat","fox"]
hash = {"key" => "value","another_key" => "another_value"}
(like a dictionary)

keys can be any type of data: string / ints / symbols / etc
only use each key once
duplicating keys overwrites the existing key
each K/V pair is unique

Create Hashes

my_hash = {}
pets = {"cat" => "Maru", "dog" => "spot", "fish" => "toby"}

Retrieving Data from Hashes

Similar to array but instead of index in [] we use key in [] (with quotes) ex: pets["cat"]


Adding Key/Values to Hashes

Instead of << we use bracket equals
person{"hometown"} = "Massena, NY"
hash["new_key"] = "new value"
