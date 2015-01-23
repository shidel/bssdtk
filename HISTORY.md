1.0.0:
	+ Created lodbsdk to replace old jstoolkit project
	+ Created basic toolkit Testing scripts
	+ renamed to bssdtk (Bash Shell Scripting Development Toolkit)
	+ rename toolkit testing scripts to meet new project name
	+ rename toolkit primary base file to core
	+ updated build data files to reflect project rename
	+ added default signal events
	+ added registerOnExitEvent
	+ added pushStack & popStack
	+ added toolkit true directory detection & Global Variable Demo
	+ added defaultIgnoreEvent, assigned OnErrorEvent to it because functions that return 
		non-zero generate an error.
	+ added require, requireOnce, include, includeOnce functions for including scripts sources
	+ added registerExternals
	+ added registerInternals to override external programs
	+ added uppercase, lowercase & capitalize string routines.
	+ added lpadchar, rpadchar, lpad, rpad, zpad, ltrim, rtrim and nzpad
	+ added pipe routines
	+ created automatic function listing and help generation
	+ added terminal height and width detection
	+ modified output for bssdtk -l for terminal width
	+ renamed stack routines to be more compliant with new naming convention
	+ renamed string routines to be compliant with new naming convention
	+ added compatibility library with linux-gnu for CentOS
	+ added proc library, and fore/background process state detection
	+ added pipeOneLine & pipeMultiLine functions
	+ added decimal padding to padZero and removed padNoZero function since padZero will 
	remove padding before apply new pad values.
	+ performance enhancement, by forcing internal use of echo when -n switch is not used.
	Causing 1x-10x performance boost.
	+ changed bssdtk tool include to automatically prefer its own copy of bssdtk over 
	any installed versions.
	+ moved most event trapping functionality into separate library.
	+ moved help system from bssdtk generic utility into it's own library.
	+ added pipeOnlyLines function
	+ Streamlining and enhancements to integrated help system.
	+ Added setDistribution for creating OS_TITLE & OS_VERSION globals
	+ Added debugSnapshot and debugCompare
	+ Added echoError function.
	+ Added Color Reset on exit when color library is being used.
	+ created xml library
	+ project moved to GutHub