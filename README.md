# etcol

Erlang terminal colors

## Usage



	etcol:t(Lines) -> string()

 	%% Types:

	Lines = [ attr_line() ]
	attr_line() = { [attrs()], string() }
	attrs() = { text_attr, attr() } | { fg_color, color() } | { bg_color, color() } 
	color() = 'black' | 'red' | 'green' | 'yellow' | 'blue' | 'magenta' | 'cyan' | 'white'
	attr() = 'reset' | 'bright' | 'dim' | 'underscore' | 'blink' | 'reverse' | 'hidden'

## Demo

Try:

	> erlc ertcol
	> erl -noshell -run ertcol test


