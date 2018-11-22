# Python-Note
My own note of python


hw12 = '%s %s %d' % (hello, world, 12)  # sprintf style string formatting

print hw12  # prints "hello world 12"

s = "hello"

print s.capitalize()  # Capitalize(首字母大写) a string; prints "Hello"

print s.upper()       # Convert a string to uppercase（大写）; prints "HELLO"

print s.rjust(7)      # Right-justify（右对齐） a string, padding with spaces; prints "  hello"

print s.center(7)     # Center a string, padding with spaces; prints " hello "

print s.replace('l', '(ell)')  # Replace all instances of one substring with another（将一个子字符串的所有实例替换为另一个）;

                               # prints "he(ell)(ell)o"
                               
print '  world '.strip()  # Strip leading and trailing whitespace（剥离前导和尾随空格）; prints "world"

