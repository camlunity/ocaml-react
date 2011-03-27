(* OASIS_START *)
(* DO NOT EDIT (digest: c42b07c83a96987fd4773853151de9ea) *)
This is the README file for the React distribution.

Applicative events and signals for OCaml

See the files INSTALL.txt for building and installation instructions. See the
file LICENCE for copying conditions.

Home page: http://erratique.ch/software/react


(* OASIS_STOP *)


...............................................................................
React - Applicative events and signals for OCaml
        Release 0.9.2
...............................................................................

React is an OCaml module for functional reactive programming (frp). It
provides support to program with time varying values : applicative
events and signals. React doesn't define any primitive event or
signal, this lets the client chooses the concrete timeline.

React is made of a single, independent, module and distributed under
the new BSD license.

Project home page : http://erratique.ch/software/react
Contact : daniel.buenzl i@erratique.ch

test.native tests the combinators, nothing should fail.

clock.native is a command line program using ANSI escape sequences and
the Unix module to print the current local time.

breakout.native is a command line program using ANSI escape sequences
and the Unix module to implement a simple breakout game.
