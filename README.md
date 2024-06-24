# Pulley Coding Challenge
Pulley challenges would-be employees to `utilize an API end point to complete a coding challenge.  After each successful hit of the end point candidates are asked to utilize the information given to solve what endpoint they need to hit next.  There isn't a pattern to how the JSON returns the way in which the data has been ciphered, just a text string explaining.  I had anticipated a certain uniformity when I started, that just wasn't there. Was definitely a more interesting way to offer the coding challenge for an interview process.

It's not the prettiest, but I got through it and got to practice some Python in the process.  

# Level 0
```JSON
{'challenger': 'damian@damianhall.net', 'encrypted_path': 'task_3db33349dec1a41258071c96e39bddd5', 'encryption_method': 'nothing', 'expires_in': '60s', 'hint': 'go to /task_3db33349dec1a41258071c96e39bddd5 to get the next challenge', 'instructions': 'encrypted_path is the path to your next challenge. encryption_method is how it was encrypted.', 'level': 0}
```
nothing on task_3db33349dec1a41258071c96e39bddd5
https://ciphersprint.pulley.com/task_3db33349dec1a41258071c96e39bddd5

# Level 1
```JSON
{'challenger': 'damian@damianhall.net', 'encrypted_path': 'task_[50,98,51,55,101,97,50,99,102,100,54,57,49,51,97,48,55,98,100,49,98,101,48,53,52,98,97,54,102,48,102,101]', 'encryption_method': 'converted to a JSON array of ASCII values', 'expires_in': '15s', 'hint': 'you should write a program to fetch these endpoints and handle each encryption method you find.', 'instructions': 'encrypted_path is the path to your next challenge. encryption_method is how it was encrypted.', 'level': 1}
```
converted to a JSON array of ASCII values on [50,98,51,55,101,97,50,99,102,100,54,57,49,51,97,48,55,98,100,49,98,101,48,53,52,98,97,54,102,48,102,101]

https://ciphersprint.pulley.com/task_2b37ea2cfd6913a07bd1be054ba6f0fe

# Level 2
```JSON
{'challenger': 'damian@damianhall.net', 'encrypted_path': 'task_6c8ifgdal6be98cc9d21beejb76hkf4295c9c1', 'encryption_method': 'inserted some non-hex characters', 'expires_in': '1s', 'hint': 'you should write a program to fetch these endpoints and handle each encryption method you find.', 'instructions': 'encrypted_path is the path to your next challenge. encryption_method is how it was encrypted.', 'level': 2}
```
inserted some non-hex characters on 6c8ifgdal6be98cc9d21beejb76hkf4295c9c1
https://ciphersprint.pulley.com/task_6c8fda6be98cc9d21beeb76f4295c9c1

# Level 3
```JSON
{'challenger': 'damian@damianhall.net', 'encrypted_path': 'task_7786d0cf647e96b8263fca4f6de91049', 'encryption_method': 'circularly rotated left by 0', 'expires_in': '1s', 'hint': 'you should write a program to fetch these endpoints and handle each encryption method you find.', 'instructions': "we've been alerted that you reached level 3, keep going!", 'level': 3}
```
circularly rotated left by 0 on 7786d0cf647e96b8263fca4f6de91049
https://ciphersprint.pulley.com/task_7786d0cf647e96b8263fca4f6de91049

# Level 4
```JSON
{'challenger': 'damian@damianhall.net', 'encrypted_path': 'task_7799c8b650e5bf634f7684506505aaad', 'encryption_method': 'encoded it with custom hex character set 13467fe89a0d5cb2', 'expires_in': '1s', 'hint': 'you should write a program to fetch these endpoints and handle each encryption method you find.', 'instructions': "we've been alerted that you reached level 4, keep going!", 'level': 4}
```
encoded it with custom hex character set 13467fe89a0d5cb2 on 7799c8b650e5bf634f7684506505aaad
https://ciphersprint.pulley.com/task_4488d7e3ca6ce531254372ca3cac999b

# Level 5
```JSON
{'challenger': 'damian@damianhall.net', 'encrypted_path': 'task_53cccb0883a9750eadc2b2a647bc81c', 'encryption_method': 'scrambled! original positions as base64 encoded messagepack: 3AAfHhsdDxkEBQIIGhYOFBwYCxcJEBEBFQ0HAAwGChITAw==', 'expires_in': '1s', 'hint': 'you should write a program to fetch these endpoints and handle each encryption method you find.', 'instructions': "we've been alerted that you reached level 5, keep going!", 'level': 5}
```
scrambled! original positions as base64 encoded messagepack: 3AAfHhsdDxkEBQIIGhYOFBwYCxcJEBEBFQ0HAAwGChITAw== on 53cccb0883a9750eadc2b2a647bc81c
https://ciphersprint.pulley.com/task_4b8cb0b68dce7a9cc28172aa0c335c5

# Level 6
```JSON
{'challenger': 'damian@damianhall.net', 'encrypted_path': 'task_a5ed6069dbfeecb43bb974458b6e679e0efd26688f786bf06df465a5e8eeff24', 'encryption_method': 'hashed with sha256, good luck', 'expires_in': '10000000s', 'hint': 'this is a gimmick, there is no way to solve this task.', 'instructions': "we've been alerted that you reached level 6, congratulations!", 'level': 6}
```
hashed with sha256, good luck on a5ed6069dbfeecb43bb974458b6e679e0efd26688f786bf06df465a5e8eeff24
I DON'T KNOW WHAT TO DO