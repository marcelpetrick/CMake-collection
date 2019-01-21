cmake_minimum_required (VERSION 3.13)
message(STATUS "line 2")
#project ("fibonacci")
message(STATUS "line 4: after project")


function(fib n)
	message(STATUS "line 2")
	if(n GREATER 1)
		message(STATUS "-> if")
		# return (fib(n-1) + fib(n-2))
	
	else
		message(STATUS "-> else")
		# return 1; actually it should be
		
	endif
endfunction(fib)
