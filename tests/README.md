This is in addition to unit tests for individual go files (e.g. file `xyz.go` has a `xyz_test.go` file wih unit tests). 

Having a test folder where test results (e.g. `fuzzing` seed corpus files, coverage reports etc), bootstrapping, and integration tests are kept can be useful. With github actions artifacts could also be written to this folder.