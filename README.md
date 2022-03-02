* Compile and run VGood, and this should not hang
* COmpile and run VBad, and for large input #s, it ought to hang
* This is because the store/load ordering is not respected w/o a volatile declaration
