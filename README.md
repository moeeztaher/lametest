# WAV to LAME command-line encoder

## Build requirements

* LAME
* sndfile
* C++17 compliant compiler
* CMake or meson


## Usage

Encode a directory of WAV files by passing the path as the first argument to the
command line:

    $ ./encoder <path-to-wav-files>

Log output can be influenced by setting the `CINEMO_LOG` environment variable,
to `debug`, `info`, `warn` or `error`, e.g. like this

    $ CINEMO_LOG=debug ./encoder <path-to-wav-files>


## Task

Your task is to extend the given encoder to make use of all CPU cores in order
to improve performance and throughput. There are no constraints other than that
the program has to work correctly and better than in the single-threaded case.


## Hints

You can find sample WAV files on [this website](https://www2.cs.uic.edu/~i101/SoundFiles).
