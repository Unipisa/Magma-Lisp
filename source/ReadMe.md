# MAGMA-Lisp

MAGMA-Lisp was designed as a language to implement A.I. programming systems that exploit nondeterminism and complex control regimes.

The simplest view of nondeterministic programming is that at each choice-point as many new computation environments are created as the alternatives to be explored are, giving raise to the *context tree*. MAGMA-Lisp brings the context tree to the foreground and gives complete control on its evolution to the programmer, rather than implementing some specific policy.

The computation environments provided by MAGMA-Lisp differ from that of standard LISP since, *within each context*, it is possible to depart from the normal LIFO discipline of LISP and define more complex control regimes, like *coroutines* etc.

The main departure from LISP is in *apply*, which has more arguments than usual, to specify the environment, the return point and the context to be used to apply the function to its arguments.

This directory contains an excerpt of the latest version of the source code of the Magma-Lisp system, comprising the control structures peculiar to the system and the garbage collector.

The code is in two folders, one for the control and contexts features and one for the garbage collector. Of the four authors, Maria Simi wrote the garbage collector, Carlo Montangero, Giuliano Pacini and Franco Turini the other files.

For more information on the development of the system look at [Magma-Lisp Story](**to be filled**)

Information on the acquisition of this code can be found in the [Magma-Lisp-Workbench](https://github.com/Unipisa/Magma-Lisp-Workbench) repository.
