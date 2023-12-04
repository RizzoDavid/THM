# Hydra is Coming to Town

This day will involve cracking passwords and how the complexity of those passwords changes the ability to crack them. Crunch will be used to generate passwords and hydra will be used to systematically test passwords. 

## Background Knowledge

### Brute Force

#### Combination Possibility

How many possible pin codes of 4 digits are there? 

Mathematically there are 10<sup>4</sup>. That makes 10,000 possible different pin codes. Each digit has a possibility of 10 diffent values and the pin is 4 values long. If we suppose there are still 4 possible values; however, each value can either be a digit (0-9), a lowercase letter (a-z), or and uppercase letter (A-Z). That makes 10 digits, 26 lower case and 26 uppercase. This means that each value could be one of 62 different options. This would then be expressed as 62<sup>4</sup>, or 14,776,336 possible combinations. Adding symbols makes the passoword more complex y adding another 30 possible characters to a single value. Increasing password length also increases how many possible combinations there are.   

#### Time

How long does it take to crack a password? 

Assuming a computer can try 1,000 passwords a second, that is 1 password every 0.001 seconds. 62<sup>4</sup>x0.001=14,776 seconds. 1 Hour eqauls 3600 seconds. 14,776 / 3600 = 4.1 hours. It would take 4 hours at that rate. That is 4 hours to go through every possible combinations. Relaisticly the combination would be somehwere in the middle meaning the time would be around 2 hours. This makes 4 digits pin codes relativly unsecure. Systems generally would not allow for this type of brute force because of lock out policies. With the pasword hash, the time is only limited by the resources of the computer since the cracking is all done 'offline'. 

## Capstone

