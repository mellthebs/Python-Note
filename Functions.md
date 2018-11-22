#### Python函数使用def来定义函数：

	def sign(x):
	    if x > 0:
 	       return 'positive'
 	   elif x < 0:
  	      return 'negative'
  	  else:
   	     return 'zero'
	
	for x in [-1, 0, 1]:
  	  print sign(x)
	# Prints "negative", "zero", "positive"
  
#### 我们常常使用可选参数来定义函数：

	def hello(name, loud=False):
	    if loud:
 	       print 'HELLO, %s' % name.upper()
 	   else:
  	      print 'Hello, %s!' % name
	
	hello('Bob') # Prints "Hello, Bob"
	hello('Fred', loud=True)  # Prints "HELLO, FRED!"
