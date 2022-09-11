# Arguments:
1.)Positional argument:Sequence/order of values matters. Here we need to supply same number of value as given while declaring the function.
Example:def info(name,age):
print('your name is:',name)
print('Your age is:',age)
info('Suhas',24)
info(31,'python')  bcz its positional hence,31 will be given to name and python will be age.
2.)Keyword: sequence/order of values doesn't matters
Example:info(age=31,name='python')  #keyword map values to its exact parameter
Default: Default arg we can supply in declaration only
def bank(name,branch,IFSC='SBI7700'): #here IFSC is a default arg, we can change it while using function but if we do not give any input it will consider default.
Variable length: *args and **kwargs
Rule: positional argument should nt follow keyword argument, we can specify/give a positional argument ONLY before Keyword argument
