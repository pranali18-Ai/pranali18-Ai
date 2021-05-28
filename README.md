situation = "when door is open"
command = "turn on AC"


instruction =  'welcome to home! '+ situation + ' ,' + command + ' .'
print(instruction)

#format 
message = '{},{}.welcome!'.format(situation, command)

#or
message = f'{situation},{command.upper()}. welcome home!'
print(dir(command))
print(message)
print(help(str.lower))
