##   Makefile.am - Automake script for example/shell/foosh.
##
##   Copyright (c) 2014, Monaco F. J.  <monaco@usp.br>
##
##   This file is part of POSIXeg.
##
##   POSIXeg is free software: you can redistribute it and/or modify
##   it under the terms of the GNU General Public License as published by
##   the Free Software Foundation, either version 3 of the License, or
##   (at your option) any later version.
##
##   This program is distributed in the hope that it will be useful,
##   but WITHOUT ANY WARRANTY; without even the implied warranty of
##   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
##   GNU General Public License for more details.
##
##   You should have received a copy of the GNU General Public License
##   along with this program.  If not, see <http://www.gnu.org/licenses/>.

AM_CPPFLAGS = @CPP_FLAGS@ -Werror -Wno-unused-result
AM_CFLAGS =   @C_FLAGS@ 
AM_LDFLAGS =  @LD_FLAGS@ 

EXTRA_PROGRAMS = fillpipe busy back


all-local: $(EXTRA_PROGRAMS)

clean-local:
	rm -f $(EXTRA_PROGRAMS)
	rm -f @TEMPFILES@
