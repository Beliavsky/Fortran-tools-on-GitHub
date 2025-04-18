### Fortran Tools on GitHub -- see [Fortran Tools](https://github.com/Beliavsky/Fortran-Tools/blob/main/README.md) for a list not restricted to GitHub

* [Automatic Documentation](#automatic-documentation)
* [Build Tools](#build-tools)
* [Compilers](#compilers)
* [Emacs Plugins](#emacs-plugins)
* [Fixed to Free Source Form Conversion](#fixed-to-free-source-form-conversion)
* [Indentation and Formatting](#indentation-and-formatting)
* [Interoperability](#interoperability)
* [Parallel Programming](#parallel-programming)
* [Preprocessors and Code Generation](#preprocessors-and-code-generation)
* [Profiling](#profiling)
* [Refactoring](#refactoring)
* [Static Analysis](#static-analysis)
* [Text Editors, Integrated Development Environments, and Plugins](#text-editors-integrated-development-environments-and-plugins)
* [Translation from Fortran](#translation-from-fortran)
* [Translation to Fortran](#translation-to-fortran)
* [Unclassified](#unclassified)
* [Unit Testing](#unit-testing)

### Automatic Documentation
[Doxygen](https://github.com/doxygen/doxygen): generates an on-line documentation browser (in HTML) and/or an off-line reference manual (in LaTeX) from a set of documented source files. There is also support for generating output in RTF (MS-Word), PostScript, hyperlinked PDF, compressed HTML, DocBook and Unix man pages. 

[f90tohtml](https://github.com/degeron/f90tohtml): Perl script to convert fortran source files into a hyperlinked web site

[ford](https://github.com/Fortran-FOSS-Programmers/ford): Automatically generates FORtran Documentation from comments within the code, from Fortran-FOSS-Programmers

### Build Tools
[easy](https://github.com/urbanjost/easy): steps to setup a GitHub repository with fpm, and GitHub actions including ford(1) documentation and unit tests, by urbanjost

[FCM](https://github.com/metomi/fcm): modern Fortran build system + wrappers to Subversion for scientific software development, from metomi

[FoBiS.py, Fortran Building System for poor people](https://github.com/szaghi/FoBiS): automatic parsing of files for dependency-hierarchy creation in case of use and include statements, and automatic building of all programs found into the root directory parsed or only a specific selected target, by szaghi et al.

[fortdepend](https://github.com/ZedThree/fort_depend.py): python script to generate dependencies for Fortran projects, by ZedThree

[fortrandep](https://github.com/orvedahl/fortrandep): Python tool to determine Makefile dependencies for a Fortran project, by Ryan Orvedahl

[fortranMakeUtils](https://github.com/deniseiras/fortranMakeUtils): Python 2.7 script for generating dependency tree and makefile, by deniseiras. Another script lowercases most Fortran keywords

[Fortran Package Manager for Visual Studio](https://github.com/everythingfunctional/fpm-for-VS): adds options and menu entries for building, running and testing your Fortran project using the Fortran Package Manager (fpm), by everythingfunctional

[Fortran Package Manager (fpm)](https://github.com/fortran-lang/fpm): package manager and build system for Fortran, from fortran-lang. Documentation is [here](https://awvwgk.github.io/fpm-docs/en/index.html)

[Fortran-reducer](https://github.com/IlyaShein/Fortran-reducer): takes a Fortran file that has a property of interest and automatically builds a hierarchy of used modules in that file and generates a compile line for all files, by Ilya Shein

[jams_makefile](https://github.com/mcuntz/jams_makefile): provides a portable, versatile way of compiling Fortran, C, C++, and mixed projects, by mcuntz

[makedepf90](https://github.com/outpaddling/makedepf90): generates make dependencies for Fortran code, by Erik Edelman

[makemake](https://github.com/janberges/makemake): Python script that generates Makefiles for modular Fortran programs, by Jan Berges. It recursively searches the working directory for .f90 files and determines their dependencies.

[meson](https://github.com/mesonbuild/meson): next-generation build system

[MinGW package for the Fortran package manager](https://github.com/awvwgk/mingw-w64-fpm-pkgbuild): provides package build instructions for the Fortran package manager (fpm) compatible with the MSYS2 toolchain. This project provides prebuilt MinGW packages at the release page. 

[mkhelper](https://github.com/skosukhin/mkhelper): collection of utilities to be used with GNU Autoconf and GNU Make for building Fortran projects, by skosukhin

[run-fortran](https://github.com/lycantropos/run-fortran): sorts Fortran files based on modules definitions and usages, by lycantropos

[xmake](https://github.com/xmake-io/xmake): lightweight cross-platform build utility based on Lua. It uses xmake.lua to maintain project builds. The two Fortran compilers supported are gfortran and ifort.

### Compilers
[f18-llvm-project](https://github.com/flang-compiler/f18-llvm-project): fork of llvm/llvm-project for f18. In sync with f18-mlir and f18.

[flang](https://github.com/flang-compiler/flang): flang (also known as "Classic Flang") is an out-of-tree Fortran compiler targeting LLVM. It is an open-sourced version of pgfortran, a commercial Fortran compiler from PGI/NVIDIA

[fortran-ios](https://github.com/ColdGrub1384/fortran-ios): script that acts like a Fortran compiler that uses Flang to build sources for iOS arm64, by Emma Cold

[Fortran kernel for Jupyter with Coarray support](https://github.com/sourceryinstitute/jupyter-CAF-kernel): from sourceryinstitute

[gfortran-for-macOS](https://github.com/fxcoudert/gfortran-for-macOS): gfortran for macOS Intel, by fxcoudert. Gfortran installation on various platforms is discussed at [fortran-lang](https://fortran-lang.org/learn/os_setup/install_gfortran).

[lfortran](https://github.com/lfortran/lfortran): modern open-source (BSD licensed) interactive Fortran compiler built on top of LLVM. It can execute user's code interactively to allow exploratory work (much like Python, MATLAB or Julia) as well as compile to binaries with the goal to run user's code on modern architectures such as multi-core CPUs and GPUs.

[Mercurium](https://github.com/bsc-pm/mcxx):  C/C++/Fortran source-to-source compilation infrastructure aimed at fast prototyping developed by the Programming Models group at the Barcelona Supercomputing Center. Mercurium is used, together with the Nanos++ Runtime Library, to implement the OmpSs programming model. Both tools provide also an implementation of OpenMP 3.1.

[ompi](https://github.com/open-mpi/ompi): open source Message Passing Interface (MPI) implementation that is developed and maintained by a consortium of academic, research, and industry partners

[Quickstart Fortran on Windows](https://github.com/LKedward/quickstart-fortran): easy Windows installer and launcher for GFortran and the Fortran Package Manager, by Laurence Kedward. The optimized OpenBLAS library is included with the GCC installation.

[ROSE](https://github.com/rose-compiler/rose): compiler infrastructure to build source-to-source program transformation and analysis tools for large-scale C (C89 and C98), C++ (C++98 and C++11), UPC, Fortran (77/95/2003), OpenMP, Java, Python and PHP applications

[xcc-project](https://github.com/JianpingZeng/xcc-project): C/C++/Fortran compiler collection written in Java, by JianpingZeng

### Emacs Plugins
[align-f90](https://github.com/jannisteunissen/align-f90): alignment support for Fortran 90 in Emacs, by jannisteunissen

[Emacs](https://github.com/emacs-mirror/emacs): extensible, customizable, free text editor. Download [here](https://www.gnu.org/software/emacs/download.html).

[f90-iface](https://github.com/wence-/f90-iface): Emacs-based browser for Fortran 90 generic interfaces, by wence- and monnier

[f90-namelist-mode](https://github.com/ZedThree/f90-namelist-mode): extension to Emacs f90-mode to handle Fortran namelists, by ZedThree

[fortpy](https://github.com/rosenbrockc/fortpy): Python Emacs Intellisense and Unit Testing Support for Fortran, by rosenbrockc and wsmorgan

[fortpy-el](https://github.com/rosenbrockc/fortpy-el): Lisp package for emacs that integrates with fortpy to provide context-specific auto-completion and intellisense for Fortran 2003, including object oriented constructs, by rosenbrockc

[fortran-index-args](https://github.com/ffevotte/fortran-index-args): numbers subroutine arguments and shows indexes before each argument in the list, by ffevotte. Such indexes are just displayed on screen, but do not modify the underlying buffer.

[Fortran layer](https://github.com/ciappi/fortran-layer): basic Spacemacs configuration layer for the Fortran language, by Marco Scopesi

[Fortran-tags](https://github.com/raullaasner/fortran-tags): Fortran source code indexing tool with the focus of finding the definition of any variable or procedure, by raullaasner et al. It is able to correctly locate all global and local variables and is expected to work with any Fortran 2008 conforming code with some exceptions as mentioned below.

[fprettify.el](https://github.com/osada-yum/fprettify.el): interface to fprettify, auto-formatter for modern Fortran code, by osada-yum

### Fixed to Free Source Form Conversion
[f2f](https://github.com/MRedies/f2f_mirror): Perl script which does much of the tedious work of converting FORTRAN 77 source code into modern Fortran, by Colby Lemon

[f77tof90](https://github.com/mattdturner/f77tof90): Python script that reads in a Fortran 77 (.f or .F) fixed form file and converts it to a free form Fortran 90 file (.f90 or .F90), by mattdturner. It was successfully used to convert a legacy codebase (over 400 .f/.F files and millions of lines of code) from Fortran 77 to Fortran 90.

[FORTRAN77_to_Fortran90](https://github.com/Koushikphy/FORTRAN77_to_Fortran90): convert old fixed source FORTRAN 77 code to free form Fortran 90 code, by Koushikphy

[fortran-legacy-tools](https://github.com/ylikx/fortran-legacy-tools): tools to deal with Fortran code: fixed to free source form converter, upper- to lowercase converter, formatter for variable declarations, by ylikx

[freestyle](https://github.com/bast/freestyle): script to convert fixed form Fortran files (written in Fortran 77) and header files to free form, by bast

[GConvert](https://github.com/GeorgeTsikas/GConvert): program to convert fixed form Fortran into code that works as fixed or free form, by GeorgeTsikas.

[to_f90](https://github.com/jbdv-no/to_f90) Alan Miller's tool for converting Fortran 77 code to free-form Fortran 90 code, from jbdv-no

### Indentation and Formatting
[ajt-fortran.vim](https://github.com/robertodr/ajt-fortran.vim): port of Ajit J. Thakkar's Vim indent script

[findent](https://github.com/MFTabriz/findent): indent and convert Fortran sources, by wvermin and MFTabriz

[FortranIndent](https://github.com/Kairzhan/FortranIndent): tools to indent Fortran 90 sources, from Kairzhan

[fprettify](https://github.com/pseewald/fprettify): auto-formatter for modern Fortran code that imposes strict whitespace formatting, written in Python, by pseewald

[IndentPatternFortran](https://github.com/JHenneberg/IndentPatternFortran): general indentation patterns for Fortran, by JHenneberg

[Stylist](https://github.com/MetOffice/stylist): code style checking tool built on a framework which supports multiple styles across multiple languages, by Matthew Hambley et al.

### Interoperability
[BindTo](https://cbfortran.sourceforge.io/bindto/): tries to make the communication with Fortran code from the outside more easily by automatically generating the required wrapping code. An intrinsic “iso_c_binding” module is used. In addition to the exposing Fortran code to C, BindTo can generate Cython files, which enable calling Fortran from Python. 

[Cython fortran-file](https://github.com/cphyc/cython_fortran_file): fast and easy reader for record-based binary format, as written by Fortran, by Corentin Cadiou

[F2x](https://github.com/DLR-SC/F2x): versatile, template-based Fortran wrapper written in Python. Compared to the popular tool f2py it comes with two important differences: a full Fortran parser based on the work by the OpenFortranParser, and a very flexible code generation backend that uses Jinja2 templates.

[f90wrap](https://github.com/jameskermode/f90wrap): Fortran 90 to Python interface generator with derived type support, by jameskermode et al.

[FORTRAN format interpreter for Python (py-fortranformat)](https://github.com/brendanarnold/py-fortranformat): Generates text from a Python list of variables or will read a line of text into Python variables according to the FORTRAN format statement passed, by Brendan Arnold and michaelackermannaiub

[FortranNamelist](https://github.com/jonathanschilling/FortranNamelist): Java reading class for Fortran namelists, by Jonathan Schilling

[Fortran Namelist Reader](https://github.com/scivision/fortran-namelist): Python and Matlab readers for Fortran namelist => dict / struct, from scivision

[fpydemo](https://github.com/banskt/fpydemo): demonstration of packaging a command line tool written in Python and Fortran, by Saikat Banerjee

[gfort2py](https://github.com/rjfarmer/gfort2py): library to allow calling Fortran code compiled with gfortran from Python 2.7 or Python 3, by Robert Farmer and Ondřej Čertík

[multilingual-julia](https://github.com/ahbarnett/multilingual-julia): minimally complete examples of Julia calling and being called by Fortran, C, and Python, by Alex Barnett

[Mwrap](https://github.com/zgimbutas/mwrap): interface generation system in the spirit of SWIG or matwrap, by Zydrunas Gimbutas et al. From a set of augmented MATLAB script files, MWrap will generate a MEX gateway to desired C/C++/Fortran function calls and MATLAB function files to access that gateway. [Mwrapdemo](https://github.com/ahbarnett/mwrapdemo) by Alex Barnett contains simple, minimally complete examples showing how to use MWrap to link to a C or Fortran library, pass in and out 1D and 2D arrays, handle complex, float, and Boolean types, and use OpenMP.

[shroud](https://github.com/LLNL/shroud): creates a Fortran or Python interface to a C or C++ library, from LANL. It can also create a C API for a C++ library.

### Parallel Programming
[allgebra](https://github.com/ricosjp/allgebra): docker images for developing C++ and Fortran HPC programs, by termoshtt and t-hishinuma

[gpufort](https://github.com/ROCmSoftwarePlatform/gpufort): source-to-source translation tool for CUDA Fortran and Fortran+X in the spirit of [hipify](https://github.com/ROCm-Developer-Tools/HIPIFY)

[hip-fortran](https://github.com/FluidNumerics/hip-fortran): Fortran layer for AMD HIP to enable GPU acceleration on Nvidia and AMD GPUs, by Joe Schoonover. 

[hipfort](https://github.com/ROCmSoftwarePlatform/hipfort): Fortran Interface For GPU Kernel Libraries

[mpich](https://github.com/pmodels/mpich): high-performance and widely portable implementation of the
MPI-3.1 standard from the Argonne National Laboratory

[Omni Compiler](https://github.com/omni-compiler/omni-compiler): compiler for code including XcalableMP, XcalableACC, and OpenACC directives. The base languages supported by Omni Compiler are C language (C99) and Fortran 2008 in XcalableMP, and C language (C99) in XcalableACC and OpenACC.

[OpenCoarrays](https://github.com/sourceryinstitute/opencoarrays): supports Fortran 2018 compilers by providing a parallel application binary interface (ABI) that abstracts away the underlying parallel programming model, which can be the Message Passing Interface (MPI) or OpenSHMEM, 
from sourceryinstitute

[Traits Static Analyzer (TSAR)](https://github.com/dvm-system/tsar): part of a system for automated parallelization [SAPFOR](https://github.com/dvm-system/sapfor). The main goal of analyzer is to determine data dependences, privatizable, reduction and induction variables and other traits of analyzed program which could be helpful to parallelize program in automated way. 

### Preprocessors and Code Generation
[f90 do nest](https://github.com/hattom/f90_do_nest): Python script to generated deeply nested do loops in Fortran, by Thomas Hayward-Schneider. It will generate "classical" nested do/enddo in f90code.F90 and also a do concurrent version in f90code_conc.F90.

[fortiel](https://github.com/Jhuighuy/fortiel): Fortran preprocessor and metaprogramming engine, by Jhuighuy

[fypp](https://github.com/aradi/fypp): Python-powered preprocessor, by aradi. It can be used for any programming languages but its primary aim is to offer a Fortran preprocessor, which helps to extend Fortran with condititional compiling and template metaprogramming capabilities

[prep](https://github.com/urbanjost/prep): Fortran pre-processor written in Fortran, by urbanjost

### Profiling
[Caliper](https://github.com/LLNL/Caliper): library to integrate performance profiling capabilities into applications, from LANL. To use Caliper, developers mark code regions of interest using Caliper's annotation API. Applications can then enable performance profiling at runtime with Caliper's configuration API.

[Quasi-Aspect-Weaving Approach (QAWA) Fortran Code Profiler](https://github.com/SokolAK/QAWA-Fortran-Code-Profiler): Python-based framework for profiling Fortran source code, by Adam K. Sokół. One can use it to track the control flow, show call chains and measure the execution time of procedures.

[timemory](https://github.com/NERSC/timemory): performance measurement and analyis package with modular and reusable components which can be used to adapt to any existing C/C++ performance measurement and analysis API and is arbitrarily extendable by users within their application, from NERSC

### Refactoring
[Fortran Language Program Remodeling system (FLPR)](https://github.com/lanl/FLPR):  C++17 library for manipulating Fortran source code, from LANL. This package contains a "best effort" Fortran 2018 input parser for fixed and free form inputs, data structures for manipulating source code at the program unit, statement, and physical line levels, and sample applications that illustrate usage and provide some ideas as to how you could use the library.

[Glasgow Fortran Source-to-Source Compiler (RefactorF4Acc)](https://github.com/wimvanderbauwhede/RefactorF4Acc): automatic refactoring tool to make Fortran code acceleration-ready, by wimvanderbauwhede and rouson. RefactorF4Acc's main purpose is to make legacy FORTRAN 77 acceleration-ready. In the process it converts FORTRAN 77 code into Fortran 95. In addition, RefactorF4Acc has a backend to translate modules to C/OpenCL.

[Fortran Kernel Generator: KGen](https://github.com/NCAR/KGen): Python tool that extracts partial codes out of a large Fortran application and converts them into a standalone/verifiable/executable kernel, by Youngsung Kim and John Dennis

[fortrantools](https://github.com/CodethinkLabs/fortrantools): tools to enable the use old or proprietary Fortran code with gfortran. They are intended to be used together with the gcc extensions in CodethinkLab's gcc branch.

### Static Analysis
[camfort](https://github.com/camfort/camfort): refactoring and verification tool for scientific Fortran programs. It currently supports Fortran 66, 77, and 90 with various legacy extensions.

[Code Comprehension Assistance for Evidence-Based performance Tuning (CCA/EBT)](https://github.com/ebt-hpc/cca-ebt): extracts the syntactic/semantic structures from Fortran code and then provides outline views of the loop-nests and the call trees decorated with source code metrics.

[flint](https://github.com/JonasToth/flint): Little linter for Fortran, with static analysis and formatting, by JonasToth

[flint](https://github.com/marshallward/flint): aspires to be a Fortran parser, delinter, and analyser, by marshallward. For now, it is a Fortran tokenizer, with tools for parsing and automated documentation.

[fortlint](https://github.com/ratnania/fortlint): Fortran static source code analysis for more secured and bug free applications

[FortranAnalyser](https://fortrananalyser.ephyslab.uvigo.es/): multi-language static analysis tool cross-platform under GPLv3 licence that measures the quality of the software for maintenance and refactoring for all versions of Fortran. An associated paper is [Assessing and improving the quality of Fortran code in scientific software: FortranAnalyser](https://www.sciencedirect.com/science/article/pii/S2665963824000800), by Michael García-Rodríguez et al., <i>Software Impacts</i> (2024).

[fortrancallgraph](https://github.com/fortesg/fortrancallgraph): static source code analysis for Fortran, tracking variables in a routine's callgraph, from fortesg

[fortran-callgraph](https://github.com/hydro-jules/fortran-callgraph): Tool to create call graphs from JULES source code

[FORTRAN_callgraph_browser](https://github.com/cemac/FORTRAN_callgraph_browser): browsing tool that reads in a directory of Fortran code and displays it as an interactive graph, by Dan Ellis and Richard Rigby

[Fortran code quality](https://github.com/eirik-kjonstad/fortran-code-quality): simple Python script that parses Fortran files and gives feedback on a few metrics relating to code quality, by Eirik F. Kjønstad and Sander Roet

[Fortran linter](https://github.com/cphyc/fortran-linter): simple fortran syntax checker, including automatic fixing of the code, from cphyc

[fortran-linter](https://github.com/uchchwhash/fortran-linter): linter for Fortran 77 using Parsec-like parsing combinators in Python, by uchchwhash

[fortran_python_tools](https://github.com/jinyun1tang/fortran_python_tools): analyzes the variable usage of fixed source form Fortran 77 code, by jinyuntang

[FortranTree](https://github.com/imaliyov/FortranTree): parses Fortran source code and creates a call tree graph with Python, by imaliyov. The code relies on pygraphviz and fparser.

[fortran-vars](https://github.com/camfort/fortran-vars): static analysis library for Fortran code. It is built on top of the open source project fortran-src which provides lexing, parsing and basic analyses of Fortran code. Fortran-vars focuses on supporting the Fortran 77 standard and extensions. It provides a Fortran memory model with a symbol table and storage table, constant expressions evaluation, constant propagation analysis.

[fsource](https://github.com/mwallerb/fsource): Fortran static analysis tool written in pure Python, by mwallerb

[i-CodeCNES](https://github.com/cnescatlab/i-CodeCNES): static code analysis tool to help developers write code compliant with CNES coding rules for Fortran 77, Fortran 90 and Shell, from cnescatlab

[K-scope](https://github.com/K-scope/K-scope): source code analysis tool with graphical user interface that visualizes program structures for Fortran 90 and FORTRAN 77 source code. This tool simply visualizes call tree from AST based on compiler's static analysis.

[Simple Lint GitHub Action (simple_lint)](https://github.com/NOAA-GFDL/simple_lint): runs simple lint-like actions on files in a git repository, from NOAA-GFDL. The current list of lint actions are to check for trailing whitespace, check Fortran files for use of tab characters, and check Fortran files for lines longer then a specified length.

### Text Editors, Integrated Development Environments, and Plugins
[atom-build-fpm](https://github.com/everythingfunctional/atom-build-fpm): plugin for running the Fortran Package Manager (fpm) from within Atom

[Code::Blocks](https://www.codeblocks.org/): free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable.

[linter-gfortran](https://github.com/AtomLinter/linter-gfortran): linting Fortran code in [Atom](https://github.com/atom) with gfortran

[Fortran IntelliJ Idea plugin](https://github.com/satamas/fortran-plugin): Fortran language plugin for IntelliJ Idea, by satamas

[Fortran Language Server](https://github.com/hansec/fortran-language-server): A Fortran implementation of the Language Server Protocol using Python (2.7+ or 3.0+), by hansec. Editor extensions using this language server to provide autocomplete and other IDE-like functionality are available for Atom, Visual Studio Code, Visual Studio, (Neo)vim, and Emacs.

[fortls](https://github.com/gnikit/fortls): implementation of the Language Server Protocol (LSP) for Fortran using Python (3.7+), by Giannis Nikiteas. Editor extensions that can integrate with fortls to provide autocomplete and other IDE-like functionality are available for Visual Studio Code, Atom, Visual Studio, (Neo)vim, and Emacs. This project is based on @hansec's Fortran Language Server, but the two projects have since diverged.

[fortran.tmbundle](https://github.com/textmate/fortran.tmbundle): TextMate support for Fortran. TextMate is a graphical text editor for macOS 10.12 or later.

[fossil](https://github.com/nrwade0/Fossil): Fortran IDE designed in Python by someone eager to learn Fortran but in an easy and accessible way, by nrwade0

[Modern-Fortran](https://github.com/eirik-kjonstad/modern-fortran-syntax): language syntax for highlighting of Fortran code in [Sublime Text](https://www.sublimetext.com/), by eirik-kjonstad. It highlights modern Fortran (Fortran 90 and newer) and incorporates features introduced in Fortran 2003, 2008, and 2018.

[neovim](https://github.com/neovim/neovim): Vim-fork focused on extensibility and usability

[SublimeLinterFortran](https://github.com/Panadestein/SublimeLinterFortran): linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) provides an interface to gfortran, by Ramón L. Panadés-Barrueta and Tejas Shetty. It will be used with files that have free format Fortran syntax. 

[vim](https://github.com/vim/vim): improved version of the UNIX editor Vi. Many new features have been added: multi-level undo, syntax highlighting, command line history, on-line help, spell checking, filename completion, block operations, script language, etc. Download [here](https://www.vim.org/download.php). 

[vimf90](https://github.com/rudrab/vimf90): Fortran ide for vim

[vim-findent](https://github.com/cradesto/vim-findent): vim plugin for [Findent](https://github.com/MFTabriz/findent), which indents Fortran sources, by cradesto

[vim-tmux-IDE](https://github.com/luco00/vim-tmux-IDE): minimal vim IDE by luco00. Sets a connection with external terminal via tmux to interactively execute code (Python, R, Julia, Fortran, Go are supported).

[Visual Studio Code (vscode)](https://github.com/microsoft/vscode): combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle, from Microsoft. It provides comprehensive code editing, navigation, and understanding support along with lightweight debugging, a rich extensibility model, and lightweight integration with existing tools.

[vscode-fortran-support](https://github.com/krvajal/vscode-fortran-support): extension that provides support for the Fortran programming language. It includes syntax highlighting, debugging, code snippets and a linting based on gfortran.

[vscode-modern-fortran-formatter](https://github.com/yukiuuh/vscode-modern-fortran-formatter): formatter extension for modern Fortran using fprettify, by Yuki Hanayama

### Translation from Fortran
[f2c](https://github.com/juanjosegarciaripoll/f2c): convert Fortran 77 to C

[f2cpp](https://github.com/victorliu/f2cpp): Converts Fortran 77 code to C++, by victorliu. Unlike f2c, the output of f2cpp.pl may or may not compile, however, only a small number of hand-tuned changes are typically needed. The resulting code is much cleaner than f2c's output, and much closer to the original intent of the original Fortran code.

[f2j](https://github.com/jonathanschilling/f2j): translate Fortran 77 to Java, especially for BLAS, LAPACK and ARPACK

[f2matlab](https://github.com/benbarrowes/f2matlab): converts Fortran 90 code to Matlab m-files, by benbarrowes. Only basic data types and constructions are recommended.

[f4go](https://github.com/Konstantin8105/f4go): Transpiling Fortran code to golang code, by Konstantin8105

[fortran2julia](https://github.com/algorithmx/fortran2julia): Python script to translate Fortran 90 to Julia, by algorithmx

### Translation to Fortran
[c2f](https://github.com/Beliavsky/c2f): partial C to Fortran translator by David Frank

[matlab2fortran](https://github.com/ebranlard/matlab2fortran): performs some simple conversions from Matlab code to Fortran, by ebranlard

[Mc2For](https://github.com/Sable/Mc2For): MATLAB to Fortran compiler, from Sable

[pyccel](https://github.com/pyccel/pyccel): Pyccel can be viewed as a Python-to-Fortran/C converter or a compiler for a Domain Specific Language with Python syntax

### Unclassified
[automates](https://github.com/ml4ai/automates): Automated Model Assembly from Text, Equations, and Software, from ml4ai

[fortran-sigwatch](https://github.com/scivision/fortran-sigwatch): library of routines to provide simple signal watching for Fortran programs, originally by Norman Gray, modified by Michael Hirsch. This allows a minimal level of control of a running program from outside it, for example to tell it to checkpoint itself on receipt of a signal.

[FORTRAN Testing Framework (FTFramework)](https://github.com/agforero/FTFramework): collection of Python and Bash scripts to enable easy testing of Fortran compilers using BATS, by agforero

[irep](https://github.com/LLNL/irep): tool for filling C/C++ or Fortran data structures from Lua input tables, from LLNL

[nmltab](https://github.com/aekiss/nmltab): Python 3 module and command-line tool to tabulate, semantically diff, superset and consistently format Fortran namelist files, with output to text, markdown, csv, latex and namelists, by Andrew Kiss and Aidan Heerdegen. Requires Python 3.4 or later, and f90nml (amongst other packages).

[nml-to-f90](https://github.com/perrette/nml-to-f90): generates Fortran source code for handling parameter I/O from a namelist, by perrette

[OpenAD](https://github.com/Augertron/OpenAD): tool for automatic differentiation (AD) of numerical computer programs

### Unit Testing
[fortran-testanything](https://github.com/dennisdjensen/fortran-testanything): test library supporting the Test Anything Protocol (TAP) inspired by Perl's Test::More module, by dennisdjensen

[FortranTestGenerator](https://github.com/fortesg/fortrantestgenerator): automatically generates unit tests for subroutines of existing Fortran applications based on an approach called Capture & Replay, from fortesg

[fortran-unit-test](https://github.com/dongli/fortran-unit-test): unit test library in Fortran to encourage scientific programmer to write tests, by dongli

[Fortran_UnitTest](https://github.com/zhenkunl/Fortran_UnitTest): unit test library based on OOP, by zhenkunl. It is strongly inspired by Zofu, and its output format is derived from [fortran-unit-test](https://github.com/dongli/fortran-unit-test).

[Fortran Unit Test Library](https://github.com/zhenkunl/Fortran_UnitTest): pure Fortran library using Object-Oriented Programming (OOP), by zhenkunl. It is strongly inspired by [Zofu](https://github.com/acroucher/zofu), and its output format is derived from [fortran-unit-test](https://github.com/dongli/fortran-unit-test). 

[FRUIT](https://github.com/mortele/FRUIT): Fortran unit test framework in Ruby, by mortele and michaelkonecny 

[fytest](https://github.com/aradi/fytest): lightweight unit testing framework for Fortran, by aradi. Thanks to its header-only design, it can be easily bundled with any Fortran project without creating extra dependencies.

[pFUnit](https://github.com/Goddard-Fortran-Ecosystem/pFUnit): unit testing framework enabling JUnit-like testing of serial and MPI-parallel software written in Fortran, from Goddard-Fortran-Ecosystem. Limited support for OpenMP is also provided in the form of managing exceptions in a thread-safe manner.

[tap](https://github.com/gzahl/tap): minimal producer implementation of the "Test Anything Protocol" (TAP) in Fortran 90, from gzahl

[test-drive](https://github.com/awvwgk/test-drive): lightweight, procedural unit testing framework based on nothing but standard Fortran, by awvwgk. Integration with meson, cmake and Fortran package manager (fpm) is available.

