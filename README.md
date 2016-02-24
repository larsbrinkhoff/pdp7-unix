# pdp7-unix
This is a project to resurrect Unix on the PDP-7 from a scan of the original
assembly code done by Norman Wilson.

Right now the scans are in the Unix Archive at
http://www.tuhs.org/Archive/PDP-11/Distributions/research/McIlroy_v0/
as the files 0*.pdf. We now need to convert these to machine-readable
assembly code, write tools such as an assembler, a filesystem creation tool,
and write from scratch missing things like a shell, ls etc.

scans/	  holds the unmodified OCR versions of the scanned files
src/cmd   holds the modified source code of the user-mode programs
src/sys   holds the modified source code of the kernel
tools/	  holds the source for the tools written to assist the project
