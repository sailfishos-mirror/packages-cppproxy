This file contains some examples of defining   and  using the C++ proxy.
Each example consists of a  .pl  and   .cpp  file.  To run the examples,
verify and possibly adjust the file parms.pl  that tell the system where
the Prolog libraries are to be found   and  how to compile an executable
from a C++ program.

To compile an example, load the .pl file   in Prolog and run the command
below. This generates the proxy code and compiles the client. The client
has the same base-name as the .pl and  .cpp files. On Windows it has the
.exe extension. To simplify debugging the   compilation of the client in
Windows swipl.exe must  be  used  to   preserver  the  C  compiler error
messages.

	?- make_client.

To run the demo start the server using   the command below and the start
the client in a separate window.  All   the  clients  are simple console
applications printing some results.

	?- start_server.

As only one server can live in a  Prolog process, stop the Prolog server
before trying the next demo.
