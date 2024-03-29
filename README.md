# mathinterface library

mathinterfacelib is a C++ library to interact with symbolic mathematics software through a common interface.

## Dependencies
   * Boost (https://www.boost.org/)
   * LibXML2 (https://gitlab.gnome.org/GNOME/libxml2) - Required by Offline engine (XML mode).
   * MATIO (https://github.com/tbeu/matio) - Required by Matlab engine.

## Usage
   See tests/ directory for basic functionality tests of the library and applications/ for more extended examples


## Install
To run matwlib...
* ... with Octave...

* ... with Eigen ...

* ... with MATLAB installed in $(MATLAB_DIRECTORY) you need (to) ...

      1. csh (as "engOpen(NULL)" will open matlab by "/bin/csh -f -c matlab")
      2. Add matlab/bin dir to path variable (e.g. export PATH=$(MATLAB_DIRECTORY)/bin:$PATH)
