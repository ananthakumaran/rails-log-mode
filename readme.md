# Rails Log Mode
Major mode for viewing Rails log files

## Installation

````cl
(add-to-list 'load-path "path/to/rails-log-mode/dir")
(require 'rails-log-mode)
````

## Usage

Run `M-x rails-log-show-development` from the project folder. This
will run `tail -f` in the development.log file and display the output in
a buffer. Press `Enter` to open the file in the stack trace.
