  ############################################################################
  ## 
  ##  AGENT++ 4.0 - Makefile.am  
  ## 
  ##  Copyright (C) 2000-2013  Frank Fock and Jochen Katz (agentpp.com)
  ##  
  ##  Licensed under the Apache License, Version 2.0 (the "License");
  ##  you may not use this file except in compliance with the License.
  ##  You may obtain a copy of the License at
  ##  
  ##      http:/www.apache.org/licenses/LICENSE-2.0
  ##  
  ##  Unless required by applicable law or agreed to in writing, software
  ##  distributed under the License is distributed on an "AS IS" BASIS,
  ##  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  ##  See the License for the specific language governing permissions and
  ##  limitations under the License.
  ##  
  ##########################################################################*

DEPS = $(top_builddir)/src/libagent++.la
LDADDS = $(top_builddir)/src/libagent++.la @LINKFLAGS@

AM_CPPFLAGS = -I$(top_builddir)/include -I$(top_srcdir)/include -I@srcdir@/../include $(PTHREAD_CFLAGS) @CLIBFLAGS@

noinst_PROGRAMS = agent_copy

agent_copy_SOURCES = 	agent_copy.cpp
agent_copy_LDFLAGS =
agent_copy_DEPENDENCIES =	$(DEPS)
agent_copy_LDADD =		$(LDADDS)
