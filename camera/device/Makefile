
OBJS = Device.o

include ../../Makefile.cfg
include ../../Makefile.src

CPPFLAGS = -O3 -fPIC -Wall -Wno-unused -D_POSIX_THREADS -fPIC \
	-D_POSIX_THREAD_SAFE_FUNCTIONS \
	-D_REENTRANT -DPOSIX -fPIC \
	-D__x86__ -D__linux__ \
	-D__OSVERSION__=2 -frepo -DUSINGTHREADS -DLINUX -D_GNU_SOURCE \
	$(PYTHON_INCLUDE) -shared

clean::
	$(RM) *~ *.so *.o

